# force making page bundle (i.e folder instead of single file)
options(blogdown.author = "Kate Hayes",  # Who the author of posts is
        blogdown.ext = ".Rmd",  # File extension for posts
        blogdown.subdir = "blog", # subfolder for posts to be placed in
        blogdown.yaml.empty = TRUE,
        blogdown.new_bundle = TRUE,
        blogdown.title_case = TRUE)

rprofile <- Sys.getenv("R_PROFILE_USER", "~/.Rprofile")

if (file.exists(rprofile)) {
  source(file = rprofile)
}
