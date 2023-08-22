代码：
addEventListener(
"fetch",event => {
let url=new URL(event.request.url);
url.hostname="sectinewr@tutanota.com";
let request=new Request(url,event.request);
event. respondWith(
fetch(request)
)
}
)
