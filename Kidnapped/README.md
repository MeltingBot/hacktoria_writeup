
# KIDNAPPED 

*Hacktoria Contract *

Writeup by @Tungst - 16/03/2023
https://hacktoria.com/contracts/kidnapped/


![](Logo_Kidnapped.png)

### Prologue

Ahmed stood in the dimly lit room, his eyes fixed on the girl in front of him. Jessica Anderson sat in a chair, her hands tied behind her back and tears streaming down her face. He couldn’t help but feel a twinge of guilt at the sight of her terror, but he knew what he was doing was necessary.

His family had been killed in Iraq during a raid by American soldiers. His wife and children had been asleep in their home when the soldiers stormed in, guns blazing. Ahmed had been working late at the time, and when he came home to find his family dead, his world crumbled around him.

For years he had struggled to come to terms with what had happened, but he couldn’t shake the feeling of anger and betrayal. He had been a proud Iraqi, but the actions of the American military had left him feeling nothing but hatred towards them.

That was how he had ended up in Paris, where he had stumbled upon the daughter of a US diplomat. At first, he hadn’t known who she was, but when he found out, he knew that this was his chance for revenge.

Jessica sobbed uncontrollably as Ahmed paced the room, his mind filled with memories of his family. He had never intended to hurt anyone, but he couldn’t let this bastard continue to get away with what they had done. This time, it would be his world that would crumble.

### Briefing

Greetings, Special Agent K.

We have an urgent case on our hands. Our friends at the Police Nationale, in Paris France, have reached out for our assistance. It’s a case concerning the daughter of a US diplomat residing in France. Recently, Jason Anderson, a former officer with the United States Army Rangers, now diplomat assigned as an intelligence liaison in Paris, received a phone call stating his daughter had been taken. Shortly after, Mr Anderson received a written message in cipher text. We have reason to believe they are closely related.

During the phone call, a man with an Arabic accent spoke to Mr Anderson about having his daughter in captivity. Also stating he has 24 hours to figure out where she is, before he would kill her. Now, this interaction happened 6 hours ago, between that time Mr Anderson contacted police, who reached out to us a few hours after getting stuck on the cipher text.

You assignment is simple, over the next several hours, figure out what the message is behind the cipher text. We need answers quickly, so the police is left with enough time to intervene.

As always, Special Agent K. The Contract is yours, if you choose to accept.

### Materials and Answer Instruction

The password is a what3words combination

Sample password: banana.truck.hairdresser

[Download the flagfile](https://hacktoria.com/wp-content/contracts/flags/flagfile-kidnapped.zip)

Starting Materials:

```
Y2MgZWQgZWAgZmEgYV8gY0IgZmEgYUMgYV8gY2AgZUMgZWMgZWQgZmEgZmIgZUQgZUMgYUEgXz8gXz8gY2AgZmIgYV8gZmggZUQgZmQgYV8gZUIgZWAgZmggYV8gZUAgZUMgZUQgZmYgYUEgYV8gY2ggYV8gZWcgZWAgZmUgZWQgYV8gZmggZUQgZmQgZmEgYV8gZWMgZWAgZmQgZWYgZWcgZmMgZWQgZmEgYUMgYV8gY2ggZUMgYV8gZmMgZWcgZWQgYV8gZUMgZWQgZmcgZmMgYV8gYmEgYmMgYV8gZWcgZUQgZmQgZmEgZmIgYUEgYV8gZmIgZWcgZWQgYV8gZmYgZWggZUEgZUEgYV8gZWEgZWQgYV8gZUAgZWggZUEgZUEgZWQgZWMgYV8gZWggZUMgYV8gZmMgZWcgZWQgYV8gZUIgZUQgZmIgZmMgYV8gZWYgZmEgZmQgZWQgZmIgZUQgZUIgZWQgYV8gZmYgZWAgZmggYV8gZWggZUIgZWAgZWYgZWggZUMgZWAgZWEgZUEgZWQgYUMgYV8gY2ggYV8gZUAgZUMgZUQgZmYgYV8gZmYgZWcgZWAgZmMgYV8gZmggZUQgZmQgYV8gZWMgZWggZWMgYV8gZmMgZUQgYV8gZUIgZWQgYV8gZWAgZUMgZWMgYV8gZUIgZmggYV8gZWUgZWAgZUIgZWggZUEgZmggYV8gZWggZUMgYV8gY2ggZmEgZWAgZmAgYUEgYV8gZWAgZUMgZWMgYV8gZmIgZUQgYV8gZWMgZUQgYV8gZmggZUQgZmQgYUMgYV8gZGMgZWcgZWQgYV8gZWUgZmQgZUMgZUMgZmggYV8gZmMgZWcgZWggZUMgZWYgYV8gZWggZmIgYUEgYV8gZWQgZmUgZWQgZUMgYV8gZmMgZWcgZUQgZmQgZWYgZWcgYV8gZmggZUQgZmQgYWYgZmEgZWQgYV8gZmIgZmMgZWAgZmEgZWggZUMgZWYgYV8gZWAgZmMgYV8gZmMgZWcgZWggZmIgYV8gZWQgZmcgZWAgZWIgZmMgYV8gZmMgZWQgZmcgZmMgYUEgYV8gZmYgZWcgZWggZWIgZWcgYV8gZmMgZWQgZUEgZUEgZmIgYV8gZmggZUQgZmQgYV8gZWQgZmcgZWAgZWIgZmMgZUEgZmggYV8gZmYgZWcgZWQgZmEgZWQgYV8gZmggZUQgZmQgZmEgYV8gZWMgZWAgZmQgZWYgZWcgZmMgZWQgZmEgYV8gZWggZmIgYUMgYV8gZGMgZWcgZmEgZUQgZmQgZWYgZWcgYV8gZWAgZUEgZUEgYV8gZmMgZWcgZWQgYV8gZUEgZWAgZmggZWQgZmEgZmIgYV8gZUQgZWUgYV8gZWQgZUMgZWIgZUQgZWMgZWggZUMgZWYgYUEgYV8gZmggZUQgZmQgYV8gZmYgZWggZUEgZUEgYV8gZUMgZWQgZmUgZWQgZmEgYV8gZWUgZWggZUMgZWMgYV8gZWcgZWQgZmEgYV8gZWggZUMgYV8gZmMgZWggZUIgZWQgYUMgXz8gXz8gY2AgZWUgZmMgZWQgZmEgYV8gZWAgZUEgZUEgYV8gZmggZUQgZmQgYV8gZWMgZWggZWMgYV8gZmMgZUQgYV8gZUIgZWQgYUEgYV8gY2ggYV8gZmMgZWAgZUAgZWQgYV8gZmIgZUQgYV8gZUIgZmQgZWIgZWcgYV8gZWQgZUMgZT8gZUQgZmggZUIgZWQgZUMgZmMgYV8gZWUgZmEgZUQgZUIgYV8gZUAgZUMgZUQgZmYgZWggZUMgZWYgYV8gZWcgZUQgZmYgYV8gZmggZUQgZmQgYWYgZmEgZWQgYV8gZmIgZmMgZWAgZmEgZWggZUMgZWYgYV8gZWAgZmMgYV8gZmMgZWcgZWggZmIgYV8gZUIgZWQgZmIgZmIgZWAgZWYgZWQgYUMgYV8gY0AgZUMgZUQgZmYgZWggZUMgZWYgYV8gZmMgZWcgZWAgZmMgYV8gZmMgZWcgZWQgYV8gZWAgZUMgZmIgZmYgZWQgZmEgYV8gZUEgZWggZWQgZmIgYV8gZmYgZWggZmMgZWcgZWggZUMgYUEgYV8gZmggZWQgZmMgYV8gZWIgZUQgZUIgZl8gZUEgZWQgZmMgZWQgZUEgZmggYV8gZl8gZUQgZmYgZWQgZmEgZUEgZWQgZmIgZmIgYV8gZmMgZUQgYV8gZWUgZWggZUMgZWMgYV8gZWggZmMgYUMgYV8gZGIgZUQgYV8gZWAgZmIgYV8gZl8gZmEgZUQgZUIgZWggZmIgZWQgZWMgYUEgYV8gZWcgZWQgZmEgZWQgYV8gZWggZmIgYV8gZmggZUQgZmQgZmEgYV8gZWMgZWAgZmQgZWYgZWcgZmMgZWQgZmEgYj8gYV8gZWggZUMgZWIgZWcgZWQgZWMgYUMgZWEgZWAgZmEgZUIgZWAgZUMgYUMgZWUgZWAgZmIgZmMgYV8gY2YgZUQgZUQgZWMgYV8gZUEgZmQgZWIgZUAgYV8gZWUgZWggZUMgZWMgZWggZUMgZWYgYV8gZmQgZmIgYV8gZWggZUMgYV8gZmMgZWggZUIgZWQgYUEgYV8gZmIgZWcgZWQgYWYgZmIgYV8gZmYgZWggZmMgZWcgYV8gZUIgZWQgYV8gZUAgZUMgZUQgZmYgYUMgYV8gY2IgZmEgZmggZWggZUMgZWYgYV8gZWUgZUQgZmEgYV8gZmIgZUQgZUIgZWQgZUQgZUMgZWQgYV8gZmMgZUQgYV8gZWUgZWggZUMgZWMgYV8gZWcgZWQgZmEgYUEgYV8gZmYgZWcgZWggZWIgZWcgYV8gZmggZUQgZmQgYV8gZmYgZWggZUEgZUEgYUEgYV8gZWggZUMgYV8gZl8gZWggZWQgZWIgZWQgZmIgYUMgYV8gZF8gZWggZWQgZWIgZWQgZmIgYV8gZWIgZmEgZWQgZWAgZmMgZWQgZWMgYV8gZUQgZmQgZmMgYV8gZUQgZWUgYV8gZWcgZWQgZmEgYV8gZWUgZUEgZWQgZmIgZWcgYV8gZmYgZWcgZWggZUEgZWQgYV8gZmIgZWcgZWQgYV8gZmYgZWAgZmIgYV8gZmIgZmMgZWggZUEgZUEgYV8gZWAgZUEgZWggZmUgZWQgYUMgYV8gZGMgZWcgZWAgZmMgYWYgZmIgYV8gZmYgZWcgZWAgZmMgYV8gZmggZUQgZmQgYV8gZWYgZWQgZmMgYV8gZWUgZUQgZmEgYV8gZmMgZWcgZWQgYV8gZWcgZUQgZmEgZmEgZUQgZmEgZmIgYV8gZmggZUQgZmQgYV8gZl8gZmQgZmMgYV8gZUIgZWQgYV8gZWAgZUMgZWMgYV8gZUIgZmggYV8gZWUgZWAgZUIgZWggZUEgZmggYV8gZmMgZWcgZmEgZUQgZmQgZWYgZWcgYUMgXz8gXz8gY2UgZmQgZWIgZUAgYV8gZmggZUQgZmQgYUEgYV8gY0IgZmEgYV8gY2AgZUMgZWMgZWQgZmEgZmIgZUQgZUMgYUM=
```

### Analysis

The text seems to be a base64 encoded text.

Let's try !

```
cc ed e` fa a_ cB fa aC a_ c` eC ec ed fa fb eD eC aA _? _? c` fb a_ fh eD fd a_ eB e` fh a_ e@ eC eD ff aA a_ ch a_ eg e` fe ed a_ fh eD fd fa a_ ec e` fd ef eg fc ed fa aC a_ ch eC a_ fc eg ed a_ eC ed fg fc a_ ba bc a_ eg eD fd fa fb aA a_ fb eg ed a_ ff eh eA eA a_ ea ed a_ e@ eh eA eA ed ec a_ eh eC a_ fc eg ed a_ eB eD fb fc a_ ef fa fd ed fb eD eB ed a_ ff e` fh a_ eh eB e` ef eh eC e` ea eA ed aC a_ ch a_ e@ eC eD ff a_ ff eg e` fc a_ fh eD fd a_ ec eh ec a_ fc eD a_ eB ed a_ e` eC ec a_ eB fh a_ ee e` eB eh eA fh a_ eh eC a_ ch fa e` f` aA a_ e` eC ec a_ fb eD a_ ec eD a_ fh eD fd aC a_ dc eg ed a_ ee fd eC eC fh a_ fc eg eh eC ef a_ eh fb aA a_ ed fe ed eC a_ fc eg eD fd ef eg a_ fh eD fd af fa ed a_ fb fc e` fa eh eC ef a_ e` fc a_ fc eg eh fb a_ ed fg e` eb fc a_ fc ed fg fc aA a_ ff eg eh eb eg a_ fc ed eA eA fb a_ fh eD fd a_ ed fg e` eb fc eA fh a_ ff eg ed fa ed a_ fh eD fd fa a_ ec e` fd ef eg fc ed fa a_ eh fb aC a_ dc eg fa eD fd ef eg a_ e` eA eA a_ fc eg ed a_ eA e` fh ed fa fb a_ eD ee a_ ed eC eb eD ec eh eC ef aA a_ fh eD fd a_ ff eh eA eA a_ eC ed fe ed fa a_ ee eh eC ec a_ eg ed fa a_ eh eC a_ fc eh eB ed aC _? _? c` ee fc ed fa a_ e` eA eA a_ fh eD fd a_ ec eh ec a_ fc eD a_ eB ed aA a_ ch a_ fc e` e@ ed a_ fb eD a_ eB fd eb eg a_ ed eC e? eD fh eB ed eC fc a_ ee fa eD eB a_ e@ eC eD ff eh eC ef a_ eg eD ff a_ fh eD fd af fa ed a_ fb fc e` fa eh eC ef a_ e` fc a_ fc eg eh fb a_ eB ed fb fb e` ef ed aC a_ c@ eC eD ff eh eC ef a_ fc eg e` fc a_ fc eg ed a_ e` eC fb ff ed fa a_ eA eh ed fb a_ ff eh fc eg eh eC aA a_ fh ed fc a_ eb eD eB f_ eA ed fc ed eA fh a_ f_ eD ff ed fa eA ed fb fb a_ fc eD a_ ee eh eC ec a_ eh fc aC a_ db eD a_ e` fb a_ f_ fa eD eB eh fb ed ec aA a_ eg ed fa ed a_ eh fb a_ fh eD fd fa a_ ec e` fd ef eg fc ed fa b? a_ eh eC eb eg ed ec aC ea e` fa eB e` eC aC ee e` fb fc a_ cf eD eD ec a_ eA fd eb e@ a_ ee eh eC ec eh eC ef a_ fd fb a_ eh eC a_ fc eh eB ed aA a_ fb eg ed af fb a_ ff eh fc eg a_ eB ed a_ e@ eC eD ff aC a_ cb fa fh eh eC ef a_ ee eD fa a_ fb eD eB ed eD eC ed a_ fc eD a_ ee eh eC ec a_ eg ed fa aA a_ ff eg eh eb eg a_ fh eD fd a_ ff eh eA eA aA a_ eh eC a_ f_ eh ed eb ed fb aC a_ d_ eh ed eb ed fb a_ eb fa ed e` fc ed ec a_ eD fd fc a_ eD ee a_ eg ed fa a_ ee eA ed fb eg a_ ff eg eh eA ed a_ fb eg ed a_ ff e` fb a_ fb fc eh eA eA a_ e` eA eh fe ed aC a_ dc eg e` fc af fb a_ ff eg e` fc a_ fh eD fd a_ ef ed fc a_ ee eD fa a_ fc eg ed a_ eg eD fa fa eD fa fb a_ fh eD fd a_ f_ fd fc a_ eB ed a_ e` eC ec a_ eB fh a_ ee e` eB eh eA fh a_ fc eg fa eD fd ef eg aC _? _? ce fd eb e@ a_ fh eD fd aA a_ cB fa a_ c` eC ec ed fa fb eD eC aC
```

Not Realy Readble !

Let's try now with ROT47


```
44 65 61 72 20 4q 72 2r 20 41 6r 64 65 72 73 6s 6r 2p 0n 0n 41 73 20 79 6s 75 20 6q 61 79 20 6o 6r 6s 77 2p 20 49 20 68 61 76 65 20 79 6s 75 72 20 64 61 75 67 68 74 65 72 2r 20 49 6r 20 74 68 65 20 6r 65 78 74 20 32 34 20 68 6s 75 72 73 2p 20 73 68 65 20 77 69 6p 6p 20 62 65 20 6o 69 6p 6p 65 64 20 69 6r 20 74 68 65 20 6q 6s 73 74 20 67 72 75 65 73 6s 6q 65 20 77 61 79 20 69 6q 61 67 69 6r 61 62 6p 65 2r 20 49 20 6o 6r 6s 77 20 77 68 61 74 20 79 6s 75 20 64 69 64 20 74 6s 20 6q 65 20 61 6r 64 20 6q 79 20 66 61 6q 69 6p 79 20 69 6r 20 49 72 61 71 2p 20 61 6r 64 20 73 6s 20 64 6s 20 79 6s 75 2r 20 54 68 65 20 66 75 6r 6r 79 20 74 68 69 6r 67 20 69 73 2p 20 65 76 65 6r 20 74 68 6s 75 67 68 20 79 6s 75 27 72 65 20 73 74 61 72 69 6r 67 20 61 74 20 74 68 69 73 20 65 78 61 63 74 20 74 65 78 74 2p 20 77 68 69 63 68 20 74 65 6p 6p 73 20 79 6s 75 20 65 78 61 63 74 6p 79 20 77 68 65 72 65 20 79 6s 75 72 20 64 61 75 67 68 74 65 72 20 69 73 2r 20 54 68 72 6s 75 67 68 20 61 6p 6p 20 74 68 65 20 6p 61 79 65 72 73 20 6s 66 20 65 6r 63 6s 64 69 6r 67 2p 20 79 6s 75 20 77 69 6p 6p 20 6r 65 76 65 72 20 66 69 6r 64 20 68 65 72 20 69 6r 20 74 69 6q 65 2r 0n 0n 41 66 74 65 72 20 61 6p 6p 20 79 6s 75 20 64 69 64 20 74 6s 20 6q 65 2p 20 49 20 74 61 6o 65 20 73 6s 20 6q 75 63 68 20 65 6r 6n 6s 79 6q 65 6r 74 20 66 72 6s 6q 20 6o 6r 6s 77 69 6r 67 20 68 6s 77 20 79 6s 75 27 72 65 20 73 74 61 72 69 6r 67 20 61 74 20 74 68 69 73 20 6q 65 73 73 61 67 65 2r 20 4o 6r 6s 77 69 6r 67 20 74 68 61 74 20 74 68 65 20 61 6r 73 77 65 72 20 6p 69 65 73 20 77 69 74 68 69 6r 2p 20 79 65 74 20 63 6s 6q 70 6p 65 74 65 6p 79 20 70 6s 77 65 72 6p 65 73 73 20 74 6s 20 66 69 6r 64 20 69 74 2r 20 53 6s 20 61 73 20 70 72 6s 6q 69 73 65 64 2p 20 68 65 72 65 20 69 73 20 79 6s 75 72 20 64 61 75 67 68 74 65 72 3n 20 69 6r 63 68 65 64 2r 62 61 72 6q 61 6r 2r 66 61 73 74 20 47 6s 6s 64 20 6p 75 63 6o 20 66 69 6r 64 69 6r 67 20 75 73 20 69 6r 20 74 69 6q 65 2p 20 73 68 65 27 73 20 77 69 74 68 20 6q 65 20 6o 6r 6s 77 2r 20 43 72 79 69 6r 67 20 66 6s 72 20 73 6s 6q 65 6s 6r 65 20 74 6s 20 66 69 6r 64 20 68 65 72 2p 20 77 68 69 63 68 20 79 6s 75 20 77 69 6p 6p 2p 20 69 6r 20 70 69 65 63 65 73 2r 20 50 69 65 63 65 73 20 63 72 65 61 74 65 64 20 6s 75 74 20 6s 66 20 68 65 72 20 66 6p 65 73 68 20 77 68 69 6p 65 20 73 68 65 20 77 61 73 20 73 74 69 6p 6p 20 61 6p 69 76 65 2r 20 54 68 61 74 27 73 20 77 68 61 74 20 79 6s 75 20 67 65 74 20 66 6s 72 20 74 68 65 20 68 6s 72 72 6s 72 73 20 79 6s 75 20 70 75 74 20 6q 65 20 61 6r 64 20 6q 79 20 66 61 6q 69 6p 79 20 74 68 72 6s 75 67 68 2r 0n 0n 46 75 63 6o 20 79 6s 75 2p 20 4q 72 20 41 6r 64 65 72 73 6s 6r 2r

```


Well, seems to be some hexa now !  lets try a hexdump


```
Dear .r. A.ders.....As y.u .ay ...w. I have y.ur daughter. I. the .ext 24 h.urs. she wi.. be .i..ed i. the ..st grues..e way i.agi.ab.e. I ...w what y.u did t. .e a.d .y fa.i.y i. Iraq. a.d s. d. y.u. The fu..y thi.g is. eve. th.ugh y.u're stari.g at this exact text. which te..s y.u exact.y where y.ur daughter is. Thr.ugh a.. the .ayers .f e.c.di.g. y.u wi.. .ever fi.d her i. ti.e...After a.. y.u did t. .e. I ta.e s. .uch e...y.e.t fr.. ...wi.g h.w y.u're stari.g at this .essage. ...wi.g that the a.swer .ies withi.. yet c..p.ete.y p.wer.ess t. fi.d it. S. as pr..ised. here is y.ur daughter. i.ched.bar.a..fast G..d .uc. fi.di.g us i. ti.e. she's with .e ...w. Cryi.g f.r s..e..e t. fi.d her. which y.u wi... i. pieces. Pieces created .ut .f her f.esh whi.e she was sti.. a.ive. That's what y.u get f.r the h.rr.rs y.u put .e a.d .y fa.i.y thr.ugh...Fuc. y.u. .r A.ders...

```

Ah we got a partial readeable text....

But several hexa numbers are incorrect.

After a quick letter swapping like

s->f
q->d
r->e
n->c
o->b
p->c

We got now 

```
Dear Mr. Anderson,..As you may know, I have your daughter. In the next 24 hours, she will be killed in the most gruesome way imaginable. I know what you did to me and my family in Iraq, and so do you. The funny thing is, even though you're staring at this exact text, which tells you exactly where your daughter is. Through all the layers of encoding, you will never find her in time...After all you did to me, I take so much enloyment from knowing how you're staring at this message. Knowing that the answer lies within, yet completely powerless to find it. So as promised, here is your daughter< inched.barman.fast Good luck finding us in time, she's with me know. Crying for someone to find her, which you will, in pieces. Pieces created out of her flesh while she was still alive. That's what you get for the horrors you put me and my family through...Fuck you, Mr Anderson.
```

the location is clearly readeable now !

**inched.barman.fast** and it's located here : https://what3words.com/inched.barman.fast


### BONUS

The CyberChef Recipe for this Challenge :

```
From_Base64('A-Za-z0-9+/=',true,false)
ROT47(47)
Find_/_Replace({'option':'Regex','string':'s'},'f',true,false,true,false)
Find_/_Replace({'option':'Regex','string':'q'},'d',true,false,true,false)
Find_/_Replace({'option':'Regex','string':'n'},'c',true,false,true,false)
Find_/_Replace({'option':'Regex','string':'r'},'e',true,false,true,false)
Find_/_Replace({'option':'Regex','string':'o'},'b',true,false,true,false)
Find_/_Replace({'option':'Regex','string':'p'},'c',true,false,true,false)
From_Hex('Auto')
```



