Why should I migrate to Charset-Normalizer?
===========================================

There is so many reason to migrate your current project. Here are some of them:

- Remove ANY license ambiguity/restriction for projects bundling Chardet (even indirectly).
- X2 faster than Chardet (average) AND support X3 more encoding.
- Never return a encoding if not suited for the given decoder. Eg. Never get UnicodeDecodeError!
- Actively maintained, open to contributors.
- Have the backward compatible function ``detect`` that come from Chardet.
- Truly detect the language used in the text.
- It is, for the first time, really universal! As there is no specific probe per charset.
- The package size is X4 lower than Chardet's (4.0)!
- Propose much more options/public kwargs to tweak the detection as you sees fit!
- Using static typing to ease your development.

And much more..! What are you waiting for? Upgrade now and give us a feedback. (Even if negative)
