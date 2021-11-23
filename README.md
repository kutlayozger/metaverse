
# Metaverse Markup Language

## Main Direvtives
- Every object may contains id (like html)
- Every object may contains class (like html)

## Main Structure
```
<meta v="1.0">
<head>
</head>
<body>
</body>
</meta>
```

## Metaverse tags

### projection

<projection y="40%" />

Projection sets 3D projection point. Projection is optional directive if not exists center point is projection point.

#### attributes
x: (Optional) default center x of screen
y: (Optional) default center y of screen


### html
```
<html x="3" y="5" size="4" direction="1" src="https://www.google.com" />
<html  x="3" y="5" size="4" direction="1"><div>...</div></html>
```
Shows html codes or web page in metaverse


### portal
```
<portal src="meta://anothermetaaddr" x="8" y="9" size="3" dir="1" />
```
Shows portal for pass another metaverse. Portals shows initial screen on it. It likes link (a) tag for meta language.
### binary
```
<binary id="avatar">[Binary data]</binary>
<binary id="avatar" src="meta://binary" />
```



