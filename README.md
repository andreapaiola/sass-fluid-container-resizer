# sass-fluid-container-resizer
<h1>Fluid Container with Clamp Calculator</h1>
<h2>What is it?</h2>
<p>
A SASS (SCSS) calculator with linear fluid scaling and clamping in a CSS container.
</p>
<h2>How does it work?</h2>
<p>
FCCCalc paramethers:
</p>
<code>
@function FCCCalc($minValue, $maxValue, $minWidth, $maxWidth)
</code>
<ul>
<li>$minValue: minimum value</li>
<li>$maxValue: maximum value</li>
<li>$minWidth: minimum width</li>
<li>$maxWidth: maximum width</li>
</ul>
<h3>Example:</h3>
<code>
.box{
  font-size: FCCCalc(16,24,400,800);
}
</code>
