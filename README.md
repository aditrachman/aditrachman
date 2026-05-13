```r
nickname <- "anshelschella"

kenalan <- function() {
  assign("nickname", "yara", envir = .GlobalEnv)
}

kenalan()
print(paste("hai, panggil aku", nickname))

```
