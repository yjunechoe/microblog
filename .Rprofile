fuse_site <- function() {
  if (file.exists("index.html")) file.remove("index.html")
  litedown::fuse_site()
  Sys.sleep(2)
  litedown::fuse_site("index.Rmd")
  browseURL("index.html")
}

newpost <- function() {
  f <- tempfile("aaa-", "posts", ".Rmd")
  file.copy("posts/_template.Rmd", f)
  browseURL(f)
}
