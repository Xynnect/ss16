# 4chan X settings support
this is a list of what affect 4chan X's settings have on ss16's appearance

---

## main
### misc
- [x] __json index is required__
- [ ] index and reply navigation are supported
- [ ] remove and/or reveal spoilers are supported

### linkification
- [x] fully supported

### filtering
- [x] refer to filter section for beneficial filters
- [ ] thread and reply hiding buttons __are not supported__, use the menu instead

### images and videos
- [x] image expansion and hovering is supported
- [x] gallery supported
- [ ] __please don't enable image prefetching, you leech__
- [x] fappe and werk time is supported

### menu
- [x] menu is supported

### monitoring
- [x] thread updater is supported
- [x] thread stats are supported
- [x] thread watcher is supported

### posting and captchas
- [x] __qr is required__
- [ ] pass link login is not supported, navigate to login page manually

### quote links
- [x] quote backlinking, inlining, previewing are all supported

---

## filters
### post numbers
`/(\d)\1$/;highlight:post--dubs;top:no;boards:s4s` - posts with dubs vibrate and are checked

### capcodes
`/Admin$/;highlight:poster--admin;op:yes` - admin posts are red

`/Mod$/;highlight:poster--mod;op:yes` - mod posts are purple

`/Manager$/;highlight:poster--manager;op:yes` - manager posts are fuchsia

`/Developer$/;highlight:poster--developer;op:yes` - dev posts are blue

### pass dates
`/./;highlight:poster--pass;top:no;` - pass users are green

### filenames
`/.webm$/;highlight:file--video;top:no;` - webm thumbnails have a play button

`/.gif$/;highlight:file--gif;top:no;` - gif thumbnails display `GIF`
