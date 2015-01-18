---
layout: page
title: About
permalink: /about/
---

The content found on this page is assembled from the handful of documentation and notes snippets found in all GPQuery repository directories, as well as my personal notebook.

## Tasklist
*Be sure to maintain the order of highest to lowest priority!*

 - [x] Tidy Up Main Repositories
   - [x] Sync `Dashboard` repositories
     - [x] Working directory clean
     - [x] Branches up-to-date with `origin/*`
   - [x] Sync `Engine` repositories
     - [x] Working directory clean
     - [x] Branches up-to-date with `origin/*`
   - [x] Verify full application is functioning
   
 - [ ] Restructure `GPQuery\GPQuery` repository
   - [x] Initialise `GPQuery\Livery` repository
   - [x] Initialise `GPQuery\Chassis` repository
   - [ ] Create `GPQuery\Livery` repository
   - [ ] Create `GPQuery\Chassis` repository
   - [ ] Reconfigure Dependencies and Packages
     - [ ] Refer to Composer documentation
     - [ ] Refer to bower documentation
 - [ ] Prune repositories and branches
   - [ ] Remove stale branches
   - [ ] `git merge develop`
 - [ ] Documentation - GitHub Pages
 - [ ] Revisit Semantic Versioning?
    
 - [ ] Finalise Slim Application Standard Routing
 - [ ] Finalise Eloquent ORM Standard Models and Relations
 - [ ] Basic Data Visualisation with nvD3
 - 
 
## Versioning

[Semantic versioning](http://semver.org) dictates a three-tier approach:
```
1.2.3 (11BCF) <- Build number, should correspond with a revision in source control
^ ^ ^
| | |
| | +--- Minor bugs, spelling mistakes, etc.
| +----- Minor features, major bug fixes, etc.
+------- Major version, UX changes, file format changes, etc.
```

  Version | Date        | Description
 -------- | ----------- | ---------------------------
  0.9.0   | 17 Jan 2015 | Pre-Alpha Development Stage
  1.0.0   |             | Alpha Release
