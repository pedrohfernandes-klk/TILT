TILT

Definitions at an angle.

TILT is a one-button crooked dictionary for second thoughts.

It gives the user a familiar word or object, then defines it from the wrong angle: sharper, stranger, more revealing, and slightly unfair in the useful way.

It is not a normal dictionary.

It is a machine for making certainty wobble.

WHAT IT IS

TILT is a self-contained browser app built as a single HTML file.

It contains a curated deck of 999 definitions. Each card takes a familiar term and tilts it sideways, turning ordinary language into a small diagnostic instrument.

The app is built for quick use.

Press once.

Read the definition.

Keep the line that makes something shift.

Most cards will miss. That is part of the mechanism. The useful one is the definition that makes a common word feel newly suspicious, funny, painful, exact, or alive.

CURRENT STATUS

App: TILT
Deck size: 999 definitions
Format: single-file HTML
Mechanism: one-button random card draw
Storage: local browser/session only
Backend: none
Build step: none
Version status: complete 999-card crooked dictionary build

CORE INTERACTION

The app has one primary action:

TILT

Each press selects one random definition from the internal deck and displays it in the output window.

Secondary controls:

COPY copies the current definition.

CLEAR resets the display.

ABOUT opens the app’s information panel.

RETURN closes the ABOUT panel and returns to the main view.

Keyboard interaction:

SPACE or ENTER draws a card from the main view.

ESC returns from the ABOUT panel.

INTENDED USE

TILT is useful for:

creative prompts
aphoristic writing
essay sparks
caption ideas
dialogue fragments
satirical definitions
worldbuilding texture
conceptual reframing
thinking exercises
social observation
short-form literary material
opening lines
titles and subtitles
visual prompt generation

A card can be used as:

a title
a caption
a first sentence
a character thought
a dialogue line
a chapter epigraph
a writing prompt
a philosophical joke
a distorted glossary entry
a seed for a short essay
a line in a fictional handbook

CONTENT PRINCIPLE

A good TILT card should define a familiar thing from an unexpected but recognisable angle.

It should feel like a dictionary entry that has had one drink too many, read some philosophy, and decided to stop pretending neutrality exists.

The best cards combine:

a familiar word
a precise twist
a small sting
a usable image
a clear sentence structure

Example:

A calendar: a grid used to trap the future.

That works because the word is ordinary, the image is immediate, and the definition changes the way the object feels.

STYLE RULES FOR FUTURE CARDS

Keep the card short.

Start with a clear term.

Use the structure:

A term: definition.

or:

Term: definition.

The definition should be compact, sharp, and immediately understandable.

Prefer plain words.

Prefer strong images.

Prefer wit with meaning.

Prefer recognisable distortions over random absurdity.

Avoid long explanations.

Avoid vague profundity.

Avoid generic jokes.

Avoid definitions that are merely decorative.

Avoid cards that sound like advice.

Avoid cards that become BADVICE.

Avoid cards that become IDK MACHINE prompts.

Avoid cards that become SAID IT-style social callouts.

Avoid cards that become FALSE POSITIVE-style diagnostic reframes.

TILT should feel like a crooked dictionary, not a quote machine.

GOOD CARD TEST

Before adding a new card, ask:

Is the term familiar?

Is the definition unexpected?

Is the image clear?

Is the sentence tight?

Does it make the word feel newly unstable?

Could it be used as a line in an essay, scene, caption, or dialogue?

Does it avoid over-explaining itself?

Does it still sound like TILT?

DECK STRUCTURE

The deck lives inside the JavaScript array named CARDS.

Each card is a plain text string.

Example structure:

"A calendar: a grid used to trap the future."

The app does not use separate themes or object fields.

The definition itself contains the term.

The deck should remain a clean plain-string array unless the app mechanism is deliberately redesigned later.

VISUAL IDENTITY

TILT belongs to the SPARK TOOLS sibling family.

The visual language should remain:

dark terminal
retro CRT atmosphere
green/gold signal palette
warning-red accent
compact one-button interaction
strong central output card
minimal controls
mobile-first layout
slightly crooked diagnostic energy

TILT should feel sharper and more lexical than IDK MACHINE.

It should feel less socially direct than SAID IT.

It should feel less behavioural than BADVICE.

It should feel more playful and definitional than FALSE POSITIVE.

The interface should support the feeling of a measuring instrument slightly out of alignment.

FILES

The app can be used as a standalone file:

index.html

It can also be placed inside a folder on a static site:

tilt/index.html

No extra files are required.

DEPLOYMENT

TILT is static.

To publish it, upload the HTML file to any static web host or to a folder inside an existing website.

Recommended structure inside the SPARK TOOLS site:

spark-tools/
tilt/
index.html

Then the live path should be:

/spark-tools/tilt/

The app does not require a database, server code, package manager, build tool, or installation step.

UPDATING THE DECK

After adding or editing cards, check that:

The total card count is correct.

There are no duplicate card texts.

Every card is a non-empty string.

Every card contains a clear term and definition.

The JavaScript still passes syntax checking.

The DECK counter reflects the current deck size.

The app still loads.

TILT draws a card.

COPY copies the current card.

CLEAR resets the card.

ABOUT opens the information panel.

RETURN closes the information panel.

SPACE or ENTER draws a card from the main view.

ESC returns from the ABOUT panel.

FINAL NOTE

TILT works because it does not explain the world directly.

It turns the word slightly.

That is enough.

A good definition should make the user think:

I knew what that word meant until it moved.

The machine does not provide certainty.

It gives certainty a bad angle.
