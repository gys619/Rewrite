// 假设你有一个request对象，其中包含了需要替换URL的信息
const verbose = true;
var originalUrl =$request.url;
var newUrl = "https://ghproxy.com/"+url;
var currentUrl = window.location.href;

if(currentUrl.indexOf(originalUrl) !== -1) {
  var newUrl = currentUrl.replace(originalUrl, newUrl);
  window.location.href = newUrl;
  

}
