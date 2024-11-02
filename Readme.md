## Go jxl mime not serverd correctly

#### How to reproduce
1. Clone this repo
2. run `go run main.go`
3. In safari/jxl supported browser open [http://localhost:3000/logo.jxl](http://localhost:3000/logo.jxl) browser will prompt to download instead of displaying in browser
4. On the other hand jpeg or any Go supported mimetype are displayed in browser.

#### Why this happens? 
`.jxl` files are not served with right mimetype
