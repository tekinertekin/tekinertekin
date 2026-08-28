<h1>Tekin Ertekin</h1>

<p><b>Software Engineer</b> — 12+ years building production systems. Currently working on low-precision numerics and machine-learning infrastructure in C.</p>

<h3>Open-source contributions</h3>

Twelve merged pull requests across four organisations. **Click a logo to open that organisation's list of my merged pull requests.**

<table>
  <tr>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Anasa&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/848102?s=100" width="56" alt="NASA"><br>
        <b>NASA</b>
      </a><br>
      <sub>F&prime; flight software &middot; 3 merged</sub>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/search?q=is%3Apr+author%3Atekinertekin+is%3Amerged+org%3Aroot-project&type=pullrequests">
        <img src="https://avatars.githubusercontent.com/u/6450093?s=100" width="56" alt="ROOT"><br>
        <b>ROOT</b>
      </a><br>
      <sub>CERN &middot; 4 merged</sub>
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
      <sub>ggml-org &middot; 2 merged</sub>
    </td>
  </tr>
</table>

Mostly numerical correctness and performance work: premature overflow in Bessel functions, a flood fill that hung or leaked past its outline depending on the brush alpha, a socket timeout that was configured but never applied, generation settings an inference server accepted but never reported back.

<h3>mantissa</h3>

[**mantissa**](https://github.com/tekinertekin/mantissa) — a low-precision numerics core for neural networks, written in C.

It stores weights and activations in narrow formats (fp8, fp4, and a block-scaled variant) and runs dense and convolutional layers over them with hand-written NEON kernels. Every performance claim in the repository is backed by a paired randomised measurement against a same-binary control, and results that did not survive that test are documented as rejected rather than removed.

<h3>Education</h3>

<table>
  <tr>
    <td width="120" align="center">
      <a href="https://www.cs.hacettepe.edu.tr/"><img src="assets/hacettepe.png" width="44" alt="Hacettepe University"></a>
    </td>
    <td><b>PhD, Computer Engineering</b> — <a href="https://www.cs.hacettepe.edu.tr/">Hacettepe University</a>, 2021 – present<br><sub>Thesis in progress. First paper published in <i>Applied Sciences</i>, 2026 — <a href="https://doi.org/10.3390/app16178542">Concept Tree Learner (CTL)</a>.</sub></td>
  </tr>
  <tr>
    <td width="120" align="center">
      <a href="https://bil-grafik.hacettepe.edu.tr/"><img src="assets/hacettepe.png" width="44" alt="Hacettepe University"></a>
    </td>
    <td><b>MSc, Game Technologies and Computer Animation</b> — <a href="https://bil-grafik.hacettepe.edu.tr/">Hacettepe University</a>, 2021<br><sub><a href="https://github.com/tekinertekin/adaptive-voronoi-mapping">adaptive-voronoi-mapping</a>: adaptive Voronoi mapping for legible visualisation of very large labelled spatial point data.</sub></td>
  </tr>
  <tr>
    <td width="120" align="center">
      <a href="https://ceng.metu.edu.tr/"><img src="assets/metu-emblem.png" width="44" alt="METU"></a>
    </td>
    <td><b>BSc, Computer Engineering</b> — <a href="https://ceng.metu.edu.tr/">Middle East Technical University</a>, 2014</td>
  </tr>
</table>

<h3>Publications</h3>

- M. T. Ertekin and B. Genç, **"Concept Tree Learner (CTL): An Incremental and Interpretable Symbolic Framework for Binary String Rule Induction"**, *Applied Sciences*, vol. 16, no. 17, art. 8542, 2026. Open access, [doi:10.3390/app16178542](https://doi.org/10.3390/app16178542)
- M. T. Ertekin and B. Genç, **"User Oriented Visualization of Very Large Spatial Data with Adaptive Voronoi Mapping (AVM)"**, in *Engineering Cyber-Physical Systems and Critical Infrastructures*, Springer, 2023, pp. 515–536. [doi:10.1007/978-3-031-31956-3_45](https://doi.org/10.1007/978-3-031-31956-3_45)
- M. T. Ertekin, **"Çok Büyük Konumsal Verinin Kullanıcı Odaklı Görselleştirilmesi"**, MSc thesis, Institute of Informatics, Hacettepe University, 2020. In Turkish, [full text](https://openaccess.hacettepe.edu.tr/items/022b3198-c0ee-471c-ad53-7346c9ffef74)

<h3>Work</h3>

<a href="https://bumper.co"><img src="assets/bumper.png" height="24" alt="Bumper"></a>

Software Engineer.

Before that, national-scale public-sector systems in .NET — both still in production:

- **KYK**, Turkey's student loans and housing agency — worked on a team that built 9 databases and 11 applications from scratch. Around **15 million users**.
- **Turkish Employment Agency (İŞKUR)** — employment and public-benefit programme systems serving **8+ million users**.

<h3>Other work</h3>

- **Flight-controller firmware** — modified the C sources running on a Pixhawk Cube autopilot.
