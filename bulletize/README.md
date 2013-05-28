Bulletize
===========

Format a nested list with bullets

Usage
------------

Suppose you have the following text on any editable text area:

```
item 1
 item 1.1
 item 1.2
  item 1.2.1
  item 1.2.2
 item 1.3
item 2
 item 2.1
```

Select the text, right click and select Bulletize.
You will end up with this:

```
 • item 1
   ◦ item 1.1
   ◦ item 1.2
     ▪ item 1.2.1
     ▪ item 1.2.2
   ◦ item 1.3
 • item 2
   ◦ item 2.1
```

Installation
------------

[Clone the snagglepuss repository](https://github.com/indefinido/snagglepuss#Installation)

Enter the repository directory:
```
cd bulletize
```

Install the service:
```
./install
```