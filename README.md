# Protocol-denken Demo

> EN: This repository hosts a mostly Dutch demonstrator of [Thinking Protocols](https://medium.com/@marc.van.andel/thinking-protocols-the-new-way-to-organize-contracts-and-value-exchange-3bfa9c6ee65f)

Deze repository bevat een Nederlandse demonstrator van ['protocol-denken'](https://medium.com/@marc.van.andel/protocol-denken-de-nieuwe-manier-om-contracten-en-waarde-uitwisseling-te-organiseren-7b6109580a23).

**Protocol-denken** is een concept om bij het ontstaan van een afsprakenstelsel direct de automatisering van dat stelsel uit te voeren. 
Een afsprakenstelsel betreft altijd informatie uitwisseling tussen meerdere partijen en dus is de implementatie / automatisering daarvan een rijk communicatie protocol.
In die uitwisseling worden transacties uitgewisseld, gebeurtenissen die hebben plaatsgevonden.
Geen standen van hoe het nu is, maar 'events'.

In deze demonstrator is daarbij het uitgangspunt dat data die ergens ontstaat een duidelijke eigenaar heeft.
Deze eigenaar kan besluiten om data wel of niet te delen.
Eenmaal gedeeld betekent dat het gedeeld blijft ... in ieder geval ten tijde van het delen.
Het hoeft niet te betekenen dat de eigenaar die data blijft delen of bijwerken.
Het betekent alleen dat de data die gedeeld is op het moment van delen, door andere partijen als gedeelde data beschouwd kan worden.

## Techniek & Architectuur

Voor de techniek wordt gebruik gemaakt van de volgende open source software:

**storage**
- [Solid Project](https://solidproject.org/)

**backend**
- [Kotlin](https://kotlinlang.org/)
- _(maybe [AxonFramework](https://axoniq.io/product-overview/axon-framework) & [AxonServer](https://axoniq.io/product-overview/axon-server))_

**frontend**
- [React & TypeScript](https://www.typescriptlang.org/docs/handbook/react.html) using [Next.js](https://nextjs.org/)

## License

This work is licensed under a [EUPL v1.2 license](./LICENSE.md). All documentation is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
