# asc-search

## GOOGLE:
https://play.google.com/store/apps/collection/topgrossing?hl=en_US

## APPLE: 
http://www.apple.com/br/itunes/charts/free-apps/

STORE: GOOGLE, APPLE
Overall = 92
Games Free = 36 

listbox: google ou apple
textfield: "My Talking Tom"

```
api/{store}/{appname}

if (store === 'google') {
	service.googleSearch(appname);
} else if (store === 'apple') {
	service.appleSearch(appname);
}
```

JSON response
```
{
	name: '', 
	icon: '', 
	ranking: {
		overall: '', 
		category: {
			name: '', 
			value: ''
		}
	}
}
```

```
Output:
Overall = 92
Games Free = 36 
```