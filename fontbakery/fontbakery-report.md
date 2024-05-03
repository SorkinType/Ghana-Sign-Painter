## FontBakery report

fontbakery version: 0.12.0



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] GaMaamli-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[13] GaMaamli-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 571 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 551:
less</p>
<p>Width = 607:
equal, notequal</p>
<p>Width = 540:
greater</p>
<p>Width = 598:
logicalnot</p>
<p>Width = 573:
plusminus</p>
<p>Width = 522:
multiply</p>
<p>Width = 641:
divide</p>
<p>Width = 570:
approxequal</p>
<p>Width = 593:
lessequal</p>
<p>Width = 568:
greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Glottalstopreversed

- periodcentered.loclCAT

- periodcentered.loclCAT.case
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* product (U+220F): L&lt;&lt;289.0,703.0&gt;--&lt;290.0,697.0&gt;&gt;/B&lt;&lt;290.0,697.0&gt;-&lt;290.0,706.0&gt;-&lt;289.0,703.0&gt;&gt; = 9.462322208025613

* product (U+220F): L&lt;&lt;506.0,703.0&gt;--&lt;507.0,697.0&gt;&gt;/B&lt;&lt;507.0,697.0&gt;-&lt;507.0,706.0&gt;-&lt;506.0,703.0&gt;&gt; = 9.462322208025613

* uni0394 (U+0394): L&lt;&lt;393.0,1.0&gt;--&lt;7.0,0.0&gt;&gt;/L&lt;&lt;7.0,0.0&gt;--&lt;7.0,0.0&gt;&gt; = 0.1484343298739336

* uni2206 (U+2206): L&lt;&lt;393.0,1.0&gt;--&lt;7.0,0.0&gt;&gt;/L&lt;&lt;7.0,0.0&gt;--&lt;7.0,0.0&gt;&gt; = 0.1484343298739336
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* AE (U+00C6): L&lt;&lt;396.0,438.0&gt;--&lt;669.0,439.0&gt;&gt;

* AE (U+00C6): L&lt;&lt;609.0,269.0&gt;--&lt;377.0,268.0&gt;&gt;

* AEacute (U+01FC): L&lt;&lt;396.0,438.0&gt;--&lt;669.0,439.0&gt;&gt;

* AEacute (U+01FC): L&lt;&lt;609.0,269.0&gt;--&lt;377.0,268.0&gt;&gt;

* Amacron (U+0100): L&lt;&lt;229.0,881.0&gt;--&lt;460.0,879.0&gt;&gt;

* Amacron (U+0100): L&lt;&lt;418.0,757.0&gt;--&lt;187.0,759.0&gt;&gt;

* E (U+0045): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* E (U+0045): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Ecaron (U+011A): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Ecaron (U+011A): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;241.0,879.0&gt;--&lt;472.0,877.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;430.0,755.0&gt;--&lt;199.0,757.0&gt;&gt;

* Eogonek (U+0118): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* Eogonek (U+0118): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* H (U+0048): L&lt;&lt;224.0,438.0&gt;--&lt;357.0,439.0&gt;&gt;

* H (U+0048): L&lt;&lt;344.0,269.0&gt;--&lt;211.0,268.0&gt;&gt;

* Hbar (U+0126): L&lt;&lt;254.0,438.0&gt;--&lt;387.0,439.0&gt;&gt;

* Hbar (U+0126): L&lt;&lt;374.0,269.0&gt;--&lt;241.0,268.0&gt;&gt;

* Hbar (U+0126): L&lt;&lt;392.0,511.0&gt;--&lt;259.0,510.0&gt;&gt;

* Hcircumflex (U+0124): L&lt;&lt;224.0,438.0&gt;--&lt;357.0,439.0&gt;&gt;

* Hcircumflex (U+0124): L&lt;&lt;344.0,269.0&gt;--&lt;211.0,268.0&gt;&gt;

* Imacron (U+012A): L&lt;&lt;287.0,756.0&gt;--&lt;56.0,758.0&gt;&gt;

* Imacron (U+012A): L&lt;&lt;98.0,880.0&gt;--&lt;329.0,878.0&gt;&gt;

* OE (U+0152): L&lt;&lt;443.0,438.0&gt;--&lt;692.0,439.0&gt;&gt;

* OE (U+0152): L&lt;&lt;632.0,269.0&gt;--&lt;431.0,268.0&gt;&gt;

* Omacron (U+014C): L&lt;&lt;227.0,880.0&gt;--&lt;458.0,878.0&gt;&gt;

* Omacron (U+014C): L&lt;&lt;416.0,756.0&gt;--&lt;185.0,758.0&gt;&gt;

* Umacron (U+016A): L&lt;&lt;240.0,879.0&gt;--&lt;471.0,877.0&gt;&gt;

* Umacron (U+016A): L&lt;&lt;429.0,755.0&gt;--&lt;198.0,757.0&gt;&gt;

* ae (U+00E6): L&lt;&lt;413.0,430.0&gt;--&lt;614.0,431.0&gt;&gt;

* ae (U+00E6): L&lt;&lt;554.0,261.0&gt;--&lt;399.0,260.0&gt;&gt;

* aeacute (U+01FD): L&lt;&lt;413.0,430.0&gt;--&lt;614.0,431.0&gt;&gt;

* aeacute (U+01FD): L&lt;&lt;554.0,261.0&gt;--&lt;399.0,260.0&gt;&gt;

* amacron (U+0101): L&lt;&lt;210.0,880.0&gt;--&lt;441.0,878.0&gt;&gt;

* amacron (U+0101): L&lt;&lt;399.0,756.0&gt;--&lt;168.0,758.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;509.0,437.0&gt;--&lt;648.0,438.0&gt;&gt;

* bracketleft (U+005B): L&lt;&lt;166.0,714.0&gt;--&lt;410.0,715.0&gt;&gt;

* bracketleft (U+005B): L&lt;&lt;194.0,156.0&gt;--&lt;367.0,157.0&gt;&gt;

* bracketleft (U+005B): L&lt;&lt;307.0,-13.0&gt;--&lt;75.0,-14.0&gt;&gt;

* bracketleft (U+005B): L&lt;&lt;350.0,545.0&gt;--&lt;222.0,544.0&gt;&gt;

* bracketright (U+005D): L&lt;&lt;114.0,156.0&gt;--&lt;242.0,157.0&gt;&gt;

* bracketright (U+005D): L&lt;&lt;157.0,714.0&gt;--&lt;389.0,715.0&gt;&gt;

* bracketright (U+005D): L&lt;&lt;270.0,545.0&gt;--&lt;97.0,544.0&gt;&gt;

* bracketright (U+005D): L&lt;&lt;298.0,-13.0&gt;--&lt;54.0,-14.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;136.0,10.0&gt;--&lt;134.0,395.0&gt;&gt;

* daggerdbl (U+2021): L&lt;&lt;161.0,10.0&gt;--&lt;160.0,146.0&gt;&gt;

* divide (U+00F7): L&lt;&lt;104.0,367.0&gt;--&lt;587.0,368.0&gt;&gt;

* divide (U+00F7): L&lt;&lt;527.0,198.0&gt;--&lt;44.0,197.0&gt;&gt;

* e (U+0065): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* e (U+0065): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* eacute (U+00E9): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* eacute (U+00E9): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* ecaron (U+011B): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* ecaron (U+011B): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* ecircumflex (U+00EA): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* ecircumflex (U+00EA): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* edieresis (U+00EB): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* edieresis (U+00EB): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* edotaccent (U+0117): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* edotaccent (U+0117): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* egrave (U+00E8): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* egrave (U+00E8): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* emacron (U+0113): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* emacron (U+0113): L&lt;&lt;222.0,881.0&gt;--&lt;453.0,879.0&gt;&gt;

* emacron (U+0113): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* emacron (U+0113): L&lt;&lt;411.0,757.0&gt;--&lt;180.0,759.0&gt;&gt;

* emdash (U+2014): L&lt;&lt;731.0,212.0&gt;--&lt;14.0,214.0&gt;&gt;

* emdash (U+2014): L&lt;&lt;74.0,384.0&gt;--&lt;791.0,382.0&gt;&gt;

* endash (U+2013): L&lt;&lt;550.0,212.0&gt;--&lt;14.0,214.0&gt;&gt;

* endash (U+2013): L&lt;&lt;74.0,384.0&gt;--&lt;610.0,382.0&gt;&gt;

* eogonek (U+0119): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* eogonek (U+0119): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* equal (U+003D): L&lt;&lt;115.0,482.0&gt;--&lt;548.0,483.0&gt;&gt;

* equal (U+003D): L&lt;&lt;452.0,20.0&gt;--&lt;19.0,19.0&gt;&gt;

* equal (U+003D): L&lt;&lt;488.0,313.0&gt;--&lt;55.0,312.0&gt;&gt;

* equal (U+003D): L&lt;&lt;79.0,189.0&gt;--&lt;512.0,190.0&gt;&gt;

* f (U+0066): L&lt;&lt;140.0,402.0&gt;--&lt;372.0,400.0&gt;&gt;

* f (U+0066): L&lt;&lt;324.0,226.0&gt;--&lt;126.0,227.0&gt;&gt;

* fi (U+FB01): L&lt;&lt;140.0,402.0&gt;--&lt;372.0,400.0&gt;&gt;

* fi (U+FB01): L&lt;&lt;324.0,226.0&gt;--&lt;126.0,227.0&gt;&gt;

* fl (U+FB02): L&lt;&lt;134.0,402.0&gt;--&lt;368.0,400.0&gt;&gt;

* fl (U+FB02): L&lt;&lt;320.0,226.0&gt;--&lt;123.0,227.0&gt;&gt;

* four (U+0034): L&lt;&lt;243.0,213.0&gt;--&lt;1.0,212.0&gt;&gt;

* greaterequal (U+2265): L&lt;&lt;408.0,-19.0&gt;--&lt;35.0,-20.0&gt;&gt;

* greaterequal (U+2265): L&lt;&lt;89.0,134.0&gt;--&lt;462.0,135.0&gt;&gt;

* h (U+0068): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* h (U+0068): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* hbar (U+0127): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* hbar (U+0127): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* hcircumflex (U+0125): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* hcircumflex (U+0125): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* hyphen (U+002D): L&lt;&lt;250.0,212.0&gt;--&lt;19.0,214.0&gt;&gt;

* hyphen (U+002D): L&lt;&lt;79.0,384.0&gt;--&lt;310.0,382.0&gt;&gt;

* imacron (U+012B): L&lt;&lt;287.0,757.0&gt;--&lt;56.0,759.0&gt;&gt;

* imacron (U+012B): L&lt;&lt;98.0,881.0&gt;--&lt;329.0,879.0&gt;&gt;

* lessequal (U+2264): L&lt;&lt;398.0,-34.0&gt;--&lt;25.0,-35.0&gt;&gt;

* lessequal (U+2264): L&lt;&lt;79.0,119.0&gt;--&lt;452.0,120.0&gt;&gt;

* lira (U+20A4): L&lt;&lt;163.0,180.0&gt;--&lt;423.0,182.0&gt;&gt;

* lira (U+20A4): L&lt;&lt;303.0,-7.0&gt;--&lt;37.0,-5.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;114.0,423.0&gt;--&lt;544.0,424.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;403.0,254.0&gt;--&lt;54.0,253.0&gt;&gt;

* macron (U+00AF): L&lt;&lt;237.0,546.0&gt;--&lt;6.0,548.0&gt;&gt;

* macron (U+00AF): L&lt;&lt;48.0,670.0&gt;--&lt;279.0,668.0&gt;&gt;

* minus (U+2212): L&lt;&lt;452.0,184.0&gt;--&lt;19.0,183.0&gt;&gt;

* minus (U+2212): L&lt;&lt;79.0,353.0&gt;--&lt;512.0,354.0&gt;&gt;

* notequal (U+2260): L&lt;&lt;111.0,495.0&gt;--&lt;376.0,496.0&gt;&gt;

* notequal (U+2260): L&lt;&lt;271.0,326.0&gt;--&lt;51.0,325.0&gt;&gt;

* notequal (U+2260): L&lt;&lt;287.0,202.0&gt;--&lt;508.0,203.0&gt;&gt;

* notequal (U+2260): L&lt;&lt;448.0,33.0&gt;--&lt;185.0,32.0&gt;&gt;

* oe (U+0153): L&lt;&lt;482.0,438.0&gt;--&lt;715.0,439.0&gt;&gt;

* oe (U+0153): L&lt;&lt;655.0,269.0&gt;--&lt;450.0,268.0&gt;&gt;

* omacron (U+014D): L&lt;&lt;238.0,882.0&gt;--&lt;469.0,880.0&gt;&gt;

* omacron (U+014D): L&lt;&lt;427.0,758.0&gt;--&lt;196.0,760.0&gt;&gt;

* plusminus (U+00B1): L&lt;&lt;398.0,-34.0&gt;--&lt;25.0,-35.0&gt;&gt;

* plusminus (U+00B1): L&lt;&lt;79.0,119.0&gt;--&lt;452.0,120.0&gt;&gt;

* product (U+220F): L&lt;&lt;94.0,717.0&gt;--&lt;621.0,718.0&gt;&gt;

* sterling (U+00A3): L&lt;&lt;156.0,180.0&gt;--&lt;416.0,182.0&gt;&gt;

* sterling (U+00A3): L&lt;&lt;296.0,-7.0&gt;--&lt;30.0,-5.0&gt;&gt;

* summation (U+2211): L&lt;&lt;172.0,162.0&gt;--&lt;415.0,161.0&gt;&gt;

* summation (U+2211): L&lt;&lt;232.0,717.0&gt;--&lt;475.0,719.0&gt;&gt;

* summation (U+2211): L&lt;&lt;355.0,-9.0&gt;--&lt;32.0,-7.0&gt;&gt;

* umacron (U+016B): L&lt;&lt;198.0,883.0&gt;--&lt;429.0,881.0&gt;&gt;

* umacron (U+016B): L&lt;&lt;387.0,759.0&gt;--&lt;156.0,761.0&gt;&gt;

* underscore (U+005F): L&lt;&lt;550.0,-193.0&gt;--&lt;14.0,-191.0&gt;&gt;

* underscore (U+005F): L&lt;&lt;74.0,-21.0&gt;--&lt;610.0,-23.0&gt;&gt;

* uni018E (U+018E): L&lt;&lt;148.0,404.0&gt;--&lt;347.0,405.0&gt;&gt;

* uni018E (U+018E): L&lt;&lt;323.0,235.0&gt;--&lt;88.0,234.0&gt;&gt;

* uni01DE (U+01DE): L&lt;&lt;239.0,1081.0&gt;--&lt;470.0,1079.0&gt;&gt;

* uni01DE (U+01DE): L&lt;&lt;428.0,957.0&gt;--&lt;197.0,959.0&gt;&gt;

* uni01DF (U+01DF): L&lt;&lt;220.0,1080.0&gt;--&lt;451.0,1078.0&gt;&gt;

* uni01DF (U+01DF): L&lt;&lt;409.0,956.0&gt;--&lt;178.0,958.0&gt;&gt;

* uni01E2 (U+01E2): L&lt;&lt;396.0,438.0&gt;--&lt;669.0,439.0&gt;&gt;

* uni01E2 (U+01E2): L&lt;&lt;425.0,910.0&gt;--&lt;656.0,908.0&gt;&gt;

* uni01E2 (U+01E2): L&lt;&lt;609.0,269.0&gt;--&lt;377.0,268.0&gt;&gt;

* uni01E2 (U+01E2): L&lt;&lt;614.0,786.0&gt;--&lt;383.0,788.0&gt;&gt;

* uni01E3 (U+01E3): L&lt;&lt;388.0,905.0&gt;--&lt;619.0,903.0&gt;&gt;

* uni01E3 (U+01E3): L&lt;&lt;413.0,430.0&gt;--&lt;614.0,431.0&gt;&gt;

* uni01E3 (U+01E3): L&lt;&lt;554.0,261.0&gt;--&lt;399.0,260.0&gt;&gt;

* uni01E3 (U+01E3): L&lt;&lt;577.0,781.0&gt;--&lt;346.0,783.0&gt;&gt;

* uni0228 (U+0228): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni0228 (U+0228): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni0229 (U+0229): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni0229 (U+0229): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni022A (U+022A): L&lt;&lt;237.0,1080.0&gt;--&lt;468.0,1078.0&gt;&gt;

* uni022A (U+022A): L&lt;&lt;426.0,956.0&gt;--&lt;195.0,958.0&gt;&gt;

* uni022B (U+022B): L&lt;&lt;245.0,1082.0&gt;--&lt;476.0,1080.0&gt;&gt;

* uni022B (U+022B): L&lt;&lt;434.0,958.0&gt;--&lt;203.0,960.0&gt;&gt;

* uni0232 (U+0232): L&lt;&lt;247.0,880.0&gt;--&lt;478.0,878.0&gt;&gt;

* uni0232 (U+0232): L&lt;&lt;436.0,756.0&gt;--&lt;205.0,758.0&gt;&gt;

* uni0233 (U+0233): L&lt;&lt;249.0,879.0&gt;--&lt;480.0,877.0&gt;&gt;

* uni0233 (U+0233): L&lt;&lt;438.0,755.0&gt;--&lt;207.0,757.0&gt;&gt;

* uni0304 (U+0304): L&lt;&lt;237.0,546.0&gt;--&lt;6.0,548.0&gt;&gt;

* uni0304 (U+0304): L&lt;&lt;48.0,670.0&gt;--&lt;279.0,668.0&gt;&gt;

* uni0305 (U+0305): L&lt;&lt;48.0,661.0&gt;--&lt;574.0,659.0&gt;&gt;

* uni0305 (U+0305): L&lt;&lt;532.0,537.0&gt;--&lt;6.0,539.0&gt;&gt;

* uni031A (U+031A): L&lt;&lt;177.0,575.0&gt;--&lt;15.0,574.0&gt;&gt;

* uni031A (U+031A): L&lt;&lt;57.0,712.0&gt;--&lt;284.0,713.0&gt;&gt;

* uni0331 (U+0331): L&lt;&lt;287.0,-211.0&gt;--&lt;56.0,-209.0&gt;&gt;

* uni0331 (U+0331): L&lt;&lt;98.0,-87.0&gt;--&lt;329.0,-89.0&gt;&gt;

* uni0332 (U+0332): L&lt;&lt;-86.0,-95.0&gt;--&lt;440.0,-97.0&gt;&gt;

* uni0332 (U+0332): L&lt;&lt;398.0,-219.0&gt;--&lt;-128.0,-217.0&gt;&gt;

* uni0394 (U+0394): L&lt;&lt;139.0,170.0&gt;--&lt;321.0,171.0&gt;&gt;

* uni0394 (U+0394): L&lt;&lt;393.0,1.0&gt;--&lt;7.0,0.0&gt;&gt;

* uni1E0E (U+1E0E): L&lt;&lt;165.0,879.0&gt;--&lt;396.0,877.0&gt;&gt;

* uni1E0E (U+1E0E): L&lt;&lt;354.0,755.0&gt;--&lt;123.0,757.0&gt;&gt;

* uni1E14 (U+1E14): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1E14 (U+1E14): L&lt;&lt;241.0,879.0&gt;--&lt;472.0,877.0&gt;&gt;

* uni1E14 (U+1E14): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1E14 (U+1E14): L&lt;&lt;430.0,755.0&gt;--&lt;199.0,757.0&gt;&gt;

* uni1E15 (U+1E15): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1E15 (U+1E15): L&lt;&lt;222.0,881.0&gt;--&lt;453.0,879.0&gt;&gt;

* uni1E15 (U+1E15): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1E15 (U+1E15): L&lt;&lt;411.0,757.0&gt;--&lt;180.0,759.0&gt;&gt;

* uni1E16 (U+1E16): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1E16 (U+1E16): L&lt;&lt;241.0,879.0&gt;--&lt;472.0,877.0&gt;&gt;

* uni1E16 (U+1E16): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1E16 (U+1E16): L&lt;&lt;430.0,755.0&gt;--&lt;199.0,757.0&gt;&gt;

* uni1E17 (U+1E17): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1E17 (U+1E17): L&lt;&lt;222.0,881.0&gt;--&lt;453.0,879.0&gt;&gt;

* uni1E17 (U+1E17): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1E17 (U+1E17): L&lt;&lt;411.0,757.0&gt;--&lt;180.0,759.0&gt;&gt;

* uni1E20 (U+1E20): L&lt;&lt;264.0,880.0&gt;--&lt;495.0,878.0&gt;&gt;

* uni1E20 (U+1E20): L&lt;&lt;453.0,756.0&gt;--&lt;222.0,758.0&gt;&gt;

* uni1E21 (U+1E21): L&lt;&lt;259.0,880.0&gt;--&lt;490.0,878.0&gt;&gt;

* uni1E21 (U+1E21): L&lt;&lt;448.0,756.0&gt;--&lt;217.0,758.0&gt;&gt;

* uni1E22 (U+1E22): L&lt;&lt;224.0,438.0&gt;--&lt;357.0,439.0&gt;&gt;

* uni1E22 (U+1E22): L&lt;&lt;344.0,269.0&gt;--&lt;211.0,268.0&gt;&gt;

* uni1E23 (U+1E23): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* uni1E23 (U+1E23): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* uni1E24 (U+1E24): L&lt;&lt;224.0,438.0&gt;--&lt;357.0,439.0&gt;&gt;

* uni1E24 (U+1E24): L&lt;&lt;344.0,269.0&gt;--&lt;211.0,268.0&gt;&gt;

* uni1E25 (U+1E25): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* uni1E25 (U+1E25): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* uni1E34 (U+1E34): L&lt;&lt;216.0,879.0&gt;--&lt;447.0,877.0&gt;&gt;

* uni1E34 (U+1E34): L&lt;&lt;405.0,755.0&gt;--&lt;174.0,757.0&gt;&gt;

* uni1E35 (U+1E35): L&lt;&lt;203.0,881.0&gt;--&lt;434.0,879.0&gt;&gt;

* uni1E35 (U+1E35): L&lt;&lt;392.0,757.0&gt;--&lt;161.0,759.0&gt;&gt;

* uni1E48 (U+1E48): L&lt;&lt;253.0,879.0&gt;--&lt;484.0,877.0&gt;&gt;

* uni1E48 (U+1E48): L&lt;&lt;442.0,755.0&gt;--&lt;211.0,757.0&gt;&gt;

* uni1E49 (U+1E49): L&lt;&lt;237.0,880.0&gt;--&lt;468.0,878.0&gt;&gt;

* uni1E49 (U+1E49): L&lt;&lt;426.0,756.0&gt;--&lt;195.0,758.0&gt;&gt;

* uni1E50 (U+1E50): L&lt;&lt;227.0,880.0&gt;--&lt;458.0,878.0&gt;&gt;

* uni1E50 (U+1E50): L&lt;&lt;416.0,756.0&gt;--&lt;185.0,758.0&gt;&gt;

* uni1E51 (U+1E51): L&lt;&lt;235.0,882.0&gt;--&lt;466.0,880.0&gt;&gt;

* uni1E51 (U+1E51): L&lt;&lt;424.0,758.0&gt;--&lt;193.0,760.0&gt;&gt;

* uni1E52 (U+1E52): L&lt;&lt;227.0,880.0&gt;--&lt;458.0,878.0&gt;&gt;

* uni1E52 (U+1E52): L&lt;&lt;416.0,756.0&gt;--&lt;185.0,758.0&gt;&gt;

* uni1E53 (U+1E53): L&lt;&lt;235.0,882.0&gt;--&lt;466.0,880.0&gt;&gt;

* uni1E53 (U+1E53): L&lt;&lt;424.0,758.0&gt;--&lt;193.0,760.0&gt;&gt;

* uni1E6E (U+1E6E): L&lt;&lt;182.0,883.0&gt;--&lt;413.0,881.0&gt;&gt;

* uni1E6E (U+1E6E): L&lt;&lt;371.0,759.0&gt;--&lt;140.0,761.0&gt;&gt;

* uni1E6F (U+1E6F): L&lt;&lt;167.0,880.0&gt;--&lt;398.0,878.0&gt;&gt;

* uni1E6F (U+1E6F): L&lt;&lt;356.0,756.0&gt;--&lt;125.0,758.0&gt;&gt;

* uni1E94 (U+1E94): L&lt;&lt;211.0,886.0&gt;--&lt;442.0,884.0&gt;&gt;

* uni1E94 (U+1E94): L&lt;&lt;400.0,762.0&gt;--&lt;169.0,764.0&gt;&gt;

* uni1E95 (U+1E95): L&lt;&lt;198.0,882.0&gt;--&lt;429.0,880.0&gt;&gt;

* uni1E95 (U+1E95): L&lt;&lt;387.0,758.0&gt;--&lt;156.0,760.0&gt;&gt;

* uni1E96 (U+1E96): L&lt;&lt;227.0,437.0&gt;--&lt;362.0,438.0&gt;&gt;

* uni1E96 (U+1E96): L&lt;&lt;274.0,877.0&gt;--&lt;505.0,875.0&gt;&gt;

* uni1E96 (U+1E96): L&lt;&lt;349.0,268.0&gt;--&lt;215.0,267.0&gt;&gt;

* uni1E96 (U+1E96): L&lt;&lt;463.0,753.0&gt;--&lt;232.0,755.0&gt;&gt;

* uni1E9E (U+1E9E): L&lt;&lt;318.0,542.0&gt;--&lt;182.0,543.0&gt;&gt;

* uni1EB8 (U+1EB8): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EB8 (U+1EB8): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EB9 (U+1EB9): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EB9 (U+1EB9): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EBA (U+1EBA): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EBA (U+1EBA): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EBB (U+1EBB): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EBB (U+1EBB): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EBC (U+1EBC): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EBC (U+1EBC): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EBD (U+1EBD): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EBD (U+1EBD): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EBE (U+1EBE): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EBE (U+1EBE): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EBF (U+1EBF): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EBF (U+1EBF): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EC0 (U+1EC0): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EC0 (U+1EC0): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EC1 (U+1EC1): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EC1 (U+1EC1): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EC2 (U+1EC2): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EC2 (U+1EC2): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EC3 (U+1EC3): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EC3 (U+1EC3): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EC4 (U+1EC4): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EC4 (U+1EC4): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EC5 (U+1EC5): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EC5 (U+1EC5): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni1EC6 (U+1EC6): L&lt;&lt;179.0,438.0&gt;--&lt;429.0,439.0&gt;&gt;

* uni1EC6 (U+1EC6): L&lt;&lt;369.0,269.0&gt;--&lt;168.0,268.0&gt;&gt;

* uni1EC7 (U+1EC7): L&lt;&lt;170.0,438.0&gt;--&lt;402.0,439.0&gt;&gt;

* uni1EC7 (U+1EC7): L&lt;&lt;342.0,269.0&gt;--&lt;137.0,268.0&gt;&gt;

* uni2116 (U+2116): L&lt;&lt;611.0,234.0&gt;--&lt;842.0,232.0&gt;&gt;

* uni2116 (U+2116): L&lt;&lt;782.0,72.0&gt;--&lt;551.0,74.0&gt;&gt;

* uni2206 (U+2206): L&lt;&lt;139.0,170.0&gt;--&lt;321.0,171.0&gt;&gt;

* uni2206 (U+2206): L&lt;&lt;393.0,1.0&gt;--&lt;7.0,0.0&gt;&gt;

* uniFF06 (U+FF06): L&lt;&lt;509.0,437.0&gt;--&lt;648.0,438.0&gt;&gt;

* uniFF0D (U+FF0D): L&lt;&lt;124.0,384.0&gt;--&lt;355.0,382.0&gt;&gt;

* uniFF0D (U+FF0D): L&lt;&lt;295.0,212.0&gt;--&lt;64.0,214.0&gt;&gt;

* uniFF3F (U+FF3F): L&lt;&lt;164.0,-21.0&gt;--&lt;700.0,-23.0&gt;&gt;

* uniFF3F (U+FF3F): L&lt;&lt;640.0,-193.0&gt;--&lt;104.0,-191.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: gothic, coptic, glagolitic, math, elbasan</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, math, old-permic, canadian-aboriginal, tifinagh, tai-le, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+031A COMBINING LEFT ANGLE ABOVE: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+031C COMBINING LEFT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032C COMBINING CARON BELOW: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, cherokee, syriac, caucasian-albanian, tifinagh</li>
<li>U+0332 COMBINING LOW LINE: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0339 COMBINING RIGHT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+034A COMBINING NOT TILDE ABOVE: not included in any glyphset definition</li>
<li>U+034B COMBINING HOMOTHETIC ABOVE: not included in any glyphset definition</li>
<li>U+034C COMBINING ALMOST EQUAL TO ABOVE: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: not included in any glyphset definition</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: not included in any glyphset definition</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: not included in any glyphset definition</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: not included in any glyphset definition</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: not included in any glyphset definition</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: not included in any glyphset definition</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: grantha, mahajani, thai, canadian-aboriginal, ahom, elbasan, hanifi-rohingya, math, mende-kikakui, kharoshthi, rejang, sogdian, tagalog, gunjala-gondi, masaram-gondi, hanunoo, gujarati, marchen, sinhala, brahmi, phags-pa, bassa-vah, cham, osage, yi, warang-citi, buginese, armenian, kannada, adlam, old-permic, tibetan, oriya, hebrew, soyombo, telugu, bhaiksuki, takri, pahawh-hmong, sharada, chakma, syloti-nagri, psalter-pahlavi, devanagari, mandaic, zanabazar-square, khudawadi, tirhuta, kaithi, limbu, javanese, bengali, caucasian-albanian, tai-viet, modi, buhid, khojki, gurmukhi, lao, khmer, tai-tham, thaana, myanmar, tamil, manichaean, balinese, kayah-li, lepcha, duployan, symbols, coptic, miao, saurashtra, wancho, music, meetei-mayek, siddham, malayalam, new-tai-lue, newa, syriac, tifinagh, dogra, nko, mongolian, tagbanwa, sundanese, tai-le, batak</li>
<li>U+3001 IDEOGRAPHIC COMMA: try adding one of: mongolian, chinese-hongkong, chinese-traditional, phags-pa, yi, japanese, chinese-simplified, tai-le</li>
<li>U+3002 IDEOGRAPHIC FULL STOP: try adding one of: mongolian, chinese-hongkong, chinese-traditional, phags-pa, yi, japanese, nushu, chinese-simplified, tai-le</li>
<li>U+3003 DITTO MARK: try adding one of: chinese-hongkong, chinese-traditional, phags-pa, yi, japanese, chinese-simplified</li>
<li>U+3008 LEFT ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-traditional, phags-pa, yi, japanese, chinese-simplified, tai-le</li>
<li>U+3009 RIGHT ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-traditional, phags-pa, yi, japanese, chinese-simplified, tai-le</li>
<li>U+301C WAVE DASH: try adding japanese</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: japanese, chinese-simplified</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: japanese, chinese-simplified, yi</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: japanese, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>dcaron uses component uni030C.</p>
 [code: wrong-mark]



* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+01E4: LATIN CAPITAL LETTER G WITH STROKE</td>
<td align="left">U+01E5: LATIN SMALL LETTER G WITH STROKE</td>
</tr>
<tr>
<td align="left">U+022F: LATIN SMALL LETTER O WITH DOT ABOVE</td>
<td align="left">U+022E: LATIN CAPITAL LETTER O WITH DOT ABOVE</td>
</tr>
<tr>
<td align="left">U+024B: LATIN SMALL LETTER Q WITH HOOK TAIL</td>
<td align="left">U+024A: LATIN CAPITAL LETTER SMALL Q WITH HOOK TAIL</td>
</tr>
<tr>
<td align="left">U+024C: LATIN CAPITAL LETTER R WITH STROKE</td>
<td align="left">U+024D: LATIN SMALL LETTER R WITH STROKE</td>
</tr>
<tr>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs have no contours even though they were expected to have some:</p>
<pre><code>- Glyph name: uni203F	Expected: 1

- Glyph name: uni203F	Expected: 1
</code></pre>
 [code: no-contour]



* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: quotedbl	Contours detected: 4	Expected: 2

- Glyph name: numbersign	Contours detected: 5	Expected: 2

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: plus	Contours detected: 3	Expected: 1

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: b	Contours detected: 3	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: i	Contours detected: 1	Expected: 2

- Glyph name: j	Contours detected: 1	Expected: 2

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: logicalnot	Contours detected: 2	Expected: 1

- Glyph name: registered	Contours detected: 5	Expected: 3 or 4

- Glyph name: plusminus	Contours detected: 4	Expected: 1 or 2

- Glyph name: paragraph	Contours detected: 4	Expected: 1, 2 or 3

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: ae	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: iacute	Contours detected: 1	Expected: 2

- Glyph name: eth	Contours detected: 3	Expected: 2

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: thorn	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0180	Contours detected: 3	Expected: 2

- Glyph name: uni0189	Contours detected: 3	Expected: 2

- Glyph name: uni0197	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni01E3	Contours detected: 3	Expected: 4

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: aeacute	Contours detected: 3	Expected: 4

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni1E15	Contours detected: 3	Expected: 4

- Glyph name: uni1E17	Contours detected: 3	Expected: 4

- Glyph name: uni1E21	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni1E3E	Contours detected: 3	Expected: 2

- Glyph name: uni1E42	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E49	Contours detected: 3	Expected: 2

- Glyph name: uni1EB9	Contours detected: 2	Expected: 3

- Glyph name: uni1EBB	Contours detected: 2	Expected: 3

- Glyph name: uni1EBD	Contours detected: 2	Expected: 3

- Glyph name: uni1EBF	Contours detected: 3	Expected: 4

- Glyph name: uni1EC1	Contours detected: 3	Expected: 4

- Glyph name: uni1EC3	Contours detected: 3	Expected: 4

- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

- Glyph name: uni1EC7	Contours detected: 3	Expected: 4

- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

- Glyph name: uni2016	Contours detected: 4	Expected: 2

- Glyph name: ellipsis	Contours detected: 2	Expected: 3

- Glyph name: uni20AA	Contours detected: 3	Expected: 2

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: ae	Contours detected: 2	Expected: 3

- Glyph name: aeacute	Contours detected: 3	Expected: 4

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: b	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: ellipsis	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: eth	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 1	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: i	Contours detected: 1	Expected: 2

- Glyph name: iacute	Contours detected: 1	Expected: 2

- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

- Glyph name: j	Contours detected: 1	Expected: 2

- Glyph name: logicalnot	Contours detected: 2	Expected: 1

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: numbersign	Contours detected: 5	Expected: 2

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: paragraph	Contours detected: 4	Expected: 1, 2 or 3

- Glyph name: plus	Contours detected: 3	Expected: 1

- Glyph name: plusminus	Contours detected: 4	Expected: 1 or 2

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: quotedbl	Contours detected: 4	Expected: 2

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: registered	Contours detected: 5	Expected: 3 or 4

- Glyph name: thorn	Contours detected: 3	Expected: 2

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: uni0180	Contours detected: 3	Expected: 2

- Glyph name: uni0189	Contours detected: 3	Expected: 2

- Glyph name: uni0197	Contours detected: 2	Expected: 1

- Glyph name: uni01E3	Contours detected: 3	Expected: 4

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni1E15	Contours detected: 3	Expected: 4

- Glyph name: uni1E17	Contours detected: 3	Expected: 4

- Glyph name: uni1E21	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni1E3E	Contours detected: 3	Expected: 2

- Glyph name: uni1E42	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E49	Contours detected: 3	Expected: 2

- Glyph name: uni1EB9	Contours detected: 2	Expected: 3

- Glyph name: uni1EBB	Contours detected: 2	Expected: 3

- Glyph name: uni1EBD	Contours detected: 2	Expected: 3

- Glyph name: uni1EBF	Contours detected: 3	Expected: 4

- Glyph name: uni1EC1	Contours detected: 3	Expected: 4

- Glyph name: uni1EC3	Contours detected: 3	Expected: 4

- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

- Glyph name: uni1EC7	Contours detected: 3	Expected: 4

- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

- Glyph name: uni2016	Contours detected: 4	Expected: 2

- Glyph name: uni20AA	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.0, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">bwj_Latn (Láá Láá Bwamu)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">pkb_Latn (Pokomo)</td>
<td align="left">Some base glyphs were missing: D̯, T̯, d̯, t̯</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̯</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">bfo_Latn (Malba Birifor)</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">lnl_Latn (South Central Banda)</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">Some base glyphs were missing: ᵽ, Ᵽ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
</tr>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">kaj_Latn (Jju)</td>
<td align="left">Shaper didn't attach uni0331 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to U</td>
</tr>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to W</td>
</tr>
<tr>
<td align="left">bdh_Latn (Baka)</td>
<td align="left">Shaper didn't attach dotbelowcomb to V</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach dotbelowcomb to v</td>
</tr>
<tr>
<td align="left">ksp_Latn (Kabba)</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">Shaper didn't attach gravecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">Some base glyphs were missing: B̯, b̯</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̯</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">bsc_Latn_GN (Bassari)</td>
<td align="left">Some base glyphs were missing: Ɉ, ɉ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
</tr>
<tr>
<td align="left">ln_Latn (Lingala)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some base glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">tzm_Latn (Central Atlas Tamazight)</td>
<td align="left">Some base glyphs were missing: Gʷ, Kʷ, gʷ, kʷ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">Shaper didn't attach tildecomb to V</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to v</td>
</tr>
<tr>
<td align="left">uth_Latn (ut-Hun)</td>
<td align="left">Shaper didn't attach uni0331 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to U</td>
</tr>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">Some mark glyphs were missing: ◌̍, ◌᷄, ◌᷅</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">Some base glyphs were missing: ʝ, Ʝ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">bba_Latn (Baatonum)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">knc_Latn (Kanuri, Central)</td>
<td align="left">Some base glyphs were missing: ɍ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
<tr>
<td align="left">rif_Latn (Riffian (Latin))</td>
<td align="left">Some mark glyphs were missing: ◌̑</td>
</tr>
<tr>
<td align="left">dya_Latn (Dyan)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">goa_Latn (Guro)</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
</tr>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">aeb_Latn (Tunisian Darija)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">mey_Latn (Hassaniyya)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0307 to x</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">kpe_Latn (Kpelle)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">nga_Latn (Ngbaka)</td>
<td align="left">Some mark glyphs were missing: ◌̍</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">naq_Latn (Nama)</td>
<td align="left">Some base glyphs were missing: ǀ, ǁ, ǂ, ǃ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">kr_Latn (Kanuri)</td>
<td align="left">Some base glyphs were missing: ɍ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">ntm_Latn (Nateni)</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">mwm_Latn (Sar)</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Umacron</td>
</tr>
<tr>
<td align="left">yba_Latn (Yala)</td>
<td align="left">Some base glyphs were missing: A̍, E̍, I̍, O̍, U̍, a̍, e̍, i̍, o̍, u̍, Ɔ̍, Ɛ̍, ɔ̍, ɛ̍</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̍</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">buu_Latn (Budu)</td>
<td align="left">Some base glyphs were missing: ꞉, ꞊</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">xsm_Latn_BF (Kasem)</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some base glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to c</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to p</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to P</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">yre_Latn (Yaouré)</td>
<td align="left">Some base glyphs were missing: ˗, ˮ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">tbz_Latn (Ditammari)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">kst_Latn (Winyé)</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
<td align="left">Shaper didn't attach uni0304 to v</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to V</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to v</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to V</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to v</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to V</td>
</tr>
<tr>
<td align="left">dnj_Latn_LR (Dan)</td>
<td align="left">Some base glyphs were missing: Ɵ, Ɵ̀, Ɵ́, Ɵ̂, ɥ, ɥ̀, ɥ́, ɥ̂, ɥ̃̀, ɵ, ɵ̀, ɵ́, ɵ̂</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">din_Latn (Dinka)</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">lob_Latn (Lobi)</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">kby_Latn (Kanuri, Manga)</td>
<td align="left">Some base glyphs were missing: ɍ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">gvl_Latn (Gulay)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">bsq_Latn (Bassa)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">grb_Latn (Grebo)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">Some base glyphs were missing: ɪ, ɪ̃, Ɪ, Ɪ̃, Ꞷ, Ꞷ̃, ꞷ, ꞷ̃</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">box_Latn (Buamu)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">Shaper didn't attach uni0324 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to W</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to W</td>
</tr>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oe</td>
</tr>
<tr>
<td align="left">lol_Latn (Mongo)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">etx_Latn (Iten)</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some base glyphs were missing: Ɯ, Ɯ̀, Ɯ́, Ɯ̂, Ɯ̄, Ɯ̋, Ɯ̏, ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, ɯ, ɯ̀, ɯ́, ɯ̂, ɯ̄, ɯ̋, ɯ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">Some base glyphs were missing: ˗</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">sba_Latn (Ngambay)</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
</tr>
<tr>
<td align="left">bqc_Latn (Boko)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">Some base glyphs were missing: A᷆, A᷇, E᷆, E᷇, I᷆, I᷇, O᷆, O᷇, U᷆, U᷇, a᷆, a᷇, e᷆, e᷇, i᷆, i᷇, o᷆, o᷇, u᷆, u᷇, Ɔ᷆, Ɔ᷇, Ɛ᷆, Ɛ᷇, ɔ᷆, ɔ᷇, ɛ᷆, ɛ᷇</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌᷆, ◌᷇</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">kcg_Latn (Tyap)</td>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
</tr>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">lu_Latn (Luba-Katanga)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">btt_Latn (Bete-Bendi)</td>
<td align="left">Some base glyphs were missing: A᷅, A᷆, E᷅, E᷆, I᷅, I᷆, O᷅, O᷆, U᷅, U᷆, a᷅, a᷆, e᷅, e᷆, i᷅, i᷆, o᷅, o᷆, u᷅, u᷆</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌᷅, ◌᷆</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
</tr>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">ktz_Latn (Juǀʼhoan)</td>
<td align="left">Some base glyphs were missing: ǀ, ǁ, ǂ, ǃ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">mql_Latn (Mbelime)</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">apd_Latn (Sudanese Arabic)</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">mge_Latn (Mango)</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Egrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Eacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Emacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Umacron</td>
</tr>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to O</td>
</tr>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
</tr>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to O</td>
</tr>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">tuz_Latn (Turka)</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">bom_Latn (Berom)</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">Shaper didn't attach uni0308 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
</tr>
<tr>
<td align="left">shi_Latn (Tachelhit (Latin))</td>
<td align="left">Some base glyphs were missing: Gʷ, Kʷ, gʷ, kʷ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">ngh_Latn (Nǁng)</td>
<td align="left">Some base glyphs were missing: ǀ, ǁ, ǂ, ǃ, ʘ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">bqp_Latn (Bisã)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to Umacron</td>
</tr>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">asg_Latn (Cishingini)</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to A</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sok_Latn (Sokoro)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fue_Latn (Fulfulde, Borgu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some auxiliary glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xsm_Latn (Kasem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dag_Latn (Dagbani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">khq_Latn (Koyra Chiini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ekm_Latn (Elip)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dzg_Latn (Dazaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">pkb_Latn (Pokomo)</td>
<td align="left">Some auxiliary glyphs were missing: D̯, T̯, d̯, t̯</td>
</tr>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xon_Latn (Konkomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fuq_Latn (Central-Eastern Niger Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ahl_Latn (Igo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yam_Latn (Yamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">shz_Latn (Syenara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ken_Latn (Kenyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fuc_Latn (Pulaar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kye_Latn (Krache)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nko_Latn (Nkonya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gde_Latn (Gude)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nhb_Latn (Beng)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kmy_Latn (Koma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gng_Latn (Ngangam)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bzx_Latn (Bozo, Hainyaxo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ted_Latn (Krumen, Tepo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lam_Latn (Lamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lok_Latn (Loko)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xed_Latn (Hdi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nuv_Latn (Nuni, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sig_Latn (Paasaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">Some auxiliary glyphs were missing: B̯, b̯</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sil_Latn (Sisaala, Tumulung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ajg_Latn (Aja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">maw_Latn (Mampruli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lig_Latn (Ligbi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some auxiliary glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ</td>
</tr>
<tr>
<td align="left">kyq_Latn (Kenga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bcw_Latn (Bana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mur_Latn (Murle)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">hag_Latn (Hanga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">wan_Latn (Wan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fod_Latn (Foodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tzm_Latn (Central Atlas Tamazight)</td>
<td align="left">Some auxiliary glyphs were missing: Gʷ, Kʷ, gʷ, kʷ</td>
</tr>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tnr_Latn (Ménik)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">avn_Latn (Avatime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ktj_Latn (Krumen, Plapo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ade_Latn (Adele)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">Some auxiliary glyphs were missing: ʝ, Ʝ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lia_Latn (Limba, West-Central)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">cae_Latn (Lehar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mzw_Latn (Deg)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kdh_Latn (Tem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kfo_Latn (Koro)</td>
<td align="left">No exemplar glyphs were defined for language Koro</td>
</tr>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bfa_Latn (Bari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xuo_Latn (Kuo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ahs_Latn (Ashe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">krs_Latn (Gbaya (Sudan))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mbo_Latn (Mbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">cko_Latn (Anufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yat_Latn (Yambeta)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mfv_Latn (Mandjak)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">taq_Latn (Tamasheq, Latin)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kpo_Latn (Ikposo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mnk_Latn (Mandinka)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kus_Latn (Kusaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">cme_Latn (Cerma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">log_Latn (Logo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tem_Latn (Timne)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">aeb_Latn (Tunisian Darija)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">dyo_Latn (Jola-Fonyi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">agc_Latn (Agatu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gux_Latn (Gourmanchéma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gud_Latn (Dida, Yocoboué)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ny_Latn (Nyanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ndv_Latn (Ndut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sxw_Latn (Saxwe Gbe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">naq_Latn (Nama)</td>
<td align="left">Some auxiliary glyphs were missing: ǀ, ǁ, ǂ, ǃ</td>
</tr>
<tr>
<td align="left">nza_Latn (Tigon Mbembe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">syi_Latn (Seki)</td>
<td align="left">No exemplar glyphs were defined for language Seki</td>
</tr>
<tr>
<td align="left">bib_Latn (Bissa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bim_Latn (Bimoba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kvf_Latn (Kabalai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dts_Latn (Dogon, Toro So)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bav_Latn (Vengo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ses_Latn (Koyraboro Senni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kbp_Latn (Kabiyé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">laj_Latn (Lango [Uganda])</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yba_Latn (Yala)</td>
<td align="left">Some auxiliary glyphs were missing: A̍, E̍, I̍, O̍, U̍, a̍, e̍, i̍, o̍, u̍, Ɔ̍, Ɛ̍, ɔ̍, ɛ̍</td>
</tr>
<tr>
<td align="left">buu_Latn (Budu)</td>
<td align="left">Some auxiliary glyphs were missing: ꞉, ꞊</td>
</tr>
<tr>
<td align="left">bza_Latn (Bandi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">muy_Latn (Muyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kqs_Latn (Kissi, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kyf_Latn (Kouya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some auxiliary glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yre_Latn (Yaouré)</td>
<td align="left">Some auxiliary glyphs were missing: ˗, ˮ</td>
</tr>
<tr>
<td align="left">mwk_Latn (Kita Maninkakan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dtm_Latn (Tomo Kan Dogon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fuh_Latn (Fulfulde, Western Niger)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ncu_Latn (Chumburung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">twq_Latn (Tasawaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mbu_Latn (Mbula-Bwazza)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">wci_Latn (Gbe, Waci)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gjn_Latn (Gonja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ntr_Latn (Delo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fub_Latn (Fulfulde, Adamawa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fuf_Latn (Pular)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn_LR (Dan)</td>
<td align="left">Some auxiliary glyphs were missing: Ɵ, Ɵ̀, Ɵ́, Ɵ̂, ɥ, ɥ̀, ɥ́, ɥ̂, ɥ̃̀, ɵ, ɵ̀, ɵ́, ɵ̂</td>
</tr>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bex_Latn (Jur Modo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
<tr>
<td align="left">dop_Latn (Lukpa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kby_Latn (Kanuri, Manga)</td>
<td align="left">Some auxiliary glyphs were missing: ɍ</td>
</tr>
<tr>
<td align="left">azo_Latn (Awing)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">spp_Latn (Sénoufo, Supyire)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kao_Latn (Xaasongaxango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">las_Latn (Lama (Togo))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sav_Latn (Saafi-Saafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nfr_Latn (Nafaanra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yas_Latn (Nugunu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bss_Latn (Akoose)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">pbi_Latn (Parkwa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">adj_Latn (Adioukrou)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">amo_Latn (Amo)</td>
<td align="left">No exemplar glyphs were defined for language Amo</td>
</tr>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some auxiliary glyphs were missing: Ɯ, Ɯ̀, Ɯ́, Ɯ̂, Ɯ̄, Ɯ̋, Ɯ̏, ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, ɯ, ɯ̀, ɯ́, ɯ̂, ɯ̄, ɯ̋, ɯ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni0181</td>
</tr>
<tr>
<td align="left">mgy_Latn (Mbunga)</td>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
</tr>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">Some auxiliary glyphs were missing: ˗</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bzw_Latn (Basa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">anv_Latn (Denya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">cou_Latn (Wamey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bsp_Latn (Baga Sitemu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">idu_Latn (Idoma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">wo_Latn (Wolof)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dyi_Latn (Sénoufo, Djimini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">acd_Latn (Gikyode)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mfd_Latn (Mendankwe-Nkwen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">Some auxiliary glyphs were missing: A᷆, A᷇, E᷆, E᷇, I᷆, I᷇, O᷆, O᷇, U᷆, U᷇, a᷆, a᷇, e᷆, e᷇, i᷆, i᷇, o᷆, o᷇, u᷆, u᷇, Ɔ᷆, Ɔ᷇, Ɛ᷆, Ɛ᷇, ɔ᷆, ɔ᷇, ɛ᷆, ɛ᷇</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lns_Latn (Lamnso’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xwe_Latn (Gbe, Xwela)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">knp_Latn (Kwanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
</tr>
<tr>
<td align="left">nhu_Latn (Noone)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mcn_Latn (Masana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">moa_Latn (Mwan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">dje_Latn (Zarma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nym_Latn (Nyamwezi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gaa_Latn (Ga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01A9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B7</td>
</tr>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">pil_Latn (Yom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">meq_Latn (Merey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">hna_Latn (Mina)</td>
<td align="left">No exemplar glyphs were defined for language Mina</td>
</tr>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bbo_Latn (Northern Bobo Madaré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">btt_Latn (Bete-Bendi)</td>
<td align="left">Some auxiliary glyphs were missing: A᷅, A᷆, E᷅, E᷆, I᷅, I᷆, O᷅, O᷆, U᷅, U᷆, a᷅, a᷆, e᷅, e᷆, i᷅, i᷆, o᷅, o᷆, u᷅, u᷆</td>
</tr>
<tr>
<td align="left">mmu_Latn (Mmaala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">toq_Latn (Toposa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lmp_Latn (Limbum)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kqp_Latn (Kimré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">srr_Latn (Serer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">boz_Latn (Tiéyaxo Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mcu_Latn (Mambila, Cameroon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ffm_Latn (Maasina Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">keu_Latn (Akebu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mfi_Latn (Wandala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mgc_Latn (Morokodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ndz_Latn (Ndogo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tod_Latn (Toma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B2</td>
</tr>
<tr>
<td align="left">naw_Latn (Nawuri)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">cch_Latn (Atsam)</td>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
</tr>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mdj_Latn (Mangbetu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">xrb_Latn (Karaboro, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lun_Latn (Lunda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">gmm_Latn (Gbaya-Mbodomo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nku_Latn (Kulango, Bouna)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">ach_Latn (Acoli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">shi_Latn (Tachelhit (Latin))</td>
<td align="left">Some auxiliary glyphs were missing: Gʷ, Kʷ, gʷ, kʷ</td>
</tr>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">sef_Latn (Cebaara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">snf_Latn (Noon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">bze_Latn (Jenaama Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">vag_Latn (Vagla)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">lem_Latn (Nomaande)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">tpm_Latn (Tampulma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mfq_Latn (Moba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 9 | 116 | 6 | 113 | 0 | 
| 0% | 0% | 2% | 4% | 47% | 2% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG