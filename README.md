## Hi there 👋

<!-- [![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=cognominal)](https://github.com/anuraghazra/github-readme-stats)
<a href="https://github.com/cognominal">
-->
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cognominal&theme=ayu-mirage&hide=css,html,markdown&langs_count=5" />

* [Go to New Plan](#new-plan)

I want to eventually port the raku [grammar engine](https://docs.raku.org/language/grammars) to wasm and support the [LSP](https://microsoft.github.io/language-server-protocol/) for the languages developped using this grammar.
Adapting rust regex engine seems the most promising way except I have to learn rust. I will probably document my progress using a kanban on notion.
Also I have many notes that I will consolidate there.
Supporting a [treesitter](https://tree-sitter.github.io/tree-sitter/) will necessitate to snapshot the compilation of compunits, so as to restart from any snapshot. Textmate grammars won't cut it.
An early work for a treesitter for raku is [hamt](https://github.com/cognominal/hamt-for-raku-moarvm).

To leverage this putative engine, tentatively called `slangs`, 
I try to get some proficiency in all things web with a focus on the modern web which is a daunting stack given my current level. At least I have now a better
but chainging view of what I know and want to know :

*  web frameworks 
    * [svelte 5](https://svelte-5-preview.vercel.app/docs/introduction)/[sveltekit](https://kit.svelte.dev/)
*  doing server side stuff client side to do complete demos : [stackblitz](https://stackblitz.com/)
*  components: [daisyui](https://daisyui.com/), [svelte-shadcn](https://www.shadcn-svelte.com/)
*  styling : [tailwindcss](https://tailwindcss.com/)
*  [TUI](https://en.wikipedia.org/wiki/Text-based_user_interface): [neovim](https://en.wikipedia.org/wiki/Vim_(text_editor)#Neovim), [lazygit](https://github.com/jesseduffield/lazygit), [charm tools](https://charm.land/) including [crush](https://github.com/charmbracelet/crush) the TUI AI interface.
*  I am moving my M2 laptop to [omarchy](https://omarchy.org/), which uses [hyprland](https://hypr.land/). I do so using a variant of [asahi](https://asahilinux.org/), with [asahi-alarm](https://asahi-alarm.org/) which is [arch](https://archlinux.org/) based instead of [fedora](https://fedoraproject.org/) based  but I have to do it semi manually because the omarchy install script is intel dependant. That means forfeiting [raycast](https://www.raycast.com/).
*  tty multiplexer : [zellij](https://zellij.dev/) a nod to [islamic art](https://en.wikipedia.org/wiki/Zellij).

 Various repositories will embody my progress using sideprojects focusing on specific technologies.

 Also I learn various tool to organize myself on my macbook : 
 [raycast](https://en.wikipedia.org/wiki/Raycast_(software)) a kitchen sink app switcher, [arc](https://arc.net/) to organize my browsing, [notion](https://www.notion.so/) to organize notes and projects, [whimsical](https://whimsical.com/)  as a mind mapping and design tool.

 ## New master plan

 I changed my plan. Twice. 
 
 - Instead of doing a grammar engine, inspired by svelte that extends the acorn AST, I want to do the polar opposite, doing sructural editing that update the AST and `unparse` the AST into a rich surface representation. I will use a modified [svelte](https://svelte.dev). So the use of codemirror. I had even a beginning of a site at [slangs](https://slangs.vercel.app/) to learn about svelte and tailwindcss.
 - TUIs are the way to go fast. So I got into the neovim ecosystem. My story: 3 years of vi, 30 years of emacs, various attempts with textmate,atom... 5 years of vscode, 2 weeks of neovim and going.

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
