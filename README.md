## Hi there 👋

* [Go to New Plan](#new-plan)

I want to eventually port the raku [grammar engine](https://docs.raku.org/language/grammars) to wasm and support the [LSP](https://microsoft.github.io/language-server-protocol/) for the languages developped using this grammar.
Adapting rust regex engine seems the most promising way except I have to learn rust. I will probably document my progress using a kanban on notion.
Also I have many notes that I will consolidate there.
Supporting a [treesitter](https://tree-sitter.github.io/tree-sitter/) will necessitate to snapshot the compilation of compunits, so as to restart from any snapshot. Textmate grammars won't cut it.
An early work for a treesitter for raku is [hamt](https://github.com/cognominal/hamt-for-raku-moarvm).

To leverage this putative engine, tentatively called `slangs`, 
I try to get some proficiency in all things web with a focus on the modern web which is a daunting stack given my current level. At least I have now a clear
view of what I want to know :

*  web frameworks 
    * [svelte 5](https://svelte-5-preview.vercel.app/docs/introduction)/[sveltekit](https://kit.svelte.dev/)
    *  the [BETH](https://stackademic.com/blog/beth-a-modern-stack-for-the-modern-web) stack. More modest than svelte with a different focus.
*  doing server side stuff client side to do complete demos : [stackblitz](https://stackblitz.com/)
*  components: [daisyui](https://daisyui.com/), [svelte-shadcn](https://www.shadcn-svelte.com/)
*  styling : [tailwindcss](https://tailwindcss.com/)

 Various repository will embody my progress using sideprojects focusing on specific technologies.

 Also I learn various tool to organize myself on my macbook : 
 [raycast](https://en.wikipedia.org/wiki/Raycast_(software)) a kitchen sink app switcher, [arc](https://arc.net/) to organize my browsing, [notion](https://www.notion.so/) to organize notes and projects, [whimsical](https://whimsical.com/)  as a mind mapping and design tool.

 ## New plan

 I changed my plan. Instead of doing a grammar engine. I want to do the polar opposite, doing sructural editing that update the AST and `unparse` the AST
 into a rich surface representation. I will use a modified [svelte.dev](https://github.com/cognominal/svelte/tree/better-ast-view) to bootstrap the project.
 The blurb is [here](https://github.com/cognominal/svelte/blob/better-ast-view/Lush.md)
<!--
**cognominal/cognominal** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
