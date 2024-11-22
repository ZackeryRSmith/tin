<img alt="Pixel art computer with a tin can on screen" src="https://github.com/user-attachments/assets/949ea187-336b-400d-8ce5-0e4671883a76" align="left"></img>

<div align="center">
  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;">Tin</h1></summary>
    </ul>
    <i>Can you parse terminal input?</i><br />No, but a <b>Tin</b> can!
    <br /><br />
    <h4>
      <a href="#bindings">⛓️ Bindings</a> &nbsp-&nbsp <a href="#examples">📖 Examples</a> &nbsp-&nbsp <a href="#quirks">⚙️ Quirks</a> &nbsp-&nbsp <a href="#build">🔨 Build</a> &nbsp-&nbsp <a href="#contributors">❤️ Contributors</a>
    </h3>
  </div>
</div>

---

# Goal
**Tin** aims to solve a problem given to us from our great ancestors, although at the time they were unaware...
Terminals have been around as early as 1967 (even earlier if you count teletypewriters), and over time many specs of the devices have changed.
Some major turning points include the release of the VT52, and VT100 systems.
Introducing control codes, for tasks like moving the cursor or providig text effects like bold and underline. However, these have been pretty constant throught the years.
What hasn't been very consistent is **input**, getting input from the terminal *past your abc's and 123's* has been different in almost all systems.

Fast forwarding today, backwards compatible jargon has made it an absolute doozy to handle terminal input. So once again, **Tin** aims to solve this provlem given to us down the years.
If the terminals won't change, the developers will. Tin is an avoidance library, without losing *much* capability for the ease of development.
