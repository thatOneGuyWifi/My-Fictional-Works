# Introduction

What is Magvo-Stellarean? Magvo-Stellarean is a conlang made by me for my fictional universe/series, **"Empires in Space" (EiS)**. EiS is basically a collection of stories (and lore) which happens inside the EiS universe/multiverse; it's similar to something like the Marvel Cinematic Universe (MCU) but a better comparison would be history, Empires in Space is sci-fi alt history.

Magvo-Stellarean is designed to be a logical language. Magvo-Stellarean uses it's own alphabet called the **"Magvo-Stellarean Marked Alphabet"**. A marked alphabet is similar to an abugida but it has more articulation diacritics than just vowels.

Here is the Magvo-Stellarean Marked Alphabet:

<img src="images/Magvo-Stellarean/Magvo-Stellarean%20Marked%20Alphabet.png">

However, the Magvo-Stellarean Marked Alphabet (as of yet) is not included in unicode so we cannot write it in plain text. Due to this: Magvo-Stellarean is written in it's own custom latin script, called the **"Romanized Magvo-Stellarean Script" (RMSS)**.

# Romanized Magvo-Stellarean Script (RMSS)

## Vowels

a: /a/  
æ: /æ/  
e: /e/  
i: /i/  
ī: /ɪ/  
ō: /ɔ/  
o: /o/  
ū: /ɤ/  
u: /u/  

*(The order goes from Front-Open to Back-Close.)*

## Consonants

### Plosives

p: /p/  
b: /b/  
t: /t/  
d: /d/  
k: /k/  
g: /g/

### Nasals

m: /m/  
n: /n/  
ŋ: /ŋ/

### Fricatives

f: /f/  
v: /v/  
s: /s/  
z: /z/  
h: /h/

### Approximants

w: /w/  
r: /ɹ/  
y: /j/  
l: /l/  

### Affricates 

c: /tʃ/  
j: /dʒ/

### Reverse Digraph (1 letter = 2 consonants)

x: /ks/  
q: /gz/
θ: /tɹ/
ð: /dɹ/

### Diacritics

eʰ: aspirates a consonants.  
e̪: makes the phoneme have a dental articulation.  
e̚: makes the phoneme have a retroflex articulation.

*(The e is just an example sound, also you can only apply these diacritics to consonants.)*

# Phonology

The phonology of Magvo-Stellarean is very expressive; there isn't much phonology in Magvo-Stellarean. Magvo-Stellarean mostly leaves it phonological works to any dialects of Magvo-Stellarean. Magvo-Stellarean presented here is referred to as Base Magvo-Stellarean when talking about dialects of Magvo-Stellarean. However—even with Base Magvo-Stellarean's loose phonology—it still has some phonology. We will get into that right now.

**Syllable Structure**: (C)(C)(C)(C)V(C)(C)(C)(C)

The C here means consonants and the V here means vowel. The C's are also inside parenthesis which indicates that the consonants are not required for a syllable (while a vowel is).

The first 4 pairs of C's are called the onset, the V is called the nucleus and the second 4 pairs of C's are called the coda. In the onset and coda: all consonants (in Magvo-Stellarean) are accepted, in the nucleus: all sonorants are accepted; which includes vowels (monophthongs, diphthongs, triphthongs) and sonorant consonants.

You might be asking, "wait... Consonants can be inside a nucleus?" And yes, a *sonorant* consonant can be the nucleus of a syllable; but only sonorant consonants (n, n̚, n̪, m, ŋ, w, r, r̚, r̪, y, l, l̚, l̪), not any other consonants.

Usually, the first syllable in Magvo-Stellarean is stressed

Base Magvo-Stellarean also has 2 phonotactic constraint, they are:

*Constraint #1*: an aspirated phoneme cannot be at the end of a syllable; for example: a word like /kīkʰ/ is not permitted. An aspirated phoneme can be at the start or in the middle of a syllable but not at the end.

*Constraint #2*: Two consonants whose only difference is voicing cannot appear in adjacent within a syllable; for example: /pb/ or /bp/ is not permitted but /pk/ and /kp/ are. A word like /ekgi/ (two consonants who only differ in voicing are put in adjacent; kg) is permitted as long /ek/ and /gi/ are within different syllables.

# Syntax

*Word Order*: Subject-Verb-Object (SVO). What this means means is that the subject comes first, then verb and finally the object. English also follows the same word order aswell. A sentence like "Manin eats ice-cream" is allowed but "Manin ice-cream eat" or "Eat Manin ice-cream" or any other order is *not*. Magvo-Stellarean's syntax has strict order placement and breaking them can either change the meaning (the man eats the cake vs the cake eats the man) or make the sentence ungrammatical (eat the man the cake).

Along with word order, Magvo-Stellarean has a strict phrase structure rule. A phrase structure rule means how words inside phrases/sentences should be arranged to be grammatical. Magvo-Stellarean's phrase structure rule is:

S →  (CP) NP (Mod) \[Conj Mod]* VP \[Conj S]* (Q)  
NP →  N' \[Conj N']* PP* (CP)  
N' →  (D) N (AdjP) \[Conj AdjP]* PP*  
AdjP →  (Deg) Adj  
VP →  V' \[Conj V']* PP* (CP)  
V' →  (Neg) V (AdvP) \[Conj AdvP]* (AdjP) \[Conj AdjP]* (NP) \[Conj NP]* PP*  
AdvP →  (Deg) Adv  
PP →  P {VP, NP}  
CP →  C S

Let's go over what this means. S means "Sentence" and the arrow states the rules of how a sentence should be structured. Let's first look at CP. CP means "Complimentizer Phrase"; a complimentizer links a clause to another one and also marks the type of a clause (like: that, if, whether, etc). A Complimentizer Phrase (here) means: the sentence (clause) is preceded by the complimentizer to put in the sentence (as you can see above at the end, C means the complimentizer). The sentence-level CP must be placed first as by the rule. Note that all subordinating conjunctions in Magvo-Stellarean are complimentizers.
 
Now NP. NP means "Noun Phrase"; it means a phrase that is headed/determined by a noun but think of it as a noun with all of it's modifiers. N' (N-bar) points to the noun with it's closer modifiers; while the NP has looser modifiers. The \[Conj N']* means after the first noun: there can be zero or more nouns—with it's closer modifiers—connected by a conjunction (like: and, or, etc). PP means "Prepositional Phrase"; we will get to them later. The asterisk (*) means there can be zero or more PP. The (CP) means there can optionally be a CP inside the NP (used for relative clauses). Note that anything inside parenthesis are optional.

Now N'. The (D) means there can optionally be a determiner before the noun (N means noun); a determiner specifies (determines) the noun; for example: the noun "dog" on it's own is ambiguous but the determiner "my" before dog ("my dog") specifies that among all the dogs out there, my dog is being talked about. AdjP means "Adjective Phrase"; it means a phrase headed by an adjective but thunk of it as a adjective with it's degree; degree means how "intense" the adjective is.

Going back to S, Mod. Mod means modal; a modal is a clause-level marker that expresses the speaker's attitude about the clause (necessity, possibility, obligation, permission, ability); you should know about them if you learned auxiliary verbs. \[Conj Mod]* means the same thing as \[Conj N']* but replace noun with modals. Note that \[Conj X]* means anything inside X can be zero or more combined with conjunctions.

Now VP. VP means "Verb Phrase"; it means a phrase headed by a verb but think of it as the verb with all of it's modifiers and the object. If you are wondering why the object is inside the VP and not in it's own NP outside the VP, it's because: the subject and object is called the **"Predicate"** and the verb effects the object. The optional CP here is for CP chosen by the verb (like: "I know *that* he left", "I wonder *whether* the show ended").

Now V' (V-bar). V-bar points to verbs with it's closer modifiers. Neg just means a negation particle/word that negates the verb. Magvo-Stellarean only has *one* negation particle (nīr). "AdvP" means "Adverb Phrase"; it means a phrase headed by an adverb but think of it as an adverb with it's degree. You might be wondering why an AdjP* is followed right after, don't adjectives modify nouns? The adjective here is a **"Predicate Adjective"**; an adjective inside the predicate/followed by a verb; for example: in the sentence "I feel happy": happy is the predicate adjective. The NP and \[Conj NP]\* is the object.

Now PP. PP means a phrase headed by a preposition but think of it as a preposition with it's NP or VP. {VP, NP} means there can either be an VP or NP; there can't be no VP/NP after a preposition (or both at the same time; if the NP is outside VP that is). You might be wondering why there is PP inside both NP, N', VP and V'. This is because prepositions closer to the noun/verb are put inside the PP inside N'/V' and looser prepositions are put inside the PP inside NP/VP.

Going back to S, \[Conj S]* means sentences can be linked together by a coordinate conjunction.

Now Q. Q means a question particle (in Magvo-Stellarean), it turns the sentence into a question and also asks the type/content (asking for a type of information).

Magvo-Stellarean also follows a strict order on preposition order, adjective order and adverb order. The order of prepositions are:

Agent > Means > Manner > Instrument > Reason > Comitative > Comparative > Directional > Place > Time

Let's go what each means.

*Agent* comes first; agent means who is the doer of action/experiencer of an experience/creator of a creation; for example: "The cake was eaten *by* the man", "love is felt *by* Maria", "Judas *by* Lady Gaga".

*Means* come next; means mean the method of the action/how it was done; for example: "She made the food *by* cooking", "He went to the store *by* car". 

*Manner* means the style/quality of the action; for example: "He had to leave *in* a hurry", "She handled the children *with* care".

*Instrument* means by what tools was the action done; for example: "He cut the carrots *with* a knife", "He framed the picture *with* nails and hammer".

*Reason* means the reason for the action; for example: "Matthew went to the cafe *to* relax", "Jessica does her job *for* money".

*Comitative* means who the action was done with; for example: "Mark joined the army *with* Roger", "Daniel climbed the stairs *with* Emilia".

*Comparative* means comparison; by what the noun is being compared to; for example: "Drew is taller *than* Mike", "Andrew runs fast *like* a cheetah."

*Directional* means direction; where the noun is going/comes from; for example: "Jenna walks *to* the store", "Henry is *from* London", "The coffee fell *off* the table", "He climbs *up* the mountain."

*Place* means in what place the action occurred/will occur/where the noun is; for example: "She threw up *on* the sink", "Meet me *at* my house", "The cat is *in* the box".

*Time* means when the action occurred/will occur; for example: "The dinner was finished *by* night", "David was told to met Alex *at* 6 PM."

---

The order of adjectives are:

Age > Material > Origin > Shape > Size > State > Color > Opinion

*Age* means how young/old is the noun; for example: "the *young* maiden", "the *old* man", "the *middle-aged* worker".

*Material* means what material the noun is made of; for example: "The *clay* tablet", "The *rocky* surface", "The *iron* armor".

*Origin* means the origin of the noun; for example: "The *French* food", "The *Chinese* outfit", "The *Russian* land".

*Shape* means the shape of the noun; for example: "The *square* tablet", "The *round* earth", "The *rectangular* box".

*Size* means the size of the noun; for example: "The *small* dog", "The *big* house", "The *tall* rabbit".

*State* means the state of the noun; for example: "The *burning* city", "The *broken* vase", "The *hollow* hole".

*Color* means the color of the noun; for example: "The *blue* sky", "The *yellow* star", "The *green* grass".

*Opinion* means the opinion the speaker has about the noun; for example: "The *bad* wolf", "The *great* king", "The *horrible* outcome".

---

The order of adverbs:

Manner > Place > Time > Frequency > Subject-Oriented > Modal > Pragmatic > Opinion

*Manner* means in what way the action was done; for example: "He ran *quickly*", "She sleeps *peacefully*", "John ate *steadily*".

*Place* means where the action happened; for example: "John ran *outside*", "She lives *here*", "Emily works *there*".

*Time* means when the action happened/will happen; for example: "The work was done *yesterday*", "The homework will arrive *soon*", "The message will be received *tomorrow*."

*Frequency* means how often the action is done; for example: "Drake eats *often*", "Harry studies *rarely*", "He draws *sometime*."

*Subject-Oriented* means the mental state, intention and disposition of the subject; for example: "She ate *reluctantly*", "He helps *kindly*", "Sarah laughed *accidentally*".

*Modal* means the speaker's degree of certainty about the action; for example: "They forgot *probably*", "Jake left *obviously*", "Paul lied *apparently*"

*Pragmatic* means how the speaker frames their own utterance; for example: "I forgot, *honestly*", "We need to talk, *seriously*", "I apologize, *sincerely*".

*Opinion* means the speaker's opinion about the action; for example: "Daniel was saved, *fortunately*", "The vase broke, *sadly*", "She agreed, *surprisingly*".

# Affix Order (Morphotactics)

The way affixes are ordered is by *scope*. That alone sounds a bit vague and it is, so let me explain further. Derivational morphemes come first and inflectional morphemes come next.

But saying derivational morphemes come first then inflectional morphemes is still a bit vague. So to figure out scope: look if the affix is modifying the root word, the affixed root word, the affixed affixed root word and so on, the affix the modify the root words come first, then the affix that modify the affixed root and so on. Think of it as: affixes which modifies the core word comes first and the affixes which modify the modified words come next and so on.

Also, the same thing applies to free morphemes combining into one word aswell.

*(Quick Note: I also wanted to put what will constitute as a prefix or suffix since Magvo-Stellarean uses both but I decided I'll figure it out as I go and give the reason why.)*

# Grammatical Morphemes

Grammatical morphemes are words that convey a grammatical meaning (alongside a semantic one). They are a closed-class category; i.e: they are built into the language and *typically* does not accept new additions (unlike nouns and verbs).

Functional morphemes are grammatical morphemes that can stand on their own. Morphemes that can stand on their own are called **"Free Morphemes"**. Inflectional morphemes are grammatical morphemes that *cannot* stand on their own; they need a word. Morphemes that need a word are called **"Bound Morpheme"** (affixes).

## Functional Morphemes

### Complimentizers

1. Ø: Declarative ("that"). You might be confused by "Ø" as this is not an letter in the RMSS or Magvo-Stellarean's marked alphabet. Ø (it's name "null") means that, in the C slot: you do not put anything there *and* you do not pronounce it (there is no pronunciation for it in Magvo-Stellarean anyways). This is called juxtaposing (here).  
2. pir: "pir" is a complimentizer that expresses uncertainty; similar to how "whether"/"if" expresses uncertainty in some sentences in english.  
3. dūko: "dūko" is a complimentizer that expresses a command/order given by the speaker.  
4. ōsb: "ōsb" is a complimentizer that expresses purpose; similar to "to"/"so that"/"in order to" in english.  
5. sib: "sib" is a complimentizer that expresses concession ("despiteness" if you can call it); similar to "although" in english.  
6. bis: "bis" works similarly to "sib" with the difference being "sib" expresses a factual concession and "bis" expresses a hypothetical concession; similar to "even if" in english.  
7. sūlūs: "sūlūs" is a complimentizer that expresses a clause happened/is happening/will happen at a point in time; similar to "when" and "while" in english. When and while are the same word in Magvo-Stellarean as tense affixes tells when it's happening.  
8. xīn: "xīn" is a complimentizer that expresses the matrix (main) clause happened after the compliment clause; similar to "after" in english.  
9. nīx: "nīx" works similar to xīn with the only difference being the matrix clause happens *before* the compliment clause; similar to "before" in english.  
10. kʰerpi: "kʰerpi" is a complimentizer that expresses that the matrix clause will happen/will not happen until the compliment clause is fulfilled; similar to "until"/"unless" in english.
11. qōv: "qōv" is a complimentizer that expresses a comparison difference between the clauses; similar to "than" in english.  
12. vōq: "vōq" is a complimentizer that expresses a comparison similarity between the clauses: similar to "as" in english.  
13. cuz: "cuz" is a complimentizer that expresses reason/cause; similar to "because" in english.  
14. t̪ʰīf: "t̪ʰīf" is a complimentizer that expresses a condition; similar to "if" in english. T̪ʰīf and sūlūs is similar because they both can express condition but t̪ʰīf emphasizes that the condition is hypothetical while sūlūs emphasizes that the condition will more likely happen.

Most question particle (excluding: vyīn and vanat̪. See [Question Particle](#question-particles)) are also complimentizers; often paired with the verb "know".

### Determiners

1. pæxo: "pæxo" is a determiner that expresses the noun is close to the speaker; similar to "this" in english.
2. vōnj: "vōnj" is a determiner that expresses the noun is far *but* not to far—mid range—from the speaker.
3. mīūn: "mīūn" is a determiner that expresses the noun is far from the speaker; similar to "that" in english (like: "that dog").
4. ūn: "ūn" is a determiner that refers to a noun that has been previously mentioned (aforementioned); similar to "that" in english (like: "that (aforementioned) man". That does a lot of things in english).
5. kom: "kom" is a determiner that selects all instances inside a (noun) category; similar to "all" in english.
6. t̚um: "t̚um" is a determiner that selects most (not all) instances inside a (noun) category; similar to "most" in english.
7. mut̚: "mut̚" works similar to t̚um with the difference being it selects a few instances inside a (noun) category; similar to "few" in english.
8. jat: "jat" is a determiner that selects many (but not most or all) instances inside a (noun) category; similar to "many" in english.
9. taj: "taj" works similar to jat with the difference being it selects a few instances inside a (noun) category. Taj is different from mut̚ as mut̚ only selects a minority while taj selects a bigger minority; still being smaller than jat, and jat is smaller than t̚um.
10. kit̪: "kit̪" is a determiner that selects any number of instances inside a (noun) category; that could be most, many or few. It's used to express that the speaker is uncertain about the volume. It is similar to "some" in english.
11. esīsta (es + -īsta): 1st person singular possessor ("my"/"mine" in english. See [Case](#case) and [Pronouns](#pronouns) for 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21).
12. darīsta (dar + -īsta): 2nd person singular possessor ("your"/"yours" in english).
13. t̪ʰed̪aīsta (t̪ʰed̪a + -īsta): 3rd person singular possessor ("his"/hers" in english)
14. esdarsaīsta (esdarsa + -īsta): inclusive 1st person dual plural possessor (inclusive "our both" in english).
15. esdariymīsta (esdariym + -īsta): inclusive 1st person plural possessor (inclusive "our" in english).
16. essaīsta (essa + -īsta): exclusive 1st person dual plural possessor (exclusive "our both" in english).
17. esiymīsta (esiym + -īsta): exclusive 1st person plural possessor (exclusive "our" in english).
18. darsaīsta (darsa + -īsta): 2nd person dual plural possessor ("your both" in english).
19. dariymīsta (dariym + -īsta): 2nd person plural possessor ("your all" in english).
20. t̪ʰed̪asaīsta (t̪ʰed̪asa + -īsta): 3rd person dual plural possessor ("their both" in english).
21. t̪ʰed̪aiymīsta (t̪ʰed̪aiym + -īsta): 3rd person plural possessor ("their"/"theirs" in english).

All numbers can also be determiner; like in the example "three dogs": three is a determiner.

### Conjunctions (Coordinate)

1. ent: "ent" is a conjunction that connects words, phrases or even clauses together of equal importance; similar to "and" in english.
2. zōc: "zōc" is a conjunction that list alternatives where one, all or any sequence can be possible; similar to the inclusive "or" in english.
3. cōz: "cōz" works similar to zōc with the difference being cōz is exclusive instead if inclusive; that means only *one* element (word, phrase, clause) can be possible.
4. deŋ: "deŋ" is a conjunction that contrasts the preceding element (word, phrase, clause); similar to "but" in english.

### Preposition

1. ðaf: agent preposition ("by" in english).
2. vīs̚: means preposition ("by" in english, they are different).
3. stōn: manner preposition.
4. wūz: instrument preposition ("with" in english).
5. wenpʰri: reason preposition ("to"/"for" in english).
6. īzc: comitative preposition ("with" in english, they are different).
7. virto: difference comparative preposition ("than" in english).
8. oθiv: same comparative preposition ("as" in english).
9. yaæj: goal directional preposition ("to" in english).
10. hīz̚: source directional preposition ("from" in english).
11. eqil: in-and-out directional preposition ("through" in english).
12. nior: side-to-side directional preposition ("across" in english).
13. bæken: parallel directional preposition ("along" in english).
14. wæxo: above directional/place preposition ("over" in english).
15. fav: below directional/place preposition ("under" in english).
16. t̪ism: by-and-beyond directional preposition ("past" in english like "he walked past her").
17. kyr: circular directional/place preposition ("around" in english).
18. hōns: up vertical directional preposition ("up" in english).
19. psr: down vertical directional preposition ("down" in english).
20. rīvs: left horizontal directional/place preposition ("left"/"left of" in english).
21. yanto: right horizontal directional/place preposition ("right"/"right of" in english).
22. ŋus: front depth directional/place preposition ("front"/"front of" in english).
23. svir: behind depth directional/place preposition ("behind"/"behind of" in english).
24. æj: point place preposition ("at" in english).
25. ŋōl: enclosed place preposition ("in" in english).
26. wek: surface place preposition ("on" in english).
27. īvs: near place preposition ("near" in english).
28. cʰog: mid-range place preposition.
29. udsa: far place preposition ("far from" in english).
30. podom: between place preposition ("between" in english).
31. jax: beyond place preposition ("beyond" in english).
32. vyic: time preposition ("at" in english, they are different).

### Modal Verbs

1. gōs̚p: obligatory/necessity modal ("must" in english).
2. veb: weaker obligatory/necessity modal ("should" in english)
3. kīūg: possibility modal ("may" in english).
4. koag: possibility modal with lower confidence.
5. kiug: possibility modal with higher confidence.
6. qæŋ: ability modal ("can" in english).
7. eiθig: obligation-not-required modal ("don't have to" in english).
8. zobe: sight evidentiality modal (the speaker saw).
9. zacīs: audible evidentiality modal (the speaker heard).
10. zoap: feeling evidentiality modal (the speaker felt).
11. uyls: inferred evidentiality modal (the speaker inferred from evidence).
12. kūlk: reported/hearsay evidentiality modal (the speaker heard from another source).
13. ræf: assumptive evidentiality modal (the speaker assumes).
14. hej: hypothetical modal ("would"/"would have" in english).

### Degrees

1. dukis: "dukis" is a degree that makes the adj/adv too little in intensity.
2. ofsan: "ofsan" is a degree that makes the adj/adv barely enough in intensity.
3. yep: "yep" is a degree that makes the adj/adv low in intensity.
4. bæŋī: "bæŋī" is a degree that makes the adj/adv mid in intensity.
5. zerito: "zerito" is a degree that makes the adj/adv high in intensity.
6. exaiv: "exaiv" is a degree that makes the adj/adv extremely high in intensity.
7. hlas: "hlas" is a degree that makes the adj/adv full in intensity
8. cʰisl: "cʰisl" is a degree that makes the adj/adv excessive in intensity.
9. vaz̚: "vaz̚" is a degree that makes the adj/adv sufficient/enough intensity.
10. wel: "wel" is a comparative degree (commonly not used when there is virto).
11. θīno: "θīno" is a equative degree (commonly not used when there is oθiv).
12. wūsyil: "wūsyil" is a superlative degree.

### Pronouns

Note that Magvo-Stellarean does not give nominative and accusative case unlike english.

1. es: 1st person singular pronoun ("I"/"me" in english).
2. dar: 2nd person singular pronoun ("you" in english).
3. t̪ʰed̪a: 3rd person singular pronoun ("he"/"she"/"it", Magvo-Stellarean doesn't distinguish it by gender).
4. esdarsa (es + dar + -sa): inclusive 1st personal dual plural; it includes both the speaker and listen, *no one else* (inclusive "we" in english but it takes two people. See [Plurality Marking](#plurality-marking) for 4, 5, 6, 7, 8, 9, 10, 11).
5. esdariym (es + dar + -iym): inclusive 1st person plural; it includes the speaker, the listener and other people (inclusive "we" in english).
6. essa (es + -sa): exclusive 1st person dual plural; it includes the speaker and someone else *but* not the listener (exclusive "we" in english but it takes two people)
7. esiym (es + -iym): exclusive 1st person plural; it includes the speaker, other people *but* not the listener (exclusive "we" in english).
8. darsa (dar + -sa): 2nd personal dual plural; it includes the listener and another person that isn't the speaker ("you both" in english).
9. dariym (dar + -iym): 2nd person plural; it includes the listener, other people *but* not the speaker ("you all" in english).
10. t̪ʰed̪asa (t̪ʰed̪a + -sa): 3rd person dual plural; it includes two people not in the conversation ("they both" in english).
11. t̪ʰed̪aiym (t̪ʰed̪a + -iym): 3rd person plural; it includes 3 or more people not in the conversation ("they" in english).

### Focus Particles

Syntactically: focus particles are adverbs/adjectives but semantically have a different use than to regular adverbs/adjectives. Focus particles focuses on a constituent (a part of a sentence) of a sentence and tells something about the alternative to the focus relative to the background. It basically focuses on a part of a sentence and tells something about the other options of the focused part.

1. d̪i: "d̪i" is a focus particle that eliminates all the other alternatives ("only" in english).
2. yio: "yio" is a focus particle that says the focused constituent is least likely to do the action stated in the background and the action is still done ("even" in english).
3. n̚ō: "n̚ō" is a focus particle that says the focused constituent noticeably done/does the action stated in the background ("especially" in english).

### Negation

As stated previously, Magvo-Stellarean only has *one* negation particle which is "nīr".

### Question Particles

1. vyīn: "vyīn" is a question particle where the speaker expects a yes or no answer.
2. væmo: "væmo" is a question particle that asks the identification of a person ("who" in english).
3. væko: "væko" is a question particle that asks the identification of a non-person/thing (object, event, content, etc. "what" in english).
4. vūst: "vūst" is a question particle that asks the method of an action ("how" in english).
5. vid: "vid" is a question particle that asks the manner of an action ("how" in english, they are different).
6. vōl: "vōl" is a question particle that asks the place of an action ("where" in english).
7. vīb: "vīb" is a question particle that asks the time of an action ("when" in english).
8. vunu: "vunu" is a question particle that asks the reason of an action ("why" in english).
9. vanat̪: "vanat̪" is a question particle that signals the speaker is confused and wants clarification ("what" in english, they are different).
10. vista: "vista" is a question particle that asks who/what owns the thing/entity stated ("whose" in english).
12. vlos: "vlos" is a question particle that asks with who/what the action was done ("with who" in english).
13. vkaf: "vkaf" is a question particle that asks with what (instrument) the action was done ("with what" in english).

## Inflectional Morphemes

### Tense

All tenses are prefixes because I feel like that when something happens should come first.

1. īr-: marks the future.
2. īb-: marks the present.
3. īd-: marks the past.

### Plurality Marking

All plural markings are suffixes because I feel like that the number of something should come after.

1. -sa: marks that the noun is exactly two; not more or less. -sa can also be used with verbs to emphasize that the verb happened *twice* but is usually not added.
2. -iym: marks that the noun is 3 or more. -iym can also be used in a verb to emphasize a verb has happened *many times* but is usually not added.
3. -un: -un is used with verbs to emphasize that a verb happened *once* but is usually not added. -un is not used for nouns.

### Case

All case markings are suffixes as I feel like where a noun belongs should come after.

1. -īsta: genitive marking; makes the noun a possessor of another noun; similar to "'s" in english.
2. -eo: dative marking; marks the indirect object/recipient.

### Preposition Disambiguation

Prepositional disambiguation inflections disambiguates adnominal preposition (the preposition belongs to the object) and adverbial preposition (the preposition belongs to the verb).

1. -ce: adnominal preposition
2. -aī: adverbial preposition

# Aspect

Aspect is always marked with tenses (and plurality with habitual).

- Perfective & Perfect (Magvo-Stellarean doesn't separate them): īd-\[verb].
- Imperfective Progressive: <īd/īr depending on past/future, nothing for present>-\[subject] īb-\[verb].
- Imperfective Habitual: <īb/īd depending on if the habit still happens or used to happen>-\[verb]-iym

# Numbers

Magvo-Stellarean has it's own number writing system but we will use the arabic numbers (1, 2, 3...) we all know with using RMSS.

<img src="images/Magvo-Stellarean/Magvo-Stellarean%20numbers.jpg">
(Magvo-Stellarean numbers)

The image shows the name of the said numbers but I'll still list them here:

- dax: zero
- un: one.
- sa: two.
- opes: three.
- nac: four.
- wifen: five.
- ætqaz: six.
- yejōs: seven.
- fūhīr: eight.
- mæval: nine

For numbers greater than nine: Magvo-Stellarean uses scientific notation to count their numbers, that is: $n\times 10^m+x$. The suffix "-uzi" indicates the number is being multiplied by ten; so to say 10 in Magvo-Stellarean, you say: "unuzi"; to say 12, you say: "unuzi sa"; to say 58, you say: "wifenuzi fūhīr". Remember the format being: n + -uzi (+ x).

When m>1 ($10^2$, $10^3$ etc), you use: ī- + m at the end of uzi; in other words: use ī- + \[number of m] at the end of uzi. "ī-" turns the number (m) into a suffix that attaches to the suffix uzi, "ī-" indicates that the number is raised to a power. To say 100 in Magvo-Stellarean, you say: "unuziīsa"; to say 2,011, you say: "sauziīopes unuzi un". Remember the format being: n + -uzi + ī- + m (+ x)

A problem arrives when we wanna say something like $2\times 10^{12}$ (2 trillion), with our current understanding, we would write it as: "sauziīunuzisa". In text, there is no ambiguity since there is no space but in speech: it can either be 2 trillion or 20 billion and 2 (sauziīunuzi sa). So to disambiguate the 2 trillion from 20 billion and 2: we use "e-", which indicates it belongs to the powered number (and also turns it to a suffix). So to actually say 2 trillion in Magvo-Stellarean, you say: "sauziīunuziesa". To say $2\times 10^{22}$, you say: "sauziīsauziesa". The pattern follows for m=100+. Remember the format being: n + -uzi + ī- + y (y being the first number of m) + e- + z (z being the second number of m) (+ x)

The prefix "s̪i-" makes the number an ordinal number (1st, 2nd, 3rd, 4th, 5th, etc). So, "s̪iun" means 1st, "s̪isa" means 2nd, "s̪iopes" means 3rd, "s̪inac" means 4th, "s̪iwifen" means 5th, "s̪iunuziīsa" means 100th and so on. You write ordinals in number (1st, 2nd, 3rd, not first, second, third) by: s̪i- + \[number]. So s̪i1 is 1st, s̪i2 is 2nd, s̪i3 is 3rd and so on.

# Root Words

Root words (root morpheme) is the core meaning of a word with affixes; in the word "unhappiness": "happy" is the core meaning while the affixes "un-" and "-ness" attach to the word to modify it.

In Magvo-Stellarean root words are always free morphemes (other languages can have bound root morphemes; like "ceive" with "receive" and "perceive" in english).

This section will show the root words of Magvo-Stellarean.

## Verbs

Before going into the list of verbs, each verb has a subcategory which tells if a verb is transitive, intransitive, ditransitive or takes other arguments. The notation for that is written as: V (__ XP) where V is the verb, __ is where the verb is placed and XP are any additional/required arguments. Also note that verbs with (__ NP) and (__ (NP) ) also means (__ AdvP)/(__ (AdvP) until stated otherwise and (__ NP) verbs can drop the NP if there is a modal before it or if it's habitual. 

1. fæs: eat/drink/consume (__ NP)
2. tʰapos: asleep (__ (PP) )
3. θība: trying to sleep but not yet fallen asleep (__ (PP) )
4. fimi: exist; sometimes used in the modal slot as the copula "to be" for emphasis (__)
5. æko: act (__ NP)
6. yahūl: live, as in to be alive (__)
7. yamīr: die (__)
8. leŋf: live, as in to live in a place (__ ŋōl NP)
9. vīg: to feel something about someone, with the prefix "pye-": it turns to "pyevīg"—which means like—and with the prefix "ban-" it turns to "banvīg"; which means dislike. Vīg on it's own means having a neutral feeling for someone (__ NP)
10. dujes: move with your legs; walk (__ (PP) )
11. fake: speak (__ NP)
12. ōnðov: write (__ NP)
13. savart: teach (__ NP)
14. kemat̪: learn/study (__ NP)
15. vik: feel (in general) (__ NP/AdjP)
16. hōt̚a: give (__ $\text{NP}_{\text{direct}}$ $\text{NP}_{\text{recipient}}$)
17. xonon: get (__ $\text{NP}_{\text{direct}}$ $\text{NP}_{\text{recipient}}$)
18. caz̚ul: put (__ NP PP)
19. rūq: pull (__ NP)
20. rūx: push (__ NP)
21. fæfur: fight (__ NP)
22. mirja: kill/murder (__ NP)
23. wil: have/possess (__ NP)
24. kuris: create/build (__ NP)
25. θazæx: destroy/break (__ NP)
26. mot: control/rule/govern (__ NP)
27. nvalīpk: go/move (__ (PP) )
28. zekʰyupl: know (__ NP/CP)
29. gecbaqt: stay/remain (__ (PP) )
30. pamef: follow (movement) (__ NP)
31. vepn̚iw: lead (__ NP)
32. ohiz: command/order (__ NP)
33. jūhūs: swim (__ (PP) )
34. ybles: fly (__ (PP) )
35. waro: crawl (__ (PP) )
36. fūvas: jump (__ (PP) )
37. pīson: wander/roam (__ (PP) )
38. goōni: sit (__ (PP) )
39. elŋæzu: stand (__ (PP) )
40. leyfa: lean (__ AdvP)
41. piosc: hold/carry (__ NP)
42. ðajama: drop (__ NP)
43. qix: throw (__ NP)
44. Dejʰō: change/turn (__ NP (PP) )
45. seiba: open (__ NP)
46. abies: close (__ NP)
47. wumīlŋe: cover (__ NP)
48. vikom: uncover (__ NP)
49. æges: see/look/watch/ (__ NP)
50. fsares: hear/listen (__ NP)
51. nomeŋ: smell (__ NP)
52. lūgæmi: taste (__ NP)
53. kegat: touch (__ NP)
54. kōgset: think (__ NP/CP)
55. tlafos̚ec: believe (__ NP/CP)
56. θyæxcu: understand (__ NP/CP)
57. favæse: remember (__ NP/CP)
58. savæfe: forget (__ NP/CP)
59. hōjīs: doubt (__ NP/CP)
60. gyavp: guess (__ NP/CP)
61. fede: decide (__ NP/CP)
62. laqŋog: choose/select (__ NP/CP)
63. būsdec: dream (__ PP/CP)
