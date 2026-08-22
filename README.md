<h1>Tekin Ertekin</h1>

<p><b>Software Engineer</b> — 12+ years building production systems. Currently working on low-precision numerics and machine-learning infrastructure in C.</p>

---

## Open-source contributions

Ten merged pull requests across four organisations. **Click a logo to open that organisation's list of my merged pull requests.**

<table>
  <tr>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Aroot-project&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/6450093?s=100" width="56" alt="ROOT"><br>
        <b>ROOT</b>
      </a><br>
      <sub>CERN &middot; 3 merged</sub>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Anasa&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/848102?s=100" width="56" alt="NASA"><br>
        <b>NASA</b>
      </a><br>
      <sub>F&prime; flight software &middot; 3 merged</sub>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Ascipy&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/288277?s=100" width="56" alt="SciPy"><br>
        <b>SciPy</b>
      </a><br>
      <sub>scipy &amp; xsf &middot; 3 merged</sub>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Aggml-org&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/134263123?s=100" width="56" alt="llama.cpp"><br>
        <b>llama.cpp</b>
      </a><br>
      <sub>ggml-org &middot; 1 merged</sub>
    </td>
  </tr>
</table>

Mostly numerical correctness and performance work: premature overflow in Bessel functions, a wrong-signed fill in CERN's image library, a dropped socket timeout in flight software, a data race under free-threading.

---

## mantissa

[**mantissa**](https://github.com/tekinertekin/mantissa) — a low-precision numerics core for neural networks, written in C.

It stores weights and activations in narrow formats (fp8, fp4, and a block-scaled variant) and runs dense and convolutional layers over them with hand-written NEON kernels. Every performance claim in the repository is backed by a paired randomised measurement against a same-binary control, and results that did not survive that test are documented as rejected rather than removed.

---

## Education

- **PhD** — thesis in progress, paper under review.
- **MSc** — [adaptive-voronoi-mapping](https://github.com/tekinertekin/adaptive-voronoi-mapping): adaptive Voronoi mapping for legible visualisation of very large graphs.

---

## Work

<a href="https://bumper.co"><img src="https://a.storyblok.com/f/321832/189x32/ca55d9d5c4/bumper-logo.png" height="26" alt="Bumper"></a>

Software Engineer.

Before that, national-scale public-sector systems in .NET — both still in production:

- **KYK**, Turkey's student loans and housing agency — worked on a team that built 9 databases and 11 applications from scratch. Around **15 million users**.
- **Turkish Employment Agency (İŞKUR)** — employment and public-benefit programme systems serving **8+ million users**.
