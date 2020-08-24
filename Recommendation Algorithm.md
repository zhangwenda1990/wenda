---


---

<h1 id="recommendation-algorithm">Recommendation Algorithm</h1>
<h2 id="four-recommendation-paradigms">Four recommendation paradigms</h2>
<p><strong>Content-based filtering</strong> algorithm,  <strong>Collaborative filtering</strong> algorithm, <strong>Social and demographic</strong> recommendation algorithm, and <strong>Contexual</strong> recommendation algorithm.</p>
<h4 id="content-based-filtering-algorithm">1. Content-based filtering algorithm</h4>
<p>This algorithm recommend similar items based on domain-specific notion of item content. This approach can be used when metadata is available (attributes of data like author’s name, publish year, file size, etc.).</p>
<blockquote>
<p>Content-based filtering methods are based on similarity of content attributes.</p>
</blockquote>
<ul>
<li>Uses attributes of items or users</li>
<li>Recommend items similar to those liked by the user in the past</li>
<li>Not support diverse content recommendation</li>
</ul>
<h4 id="collaborative-filtering-algorithm">2. Collaborative filtering algorithm</h4>
<p>This algorithm use given matrix of user preferences for items to predict missing preferences for items and recommend items with high predictions. The start of this algorithm is to define the notion of preference and user/item IDs.</p>
<blockquote>
<p>Collaborative filtering methods are based on similarity of users. Collaborative filtering is perhaps the most well-known approach, to the point that it’s seen as the synonymous with the field of recommendation.</p>
</blockquote>
<ul>
<li>Recommend items liked by similar users</li>
<li>Enable exploration of diverse content</li>
</ul>
<p><img src="https://miro.medium.com/max/800/0*JnvYsBGc2vWT5JOQ" alt="Image for post"></p>
<h4 id="social-and-demographic-recommendation-algorithm">3. Social and demographic recommendation algorithm</h4>
<p>This algorithm suggests items that are liked by friends.</p>
<ul>
<li>No need for preferences by the target users</li>
<li>Based on demographically-similar people or connected people (like friends).</li>
</ul>
<h4 id="contextual-recommendation-algorithm">4. Contextual recommendation algorithm</h4>
<p>This algorithm recommends items that match the user’s current context.</p>
<h2 id="evaluation">Evaluation</h2>
<ul>
<li>RMSE</li>
<li>Top-N recommendation</li>
</ul>
<blockquote>
<p>Root mean squared error (RMSE) is widely used in despite of poor estimation for online performance</p>
</blockquote>
<p>u – user;<br>
i – item;<br>
model(u, i) – predicted ratings;<br>
r – observed ratings<br>
<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi mathvariant="normal">∣</mi><msub><mi>R</mi><mrow><mi>t</mi><mi>e</mi><mi>s</mi><mi>t</mi></mrow></msub><mi mathvariant="normal">∣</mi></mrow><annotation encoding="application/x-tex">|R_{test}|</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">∣</span><span class="mord"><span class="mord mathdefault" style="margin-right: 0.00773em;">R</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.280556em;"><span class="" style="top: -2.55em; margin-left: -0.00773em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathdefault mtight">t</span><span class="mord mathdefault mtight">e</span><span class="mord mathdefault mtight">s</span><span class="mord mathdefault mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mord">∣</span></span></span></span></span> – number of test cases<br>
<img src="https://miro.medium.com/max/800/0*fumY8hRkzmo2XRjE" alt="Image for post"></p>
<blockquote>
<p>Top-N recommendation is the confusion matrix of testing results</p>
</blockquote>
<p><img src="https://miro.medium.com/max/800/0*B3Bjy-bAmzSG4VEE" alt="Image for post"></p>
<h2 id="application-domains">Application domains</h2>
<blockquote>
<p>Media/eCommerce/Jobs boards/Travel and Real Estate/Education</p>
</blockquote>
<ul>
<li>Media – news, videos, music</li>
<li>eCommerce – products</li>
<li>Job boards – personalizing job boards, email newsletters with job offers</li>
<li>Travel – events, hotel, restaurants, flights, car rentals (all info)</li>
<li>Real Estate – house buying, house rental</li>
<li>Education – education materials</li>
</ul>

