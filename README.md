edUI
====

educational interface

##Version 1.0

1 memo game available.

The configuration is based on xml and use jQuery UI .


###xml directory

Each board are defined in an xml file.

The board tag defines the accordion containing all the decks available for one theme.

The deck tag contains all the couple of card for one memory.

|attribute|type|description
|---|---|---|
|hideunselected|boolean|the unselected card are hidden (advanced player) or not (young player)|
|name|string|Link name in the accordeon|
|description|string|Short description|

```xml

<?xml version="1.0" encoding="ISO-8859-1"?>
<board>
  <title>My first memory</title>
  <description>memory for babies</description>
  <decks>
    <deck hideunselected="false" name="Animaux 1" description="Trouve les deux images d'animaux identiques">
      <couple>
        <card><![CDATA[<img src="./img/animaux/autruche.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/autruche.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/biche.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/biche.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/bison.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/bison.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/canard.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/canard.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/cerf.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/cerf.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/chameau.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/chameau.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/chat.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/chat.png" style="vertical-align: middle; ">]]></card>
      </couple>
      <couple>
        <card><![CDATA[<img src="./img/animaux/cheval.png" style="vertical-align: middle; ">]]></card>
        <card><![CDATA[<img src="./img/animaux/cheval.png" style="vertical-align: middle; ">]]></card>
      </couple>
    </deck>
  </decks>
</board>
```

###img directory

All images in img came from http://openclipart.org/


