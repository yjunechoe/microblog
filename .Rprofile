fuse_site <- function() {
  file.remove("index.html")
  litedown::fuse_site()
  litedown::fuse_site("index.html")
  browseURL("index.html")
}

newpost <- function() {
  file.copy("posts/_template.Rmd", tempfile("aaa-", "posts", ".Rmd"))
}
