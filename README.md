Ocean
=====

This is the Ocean programming language lab.

Ocean is based upon the idea that every problem becomes simple if you have the right parser generator at your side.

With a careful decoupling of language syntax and parser rules, Ocean implements Knuth's Attribute Grammars fused
with Ford's Parsing Expression Grammars.  This is a powerful combination made reasonable by lazy evaluation and
a "cut" operator to prune the grammar search.

Parsers are aggressively exploited, as in Piumarta's work for the STEPS project.  This makes Ocean not just a compiler,
but a full-fledged application framework that transforms simple grammars with rules in your favourite language into
software agents that monitor and respond to data flows.

Michael FiG, <ocean@michael.fig.org>, 2013-09-04
