### XML (Working with XML and XML files)

Maybe it is a hard to understand, but XML does not DO anything !. Ref# w3school<br>
Nodes are the budling bloks of XML

```xml
<note>
  <to>Tove</to>
  <from>Jani</from>
  <heading>Reminder</heading>
  <body>Don't forget me this weekend!</body>
</note>
```

Note to Tove from Jani, Don't forget me this weekend! stored as XML

#### Note
To: Tove
From: Jani

#### Reminder
Don't forget me this weekend!

### XML Syntax Rules

* The XML Prolog at the xml file header: ```xml <?xml version="1.0" encoding="UTF-8"?> ```
* XML Documents Must Have a Root Element that is the parent of all other elements.
* All XML Elements Must Have a Closing Tag.
* XML Elements Must be Properly Nested.
* Comments in XML: <!-- This is a comment -->
* XML Stores New Line as LF (Windows applications store a new line as: carriage return (CR+LF).


```xml
<root>
  <child>
    <subchild>.....</subchild>
  </child>
</root>
```

