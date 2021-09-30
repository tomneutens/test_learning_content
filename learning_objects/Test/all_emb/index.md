---
hruid: test-v1
version: 3
language: nl
title: This is a titleeeee
description: This is a description
keywords: [voorbeeld, voorbeeld2]
educational_goals: [
    {source: Source, id: id}, 
    {source: Source2, id: id2}
]
copyright: Copyright by Jerro
licence: Licenced by Jerro
content_type: text/markdown
available: true
target_ages: [4, 3]
difficulty: 3
return_value: {
    callback_url: url/callback,
    callback_schema: {
        att: test,
        att2: test2
    }
}
content_location: content/location/http
estimated_time: 20
skos_concepts: [
    'http://ilearn.ilabt.imec.be/vocab/curr1/c-andere-talen', 
    'http://ilearn.ilabt.imec.be/vocab/ondniv/sec-gr2-doorstroom-aso'
]
teacher_exclusive: true
---
updated
# link pdf

[Vergadering pdf!](vergadering.pdf)

# link audio

[Momo!](momo.mp3)

# link yt

[Ricky!](https://www.youtube.com/watch?v=dQw4w9WgXcQ)


# link leerobj

[link](@learning-object/opdracht_leds/nl/1 "dit is een leerobject")

# link afbeelding

[afbeelding](dwengo_logo.png "dit is een afbeelding")

# link blocks

[Download](@blockly/blocks.xml "download deze blocks")

# afbeelding

![afbeelding](dwengo_logo.png "dit is een afbeelding")

# yt

![](@youtube/https://www.youtube.com/watch?v=ANJ9JLV4IPg)

# pdf

![](vergadering.pdf)

# blocks

![](@blockly/blocks.xml)

# Jupyter notebook

![](@notebook/https://www.cantera.org/examples/jupyter/thermo/flame_temperature.ipynb)


# audio

![](@audio/momo.mp3)


# leerobj
![](@learning-object/opdracht_leds/nl/1 )


