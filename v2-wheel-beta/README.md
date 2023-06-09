# v2 wheel beta

it's a beta.  you've been warned.

| `r1` | [`wheel-beta-r1`](./stl/wheel-beta-r1.stl) |
| :---: | :---: |


---

### background...

the pika buffer project started with my ercp frustration, but as with any open source project it still made sense to copy over the things that worked.  and who reinvents the wheel, right?

life progressed, and pika users started asking for more buffering capacity - up to 2600mm!  the most obvious way to add extra capacity was to make the buffer itself larger, but something about changing the aesthetic of my nice compact little buffer was holding me back, and I got thinking about the wheel...

well, there are plenty of people who [reinvent the wheel](https://en.wikipedia.org/wiki/Shark_Wheel), which got me thinking about the limitations of the stock ercp wheel, and what could be done to improve it.  the thought driving me was this:

- *there isn't a lot of space for the filament to sit next to itself, as the channel is very narrow in the flat center due to the angled overhangs... would an area wide enough for all loops to sit next to eachother lead to fewer tangles?  less friction?*
- *given enough room on the wheel, what is the maximum number of loops and filament that can be buffered without changing overall design?*
- *each diameter of the wheel is space in the buffer that isn't actually buffering the reverse bowden.  can the wheel be smaller?*
- *has anyone actually studied the mechanics of all of this?*

it turns out, there are scientists who study this stuff.

one of the [studies I found](./JS0q4v-jom_v35_1_131.pdf) investigated coiling and uncoiling effects in commercial cable systems, and demonstrated that an off-center drum like this resulted in a more uniform system:

![drum](./drum.png)

so I started there and tried to answer my questions with different designs and experimentation.

### next steps

I've documented most of what I discovered [in the base README](../README.md#how-much-can-i-buffer), and had a few people besides me experiment with the new wheel with a decent degree of success.  now it's time for a slightly wider audience.

remember: it's a beta, so there are no guarantees here.  if you use it on a 500 hour print and things go awry, well...

### thanks

many thanks to the early beta testers:

- @ningj V2.2726
- @Imburr VT.959
