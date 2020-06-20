
# in case of errors fall-back on renv-free setup.
renv::deactivate()
delete renv.lock and renv folder


remotes::install_local()

have to add to .Rbuildignore all files that are not part of the standard R package structure (use_travis do it for you)
