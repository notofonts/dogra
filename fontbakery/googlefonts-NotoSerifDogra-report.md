## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[10] NotoSerifDogra-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 260 font units wide, non-breaking space named (uni00A0) is 240 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/dogra.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifDogra/googlefonts/ttf/NotoSerifDogra-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/dogra.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑠊𑠹𑠨𑠭 𑠙𑠹𑠤𑠭 𑠑𑠹𑠓𑠭 𑠩𑠹𑠔𑠭 𑠧𑠹𑠤𑠭</span> (#9)</li>


<pre>Expected: matraI.alt.dogra=0+284|KaSsa.dogra=0+563|space=4+240|matraI.dogra=5+284|TaRa.dogra=5+546|space=9+240|matraI.dogra=10+284|JaNya.dogra=10+774|space=14+240|matraI.dogra=15+284|SaTta.dogra=15+601|space=19+240|matraI.dogra=20+284|ShaRa.dogra=20+822</pre>



<pre>Got     : matraI.alt.dogra=0+284|KaSsa.dogra=0+563|space=4+260|matraI.dogra=5+284|TaRa.dogra=5+546|space=9+260|matraI.dogra=10+284|JaNya.dogra=10+774|space=14+260|matraI.dogra=15+284|SaTta.dogra=15+601|space=19+260|matraI.dogra=20+284|ShaRa.dogra=20+822</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5766 2494" transform="matrix(1 0 0 -1 0 0)">
<path d="M172.0,-4.0L103.0,30.0L103.0,677.0Q103.0,754.0 148.0,795.0Q193.0,836.0 260.0,836.0Q313.0,836.0 348.5,813.0Q384.0,790.0 406.5,753.0Q429.0,716.0 441.0,673.0L405.0,658.0Q384.0,712.0 354.0,740.5Q324.0,769.0 280.0,769.0Q238.0,769.0 209.5,741.5Q181.0,714.0 181.0,658.0L181.0,-4.0L172.0,-4.0Z" transform="translate(0, 864)"/>
<path d="M504.0,-55.0Q486.0,-23.0 470.0,6.0Q454.0,35.0 436.0,61.0Q405.0,42.0 363.0,31.0Q321.0,20.0 268.0,20.0Q229.0,20.0 189.5,31.5Q150.0,43.0 117.5,63.0Q85.0,83.0 65.0,109.0Q45.0,135.0 45.0,163.0Q45.0,208.0 80.0,234.5Q115.0,261.0 179.0,261.0Q233.0,261.0 278.0,244.5Q323.0,228.0 358.0,203.5Q393.0,179.0 416.0,156.0Q422.0,167.0 424.5,179.5Q427.0,192.0 427.0,205.0Q427.0,240.0 398.0,263.5Q369.0,287.0 288.0,302.0L243.0,310.0Q158.0,326.0 110.0,369.0Q62.0,412.0 62.0,479.0Q62.0,525.0 87.5,560.5Q113.0,596.0 160.0,617.0Q207.0,638.0 271.0,638.0Q314.0,638.0 353.5,625.0Q393.0,612.0 424.0,590.5Q455.0,569.0 473.0,544.0Q491.0,519.0 491.0,494.0Q491.0,449.0 453.0,424.0Q415.0,399.0 353.0,399.0Q296.0,399.0 240.5,422.5Q185.0,446.0 145.0,484.0Q141.0,472.0 141.0,456.0Q141.0,416.0 166.0,394.5Q191.0,373.0 245.0,362.0L298.0,352.0Q411.0,331.0 459.0,285.5Q507.0,240.0 507.0,182.0Q507.0,131.0 472.0,91.0Q515.0,38.0 552.0,-27.0L504.0,-55.0ZM311.0,462.0Q358.0,462.0 384.5,476.0Q411.0,490.0 411.0,518.0Q411.0,542.0 387.0,558.0Q363.0,574.0 313.0,574.0Q267.0,574.0 228.5,560.0Q190.0,546.0 167.0,520.0Q193.0,494.0 229.5,478.0Q266.0,462.0 311.0,462.0ZM228.0,83.0Q286.0,83.0 325.0,93.5Q364.0,104.0 387.0,122.0Q351.0,154.0 309.5,174.5Q268.0,195.0 211.0,195.0Q170.0,195.0 147.5,179.5Q125.0,164.0 125.0,139.0Q125.0,83.0 228.0,83.0Z" transform="translate(284, 864)"/>
<path d="" transform="translate(847, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(1107, 864)"/>
<path d="M333.0,-145.0L194.0,25.0Q116.0,30.0 75.5,57.0Q35.0,84.0 35.0,122.0Q35.0,148.0 51.0,163.0Q67.0,178.0 95.0,178.0Q123.0,178.0 149.0,158.5Q175.0,139.0 210.0,94.0L212.0,94.0Q305.0,94.0 350.5,129.5Q396.0,165.0 396.0,222.0Q396.0,263.0 363.5,288.0Q331.0,313.0 268.0,313.0L141.0,313.0L118.0,380.0L158.0,380.0Q230.0,380.0 279.0,395.5Q328.0,411.0 356.0,449.5Q384.0,488.0 391.0,558.0L57.0,558.0L25.0,616.0L25.0,625.0L489.0,625.0L521.0,567.0L521.0,558.0L475.0,558.0Q467.0,473.0 438.5,422.0Q410.0,371.0 360.0,344.0Q388.0,332.0 414.5,310.0Q441.0,288.0 459.0,258.0Q477.0,228.0 477.0,191.0Q477.0,119.0 420.5,76.0Q364.0,33.0 266.0,25.0L386.0,-99.0L333.0,-145.0Z" transform="translate(1391, 864)"/>
<path d="" transform="translate(1937, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(2197, 864)"/>
<path d="M284.0,24.0Q247.0,24.0 208.0,41.5Q169.0,59.0 136.0,89.5Q103.0,120.0 83.0,160.5Q63.0,201.0 63.0,246.0Q63.0,328.0 119.5,368.5Q176.0,409.0 270.0,409.0L352.0,409.0L352.0,558.0L57.0,558.0L25.0,616.0L25.0,625.0L717.0,625.0L749.0,567.0L749.0,558.0L430.0,558.0L430.0,408.0L485.0,407.0Q533.0,406.0 575.0,388.0Q617.0,370.0 649.0,339.5Q681.0,309.0 699.5,271.0Q718.0,233.0 718.0,194.0Q718.0,115.0 671.5,69.5Q625.0,24.0 548.0,24.0Q506.0,24.0 471.0,41.0Q436.0,58.0 410.0,82.0Q393.0,54.0 361.5,39.0Q330.0,24.0 284.0,24.0ZM255.0,88.0Q304.0,88.0 328.0,116.5Q352.0,145.0 352.0,190.0L352.0,342.0L300.0,342.0Q220.0,342.0 181.5,305.5Q143.0,269.0 143.0,206.0Q143.0,148.0 176.0,118.0Q209.0,88.0 255.0,88.0ZM513.0,88.0Q569.0,88.0 603.0,123.0Q637.0,158.0 637.0,228.0Q637.0,281.0 607.5,311.0Q578.0,341.0 516.0,341.0L430.0,341.0L430.0,164.0Q430.0,154.0 429.0,144.5Q428.0,135.0 426.0,126.0Q444.0,108.0 466.0,98.0Q488.0,88.0 513.0,88.0Z" transform="translate(2481, 864)"/>
<path d="" transform="translate(3255, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(3515, 864)"/>
<path d="M437.0,-87.0Q391.0,-87.0 347.5,-65.0Q304.0,-43.0 276.0,-6.5Q248.0,30.0 248.0,71.0Q248.0,101.0 260.0,123.5Q272.0,146.0 295.5,168.5Q319.0,191.0 353.0,221.0L390.0,253.0Q428.0,286.0 443.0,312.0Q458.0,338.0 458.0,372.0Q458.0,402.0 442.0,422.0Q426.0,442.0 394.0,442.0Q351.0,442.0 316.0,412.0Q281.0,382.0 237.0,313.0L214.0,277.0Q210.0,222.0 192.0,188.5Q174.0,155.0 142.0,155.0Q117.0,155.0 98.0,170.5Q79.0,186.0 79.0,206.0Q79.0,220.0 91.0,240.0L150.0,332.0Q151.0,340.0 151.5,348.5Q152.0,357.0 152.0,366.0Q152.0,428.0 123.0,478.5Q94.0,529.0 42.0,559.0L9.0,616.0L9.0,625.0L544.0,625.0L576.0,567.0L576.0,558.0L126.0,558.0Q152.0,530.0 171.0,490.0Q190.0,450.0 200.0,407.0Q241.0,463.0 277.0,484.5Q313.0,506.0 358.0,506.0Q392.0,506.0 423.5,490.5Q455.0,475.0 480.5,450.0Q506.0,425.0 521.0,395.5Q536.0,366.0 536.0,337.0Q536.0,294.0 515.0,265.0Q494.0,236.0 447.0,194.0L416.0,166.0Q381.0,135.0 361.5,114.5Q342.0,94.0 334.0,78.0Q326.0,62.0 326.0,42.0Q326.0,-23.0 405.0,-23.0Q446.0,-23.0 477.0,-6.5Q508.0,10.0 538.0,41.0L586.0,-18.0Q563.0,-49.0 527.5,-68.0Q492.0,-87.0 437.0,-87.0Z" transform="translate(3799, 864)"/>
<path d="" transform="translate(4400, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(4660, 864)"/>
<path d="M359.0,-16.0L201.0,167.0Q182.0,161.0 160.0,161.0Q120.0,161.0 92.0,186.0Q64.0,211.0 64.0,242.0Q64.0,267.0 78.5,281.5Q93.0,296.0 117.0,296.0Q136.0,296.0 154.0,286.0Q172.0,276.0 197.0,252.0Q233.0,266.0 258.5,286.5Q284.0,307.0 300.0,332.0Q209.0,349.0 151.0,389.5Q93.0,430.0 93.0,504.0Q93.0,535.0 103.0,558.0L56.0,558.0L25.0,616.0L25.0,625.0L765.0,625.0L797.0,567.0L797.0,558.0L733.0,558.0L733.0,436.0Q733.0,376.0 720.0,339.0Q707.0,302.0 680.0,276.0Q653.0,250.0 612.0,223.0L764.0,33.0L716.0,-5.0L555.0,215.0Q536.0,241.0 526.0,259.5Q516.0,278.0 516.0,297.0Q516.0,316.0 528.5,327.5Q541.0,339.0 566.0,351.0L651.0,393.0Q653.0,404.0 654.0,418.0Q655.0,432.0 655.0,448.0L655.0,558.0L406.0,558.0Q414.0,516.0 414.0,469.0L414.0,458.0Q414.0,363.0 379.0,298.0Q344.0,233.0 252.0,188.0L405.0,27.0L359.0,-16.0ZM321.0,375.0Q334.0,413.0 334.0,464.0L334.0,475.0Q334.0,497.0 332.5,518.0Q331.0,539.0 327.0,558.0L190.0,558.0Q183.0,547.0 178.0,531.5Q173.0,516.0 173.0,499.0L173.0,489.0Q173.0,446.0 208.5,417.5Q244.0,389.0 321.0,375.0Z" transform="translate(4944, 864)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5686 2494" transform="matrix(1 0 0 -1 0 0)">
<path d="M172.0,-4.0L103.0,30.0L103.0,677.0Q103.0,754.0 148.0,795.0Q193.0,836.0 260.0,836.0Q313.0,836.0 348.5,813.0Q384.0,790.0 406.5,753.0Q429.0,716.0 441.0,673.0L405.0,658.0Q384.0,712.0 354.0,740.5Q324.0,769.0 280.0,769.0Q238.0,769.0 209.5,741.5Q181.0,714.0 181.0,658.0L181.0,-4.0L172.0,-4.0Z" transform="translate(0, 864)"/>
<path d="M504.0,-55.0Q486.0,-23.0 470.0,6.0Q454.0,35.0 436.0,61.0Q405.0,42.0 363.0,31.0Q321.0,20.0 268.0,20.0Q229.0,20.0 189.5,31.5Q150.0,43.0 117.5,63.0Q85.0,83.0 65.0,109.0Q45.0,135.0 45.0,163.0Q45.0,208.0 80.0,234.5Q115.0,261.0 179.0,261.0Q233.0,261.0 278.0,244.5Q323.0,228.0 358.0,203.5Q393.0,179.0 416.0,156.0Q422.0,167.0 424.5,179.5Q427.0,192.0 427.0,205.0Q427.0,240.0 398.0,263.5Q369.0,287.0 288.0,302.0L243.0,310.0Q158.0,326.0 110.0,369.0Q62.0,412.0 62.0,479.0Q62.0,525.0 87.5,560.5Q113.0,596.0 160.0,617.0Q207.0,638.0 271.0,638.0Q314.0,638.0 353.5,625.0Q393.0,612.0 424.0,590.5Q455.0,569.0 473.0,544.0Q491.0,519.0 491.0,494.0Q491.0,449.0 453.0,424.0Q415.0,399.0 353.0,399.0Q296.0,399.0 240.5,422.5Q185.0,446.0 145.0,484.0Q141.0,472.0 141.0,456.0Q141.0,416.0 166.0,394.5Q191.0,373.0 245.0,362.0L298.0,352.0Q411.0,331.0 459.0,285.5Q507.0,240.0 507.0,182.0Q507.0,131.0 472.0,91.0Q515.0,38.0 552.0,-27.0L504.0,-55.0ZM311.0,462.0Q358.0,462.0 384.5,476.0Q411.0,490.0 411.0,518.0Q411.0,542.0 387.0,558.0Q363.0,574.0 313.0,574.0Q267.0,574.0 228.5,560.0Q190.0,546.0 167.0,520.0Q193.0,494.0 229.5,478.0Q266.0,462.0 311.0,462.0ZM228.0,83.0Q286.0,83.0 325.0,93.5Q364.0,104.0 387.0,122.0Q351.0,154.0 309.5,174.5Q268.0,195.0 211.0,195.0Q170.0,195.0 147.5,179.5Q125.0,164.0 125.0,139.0Q125.0,83.0 228.0,83.0Z" transform="translate(284, 864)"/>
<path d="" transform="translate(847, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(1087, 864)"/>
<path d="M333.0,-145.0L194.0,25.0Q116.0,30.0 75.5,57.0Q35.0,84.0 35.0,122.0Q35.0,148.0 51.0,163.0Q67.0,178.0 95.0,178.0Q123.0,178.0 149.0,158.5Q175.0,139.0 210.0,94.0L212.0,94.0Q305.0,94.0 350.5,129.5Q396.0,165.0 396.0,222.0Q396.0,263.0 363.5,288.0Q331.0,313.0 268.0,313.0L141.0,313.0L118.0,380.0L158.0,380.0Q230.0,380.0 279.0,395.5Q328.0,411.0 356.0,449.5Q384.0,488.0 391.0,558.0L57.0,558.0L25.0,616.0L25.0,625.0L489.0,625.0L521.0,567.0L521.0,558.0L475.0,558.0Q467.0,473.0 438.5,422.0Q410.0,371.0 360.0,344.0Q388.0,332.0 414.5,310.0Q441.0,288.0 459.0,258.0Q477.0,228.0 477.0,191.0Q477.0,119.0 420.5,76.0Q364.0,33.0 266.0,25.0L386.0,-99.0L333.0,-145.0Z" transform="translate(1371, 864)"/>
<path d="" transform="translate(1917, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(2157, 864)"/>
<path d="M284.0,24.0Q247.0,24.0 208.0,41.5Q169.0,59.0 136.0,89.5Q103.0,120.0 83.0,160.5Q63.0,201.0 63.0,246.0Q63.0,328.0 119.5,368.5Q176.0,409.0 270.0,409.0L352.0,409.0L352.0,558.0L57.0,558.0L25.0,616.0L25.0,625.0L717.0,625.0L749.0,567.0L749.0,558.0L430.0,558.0L430.0,408.0L485.0,407.0Q533.0,406.0 575.0,388.0Q617.0,370.0 649.0,339.5Q681.0,309.0 699.5,271.0Q718.0,233.0 718.0,194.0Q718.0,115.0 671.5,69.5Q625.0,24.0 548.0,24.0Q506.0,24.0 471.0,41.0Q436.0,58.0 410.0,82.0Q393.0,54.0 361.5,39.0Q330.0,24.0 284.0,24.0ZM255.0,88.0Q304.0,88.0 328.0,116.5Q352.0,145.0 352.0,190.0L352.0,342.0L300.0,342.0Q220.0,342.0 181.5,305.5Q143.0,269.0 143.0,206.0Q143.0,148.0 176.0,118.0Q209.0,88.0 255.0,88.0ZM513.0,88.0Q569.0,88.0 603.0,123.0Q637.0,158.0 637.0,228.0Q637.0,281.0 607.5,311.0Q578.0,341.0 516.0,341.0L430.0,341.0L430.0,164.0Q430.0,154.0 429.0,144.5Q428.0,135.0 426.0,126.0Q444.0,108.0 466.0,98.0Q488.0,88.0 513.0,88.0Z" transform="translate(2441, 864)"/>
<path d="" transform="translate(3215, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(3455, 864)"/>
<path d="M437.0,-87.0Q391.0,-87.0 347.5,-65.0Q304.0,-43.0 276.0,-6.5Q248.0,30.0 248.0,71.0Q248.0,101.0 260.0,123.5Q272.0,146.0 295.5,168.5Q319.0,191.0 353.0,221.0L390.0,253.0Q428.0,286.0 443.0,312.0Q458.0,338.0 458.0,372.0Q458.0,402.0 442.0,422.0Q426.0,442.0 394.0,442.0Q351.0,442.0 316.0,412.0Q281.0,382.0 237.0,313.0L214.0,277.0Q210.0,222.0 192.0,188.5Q174.0,155.0 142.0,155.0Q117.0,155.0 98.0,170.5Q79.0,186.0 79.0,206.0Q79.0,220.0 91.0,240.0L150.0,332.0Q151.0,340.0 151.5,348.5Q152.0,357.0 152.0,366.0Q152.0,428.0 123.0,478.5Q94.0,529.0 42.0,559.0L9.0,616.0L9.0,625.0L544.0,625.0L576.0,567.0L576.0,558.0L126.0,558.0Q152.0,530.0 171.0,490.0Q190.0,450.0 200.0,407.0Q241.0,463.0 277.0,484.5Q313.0,506.0 358.0,506.0Q392.0,506.0 423.5,490.5Q455.0,475.0 480.5,450.0Q506.0,425.0 521.0,395.5Q536.0,366.0 536.0,337.0Q536.0,294.0 515.0,265.0Q494.0,236.0 447.0,194.0L416.0,166.0Q381.0,135.0 361.5,114.5Q342.0,94.0 334.0,78.0Q326.0,62.0 326.0,42.0Q326.0,-23.0 405.0,-23.0Q446.0,-23.0 477.0,-6.5Q508.0,10.0 538.0,41.0L586.0,-18.0Q563.0,-49.0 527.5,-68.0Q492.0,-87.0 437.0,-87.0Z" transform="translate(3739, 864)"/>
<path d="" transform="translate(4340, 864)"/>
<path d="M172.0,-4.0L103.0,30.0L103.0,558.0L47.0,558.0L15.0,616.0L15.0,625.0L103.0,625.0L103.0,670.0Q103.0,748.0 152.5,791.0Q202.0,834.0 278.0,834.0Q331.0,834.0 369.0,813.5Q407.0,793.0 432.5,758.0Q458.0,723.0 472.5,680.5Q487.0,638.0 493.0,594.0L443.0,585.0Q438.0,634.0 422.0,675.5Q406.0,717.0 376.0,742.5Q346.0,768.0 300.0,768.0Q251.0,768.0 216.0,739.5Q181.0,711.0 181.0,652.0L181.0,625.0L382.0,625.0L414.0,567.0L415.0,558.0L181.0,558.0L181.0,-4.0L172.0,-4.0Z" transform="translate(4580, 864)"/>
<path d="M359.0,-16.0L201.0,167.0Q182.0,161.0 160.0,161.0Q120.0,161.0 92.0,186.0Q64.0,211.0 64.0,242.0Q64.0,267.0 78.5,281.5Q93.0,296.0 117.0,296.0Q136.0,296.0 154.0,286.0Q172.0,276.0 197.0,252.0Q233.0,266.0 258.5,286.5Q284.0,307.0 300.0,332.0Q209.0,349.0 151.0,389.5Q93.0,430.0 93.0,504.0Q93.0,535.0 103.0,558.0L56.0,558.0L25.0,616.0L25.0,625.0L765.0,625.0L797.0,567.0L797.0,558.0L733.0,558.0L733.0,436.0Q733.0,376.0 720.0,339.0Q707.0,302.0 680.0,276.0Q653.0,250.0 612.0,223.0L764.0,33.0L716.0,-5.0L555.0,215.0Q536.0,241.0 526.0,259.5Q516.0,278.0 516.0,297.0Q516.0,316.0 528.5,327.5Q541.0,339.0 566.0,351.0L651.0,393.0Q653.0,404.0 654.0,418.0Q655.0,432.0 655.0,448.0L655.0,558.0L406.0,558.0Q414.0,516.0 414.0,469.0L414.0,458.0Q414.0,363.0 379.0,298.0Q344.0,233.0 252.0,188.0L405.0,27.0L359.0,-16.0ZM321.0,375.0Q334.0,413.0 334.0,464.0L334.0,475.0Q334.0,497.0 332.5,518.0Q331.0,539.0 327.0,558.0L190.0,558.0Q183.0,547.0 178.0,531.5Q173.0,516.0 173.0,499.0L173.0,489.0Q173.0,446.0 208.5,417.5Q244.0,389.0 321.0,375.0Z" transform="translate(4864, 864)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Avagraha.dogra

	- Eight.dogra

	- Five.dogra

	- Four.dogra

	- Nine.dogra

	- One.dogra

	- Seven.dogra

	- Six.dogra

	- Three.dogra

	- Two.dogra 

	- 6 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=395.5,Y=624.0 (should be at cap-height 625?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* P (U+0050): X=422.0,Y=625.5 (should be at cap-height 625?)

	* V (U+0056): X=192.0,Y=624.0 (should be at cap-height 625?)

	* V (U+0056): X=520.0,Y=623.0 (should be at cap-height 625?)

	* W (U+0057): X=201.0,Y=624.0 (should be at cap-height 625?) 

	* 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Ba.dogra (U+11820): L<<326.0,385.0>--<242.0,353.0>> -> L<<242.0,353.0>--<239.0,352.0>> 

	* Rra.dogra (U+1182B): L<<311.0,70.0>--<293.0,67.0>> -> L<<293.0,67.0>--<235.0,60.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 6 | 117 | 7 | 112 | 0 |
| 0% | 2% | 2% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**