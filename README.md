<style>
body {
  min-height: 100vh;
  margin: 0;
}

article {
  padding: 5em;
}

.body {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background: white;
  background-color: var(--bg-color, #fff);
  color: var(--color, #000);
  transition: 250ms;
}

#switcher {
  position: absolute;
  -webkit-appearance: none;
     -moz-appearance: none;
          appearance: none;
  top: 1rem;
  right: 1rem;
  width: 4em;
  height: 2em;
  background-color: var(--color, #000);
  border-radius: 2em;
  font-size: 20px;
}

#switcher::after {
  position: absolute;
  top: 0.25em;
  left: 0.25em;
  width: 1.5em;
  height: 1.5em;
  content: "";
  background-color: var(--bg-color, #fff);
  border-radius: 2em;
  transform: translateX(var(--translate, 0));
  transition: 250ms;
}

#switcher:checked {
  --translate: 2em;
  --bg-color: #424242;
  --color: #81d4fa;
}

#switcher:checked ~ * {
  --bg-color: #424242;
  --color: #81d4fa;
}
</style>

<input type="checkbox" id="switcher">
<div class="body">
<article>

Hi, I'm Paul.
**Software engineer** with more than 4 years of working experience.

I speak fluently _French_, _English_ and _Spanish_ along with some _Catalan_.

- Backend developer – DevOps.
- Writer and culture aficionado.

## Experience

Check my <a target="_blank" href="https://www.canva.com/design/DAGZ8D0pvhc/0Npp_HI8-Ir3j4SuWOjT7w/view">résumé</a>.

## Portfolio

### Code

1. <a target="_blank" href="https://github.com/paul-florentin-charles/bcn-rainfall-models/">Analysis and visualisation of Barcelona rainfall</a>.
2. <a target="_blank" href="https://github.com/paul-florentin-charles/dereverberation-ml/">Removal of reverberation via Deep Learning</a>.
3. <a target="_blank" href="https://github.com/paul-florentin-charles/TOSCA-Validator/tree/master/frontend/">Frontend of a webapp validating TOSCA NFV files</a>.
4. <a target="_blank" href="https://github.com/paul-florentin-charles/Youtube-Playlist-Maker/">Generate YouTube playlist URLs</a>.

### Miscellaneous

1. <a target="_blank" href="https://paul-florentin-charles.github.io/dictionnaire/">French dictionary</a>.
2. <a target="_blank" href="https://www.canva.com/design/DAGA6mLTA4k/IG6VHvTyOinJhX-tgxyebg/view">Photobook</a>.
3. <a target="_blank" href="https://medium.com/@paul.florentin.charles/list/poesie-ef2bda8094b4">French poetry</a>.

## Want to work together?

- Check my <a target="_blank" href="https://www.malt.fr/profile/paulcharles/">Malt profile</a>.
- Write me <a href="mailto:paul.charles@tutanota.com">an email</a>.

### Contact me

<form action="https://formsubmit.co/1fac7b1a2dda22da078a09d344d31dec" method="POST" target="_blank">
  <input type="hidden" name="_subject" value="New contact from personal website!">
  
  <label for="name">Your name</label><br>
  <input type="text" id="name" name="name" required><br>

  <label for="email">Your email</label><br>
  <input type="email" id="email" name="email" required><br>
    
  <label for="message">Your message</label><br>
  <textarea id="message" name="body" cols="40" rows="5" required></textarea><br><br>
  
  <button type="submit">Submit</button>
</form>

---

<div style="margin: auto; text-align: center;">
  <a target="_blank" href="https://www.linkedin.com/in/paul-charles-6a49ba12b/"><img height="25px" src="/static/img/linkedin.svg" alt="LinkedIn"></a>
  <a target="_blank" href="https://www.malt.fr/profile/paulcharles/"><img height="25px" src="/static/img/malt.svg" alt="Malt"></a>
  <a target="_blank" href="https://github.com/paul-florentin-charles/"><img height="25px" src="/static/img/github.svg" alt="GitHub"></a>
  <a target="_blank" href="https://medium.com/@paul.florentin.charles/"><img height="25px" src="/static/img/medium.svg" alt="Medium"></a>
</div>

---

<div style="margin: auto; text-align: right;">
  © 2024 Paul CHARLES
</div>

</article>
</div>