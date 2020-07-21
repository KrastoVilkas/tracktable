
<!--

This template is for creating a Tracktable release that will go out to the world.  

-->

# Public Tracktable release

### Version Number

<!-- 
    Example: 1.3.1
-->

### Major/Minor/Patch release?

<!--
    Example: Patch
-->

### Major features in this release

<!--
    Example: Interactive trajectory rendering using Folium
-->

### Major bug fixes in this release

<!-- 
    Example: Python interpreter crashes on import
-->

### Checklist

- [ ] Create release branch from `develop`
- [ ] Wheels
    * [ ] Build Wheels
        - [ ] Linux
        - [ ] Windows
        - [ ] MacOS
    * [ ] Upload wheels to PyPI
    * [ ] Upload wheels to Cascade
- [ ] Release Notes
    * [ ] Compile from issues since previous version
    * [ ] Note known issues
    * [ ] Check into release branch
- [ ] Documentation
    * [ ] Build
    * [ ] `.tar.gz` file
    * [ ] `.zip` file
    * [ ] Upload to Cascade
- [ ] Source Code
    * [ ] Check out clean copy
    * [ ] Delete `.git` directory
    * [ ] Make `.tar.gz` version
    * [ ] Make `.tar.bz2` version
    * [ ] Make `.zip` version
    * [ ] Upload to Cascade
- [ ] Push source code to `sandialabs/tracktable` on Gitlab
- [ ] Announcement
    * [ ] Send to tracktable-develop
    * [ ] Post on Cascade
- [ ] Finalize
    * [ ] Create and handle merge request for release branch
    * [ ] Publish updates on Cascade to `https://tracktable.sandia.gov`