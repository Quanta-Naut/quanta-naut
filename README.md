<style>
.terminal {
  background: transparent;
  color: #b2c2e2ff;
  font-family: "Fira Code", "Consolas", "Courier New", monospace;
  padding: 1.5rem 0;
  font-size: 0.95rem;
  line-height: 1.6;
  white-space: pre-wrap;
}
.terminal .ascii-header {
  font-size: clamp(0.4rem, 2vw, 1rem);
  display: block;
  overflow-x: auto;
}
.terminal .username {
  color: #ff6b35;
}
.terminal a {
  color: #ff6b35;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
}
.terminal a:hover {
  border-bottom-color: #ff6b35;
}

@media (max-width: 768px) {
  .terminal .ascii-header {
    font-size: clamp(0.3rem,  0.7rem);
  }
}

@media (max-width: 480px) {
  .terminal .ascii-header {
    font-size: clamp(0.25rem, 2.5vw, 0.5rem);
  }
}
</style>
<div class="terminal">
<span class="ascii-header">
  ___                   _           _   _             _
 / _ \ _   _  __ _ _ __ | |_ __ _   | \ | | __ _ _   _| |_
| | | | | | |/ _` | '_ \| __/ _` |  |  \| |/ _` | | | | __|
| |_| | |_| | (_| | | | | || (_| |  | |\  | (_| | |_| | |_
 \__\_\\__,_|\__,_|_| |_|\__\__,_|  |_| \_|\__,_|\__,_|\__|

 </span>     

<span class="command">$ whoami</span>
<span class="username">quanta naut</span>

<span class="command">$ cat about.txt</span>
developer fascinated by open source, graphics, and rocketry. 
building, experimenting, and learning

<span class="command">$ cat links.txt</span>
portfolio → <a href="https://quanta-naut.github.io/" target="_blank">quanta-naut.github.io</a> 
linkedin  → <a href="https://www.linkedin.com/in/tarsk" target="_blank">linkedin.com/in/tarsk</a> 
instagram → <a href="https://www.instagram.com/quantum._naut/" target="_blank">instagram.com/quantum._naut</a>

<span class="command">$ support --sponsor</span>
github sponsor → <a href="https://github.com/sponsors/Quanta-Naut" target="_blank">github.com/sponsors/Quanta-Naut</a> 
buy me coffee   → <a href="https://buymeacoffee.com/quanta.naut" target="_blank">buymeacoffee.com/quanta.naut</a>

<span class="command">$ exit</span>
</div>
