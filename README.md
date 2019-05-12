# git-badges
github badge links for README.md

git-badges are picture marks which you need to show your projects progresses with.
Use git-badges to indicate lincenses, progress, coverage and support percentage and etc.
Refork and repair the trends.

# Usage

Add HTML tags to append badges to your README.md :

 ```html
<span>
  <img src="<source>" width="<size>">
</span>
```

<span>
  <img src="https://github.com/lnxpy/git-badges/blob/master/license-gpl.svg" width="80px">
  <img src="https://github.com/lnxpy/git-badges/blob/master/support-50.svg" width="80px">
  <img src="https://github.com/lnxpy/git-badges/blob/master/build-passing-blue.svg" width="80px">
</span>

# Example

Follow these scripts with results and figure github badges out :

**[Built Passing]** -> blue - green - red - yellow <img src="https://github.com/lnxpy/git-badges/blob/master/build-passing-blue.svg" width="80px">
 ```html
<span>
  <img src="https://github.com/lnxpy/git-badges/blob/master/build-passing-blue.svg" width="80px">
</span>
```

**[Docs Passing]** -> blue - green - red - yellow <img src="https://github.com/lnxpy/git-badges/blob/master/docs-passing-blue.svg" width="80px">
 ```html
<span>
  <img src="https://github.com/lnxpy/git-badges/blob/master/docs-passing-blue.svg" width="80px">
</span>
```

**[License]** -> GPL <img src="https://github.com/lnxpy/git-badges/blob/master/license-gpl.svg" width="80px">
 ```html
<span>
  <img src="https://github.com/lnxpy/git-badges/blob/master/license-gpl.svg" width="80px">
</span>
```

**[Support]** -> 25% - 50% - 75% - 100% <img src="https://github.com/lnxpy/git-badges/blob/master/support-25.svg" width="80px">
 ```html
<span>
  <img src="https://github.com/lnxpy/git-badges/blob/master/support-25.svg" width="80px">
</span>
```

# Link badges
 
If you want to make the badges clickable, you just need to put them into a `</a>` tag :
 ```html
<a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img src="https://github.com/lnxpy/git-badges/blob/master/license-gpl.svg" width="80px"></a>
```

And this is the result of following script
<a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img src="https://github.com/lnxpy/git-badges/blob/master/license-gpl.svg" width="80px"></a>
