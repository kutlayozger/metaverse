
# Metaverse Markup Language

## Main Direvtives
- Every object may contains id (like html)
- Every object may contains class (like html)
- If any object has not got x value x value equal previous objects x + previous object width
- If any object has not got x value y value equal previous objects y + previous object height

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
<html x="3" y="5" width="4" height="2" direction="1" src="https://www.google.com" />
<html  x="3" y="5" width="4" height="2" direction="1"><div>...</div></html>
```
Shows html codes or web page in metaverse

#### attributes
x: x position of object

y: y position of object

direction: angle of direction


### portal
```
<portal src="meta://anothermetaaddr" x="8" y="9" size="3" dir="1" />
```
Shows portal for pass another metaverse. Portals shows initial screen on it. It likes link (a) tag for meta language.

#### attributes
x: x position of object

y: y position of object

direction: angle of direction

### binary
```
<binary id="avatar">[Binary data]</binary>
<binary id="avatar" src="meta://binary" />
```

### object
```
<object x="4" y="5" direction="90" binary="[binarycode]" />
<object from="binaryId" />
```

