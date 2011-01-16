[Mustache] is a simple, logic-less templating language. Flatstache supports an even simpler subset of template features: just escaped or unescaped mustachios from a flat dictionary: 

	Flatstache.to_html("{{test}}{{{ing}}}, {{what}}{{not}}", {test:'Win', ing:'ning', what: "I dunno the \"<3\" contest maybe?"});

Outputs a string suitable for use as an element's innerHTML: "Winning, I dunno the &quot;&lt;3&quot; contest maybe?"

So it's kind of like mustache.js loses to printf without the 'f' or...something. But it's small (~1kB)!