[MDN Web Docs](https://developer.mozilla.org/en-US/){:target="_blank"} is a documentation repository and learning resource for web development. Topics include HTML, CSS, JavaScript, and more. 
As part of Writing Day during the [Write the Docs Portland 2022 conference](https://www.writethedocs.org/conf/portland/2022/){:target="_blank"}, I chose to work on MDN. I frequently use MDN so improving the documentation felt like a great way to give back to the MDN community.

## Contributions
While updating the documentation, I focused on the following:

- Updating syntax in the JavaScript code samples to modern standards
- Re-writing descriptions to be clear and concise 
- Review links to source code samples

I opened a number of pull requests and issues based on my updates.

### Pull Requests

When updating various documentation pages, I created the following pull requests. You can also view all my pull requests on [Github](https://github.com/mdn/content/pulls?q=author%3Aseumoo+){:target="_blank"}.

<table class="tg" style="undefined;table-layout: fixed; width: 487px">
<colgroup>
<col style="width: 50px">
<col style="width: 120px">
<col style="width: 275px">
<col style="width: 307px">
</colgroup>
<thead>
  <tr>
    <th class="tg-7btt">#</th>
    <th class="tg-7btt">Pull Request #</th>
    <th class="tg-7btt">Code Instance</th>
    <th class="tg-7btt">Work Done</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">1</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16348" target="_blank" rel="noopener noreferrer">16348</a></td>
    <td class="tg-9wq8""><code>Array.prototype.fill()</code></td>
    <td class="tg-lboi" rowspan="3">
        <ul>
            <li>Changed <code>var</code> declaration to <code>const</code> declaration</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td class="tg-c3ow">2</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16358" target="_blank" rel="noopener noreferrer">16358</a></td>
    <td class="tg-9wq8""><code>WebAssembly.validate()</code></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16546" target="_blank" rel="noopener noreferrer">16546</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Module()</code></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16519" target="_blank" rel="noopener noreferrer">16519</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Table.prototype.grow()</code></td>
    <td class="tg-lboi" rowspan="5">
        <ul>
            <li>Changed <code>var</code> declaration to <code>const</code> declaration</li>
            <li>Revised code descriptions</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16525" target="_blank" rel="noopener noreferrer">16525</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Table.prototype.grow()</code></td>
  </tr>
  <tr>
    <td class="tg-c3ow">6</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16554" target="_blank" rel="noopener noreferrer">16554</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Module.imports()</code></td>
  </tr>
  <tr>
    <td class="tg-c3ow">7</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16573" target="_blank" rel="noopener noreferrer">16573</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Module.customSections()</code></td>
  </tr>
  <tr>
    <td class="tg-c3ow">8</td>
    <td class="tg-c3ow"><a href="https://github.com/mdn/content/pull/16575" target="_blank" rel="noopener noreferrer">16575</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Module</code></td>
  </tr>
  <tr>
    <td class="tg-9wq8">9</td>
    <td class="tg-9wq8"><a href="https://github.com/mdn/content/pull/16500" target="_blank" rel="noopener noreferrer">16500</a></td>
    <td class="tg-9wq8""><code>WebAssembly.Table</code></td>
    <td class="tg-0pky">
        <ul>
            <li>Heavily revised the Examples section</li>
            <li>Re-wrote instructions to be clearer and in sequential order</li>
            <li>Added source code of reference files to improve accessibility</li>
            <li>Re-wrote code snippets to follow example instructions</li>
            <li>Added comments in code snippets to explain functionality</li>
            <li>Change <code>var</code> declaration to <code>const</code> declaration</li>
        </ul>
  </tr>
</tbody>
</table>

### Issues Opened

Many <code>WebAssembly</code> pages have live versions of their respective examples section. Live versions are very useful since you can examine the example code in real time and see how various code snippets work. 

While updating the <code>WebAssembly</code> pages, I noticed that many live examples display a blank page and thought the examples were broken. However, I realized the samples do work since they display the correct console logs. I opened an issue detailing my findings and provided recommendations to improve accessibility for the live versions.

<table class="tg" style="undefined;table-layout: fixed; width: 636px">
<colgroup>
<col style="width: 98px">
<col style="width: 280px">
<col style="width: 372px">
</colgroup>
<thead>
  <tr>
    <th class="tg-7btt">Issue #</th>
    <th class="tg-7btt">Issue</th>
    <th class="tg-7btt">Recommendations</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8"><a href="https://github.com/mdn/content/issues/16572" target="_blank" rel="noopener noreferrer">16572</a></td>
    <td class="tg-0pky">
        <ul>
            <li>Viewing live versions of <code>WebAssembly</code> examples displays a blank page</li>
            <li>Users may assume the live version is not working when it actually is</li>
        </ul>
        <td class="tg-0pky">
        <ul>
            <li>In the live version, display a line in the HTML that states, "Please open your Developer Console to display console logs based on the <code>WebAssembly</code> example"</li>
            <li>In the <code>WebAssembly</code> documentation page, include a note telling the user to open the Developer Console when viewing the live version</li>
        </ul>
    </td>
  </tr>
</tbody>
</table>

## Challenges

### Revising the Examples Section
Revising descriptions in the <code>WebAssembly.Table</code> examples section was challenging as the initial descriptions were unclear, the reference files were easily accessible, and the instructions were not sequential. I tried to segment the code snippets in an understandable sequential order, edited and moved descriptions to correlate with the instructions, and listed all references used.

I had trouble setting up my Visual Studio Code IDE when viewing my pull requests and contributor comments. It was hard to edit the documentation page as comments did not align with specific code lines even though comments were viewable on Github. I eventually committed a revision that implemented suggestions from various contributors and was extremely happy with the result.

## What I Learned

I learned about contributing to open source documentation using Github. This was my first creating pull requests, opening issues, and collaborating with others on a public Github repository. I had a lot of practice committing changes to pull requests and now understand how pull requests work and when to use them.

Additionally, I received a lot of feedback on grammar and code changes from other contributors. I learned how to use Visual Studio Code to checkout my pull requests, review contributor comments, and implement file changes. I learned a lot of about how <code>WebAssembly</code> works though contributors explaining how the code examples worked.

