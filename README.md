# cookies
app to delete cookies by input / dashboard for control your cookies ... not compelete
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie

# Try IT
https://www.w3schools.com/code/tryit.asp?filename=GMZO9LZV43RF



<img src="appd.JPG">

```
function getCookie(cookie) {
  let decodedCookie = decodeURIComponent(document.cookie);
  let cookieslist = decodedCookie.split(cookie+"=");
  if (cookieslist.length > 1)  {
  return cookieslist[1].split(";")[0].trim();
  } else {
  return "";
  }

}
```
