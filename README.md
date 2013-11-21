# Github Stars
Returns a count of stars for any user or a single repo

## Asynchronous
```
//user or org
githubStars("stretchr", function(stars) {
	console.log("Stars: " + stars);
});

//individual repo
githubStars("stretchr/sdk-js", function(stars) {
	console.log("Stars for SDK-JS: " + stars);
});
```

## Synchronous
You can also perform requests synchronously if you'd prefer
```
var stars = githubStars("stretchr");
console.log("Stars: " + stars);