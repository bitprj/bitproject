# Writing Style Guides

## Punctuation 

### Case

Use sentence case for titles, headings, labels, menu items, and buttons. Use title case when referring to [features](https://about.gitlab.com/features/) or [products](https://about.gitlab.com/products/). Note that some features are also objects \(for example, “Merge Requests” and “Merge requests”\).

| Do | Don’t |
| :--- | :--- |
| Add issues to the Issue Board feature in GitLab Hosted. | Add Issues to the Issue Board Feature in GitLab Hosted. |

Always capitalize the first word in bulleted lists. This includes sentences that complete an introductory stem.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>This is an introductory stem:</p>
        <ul>
          <li>Completed by this capitalized sentence.</li>
          <li>Also completed by this capitalized sentence.</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>This is an introductory stem:</p>
        <ul>
          <li>completed by this uncapitalized sentence.</li>
          <li>also completed by this uncapitalized sentence.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>### Periods

A period signals to a speaker or reader that a sentence has come to an end, and it assists users in visually breaking up content. Follow these guidelines:

Place a period after a link that is followed by a sentence.

| Do | Don’t |
| :--- | :--- |
| Mention someone to notify them. [More information](https://design.gitlab.com/content/punctuation/#). This is another sentence. | Mention someone to notify them. [More information](https://design.gitlab.com/content/punctuation/#). |

Place periods after sentences that follow a link.

| Do | Don’t |
| :--- | :--- |
| Mention someone to notify them. [More information](https://design.gitlab.com/content/punctuation/#). This is another sentence. | Mention someone to notify them [More information](https://design.gitlab.com/content/punctuation/#). This is another sentence |

Use a period after every bullet point that is a sentence.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>This is a complete sentence.</li>
          <li>This is also a complete sentence.</li>
        </ul>
      </td>
      <td style="text-align:left">
        <ul>
          <li>This is a complete sentence, it needs a period</li>
          <li>This is also a complete sentence, it also needs a period</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>Use a period after every bullet point that completes the introductory stem.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>This is an introductory stem:</p>
        <ul>
          <li>Completed by this sentence.</li>
          <li>Also completed by this sentence.</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>This is an introductory stem:</p>
        <ul>
          <li>Completed by this sentence</li>
          <li>Also completed by this sentence</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>Use no punctuation after bullets that are not sentences and do not complete the stem.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>These are just words in a list:</p>
        <ul>
          <li>One item</li>
          <li>Two item</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>These are just words in a list:</p>
        <ul>
          <li>One item.</li>
          <li>Two item.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>Use all sentences or all fragments in a bulleted list, not a mixture.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>Consistency is key here.</li>
          <li>Item.</li>
          <li>Don&#x2019;t mix sentences and individual items in a list.</li>
        </ul>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Consistency is key here.</li>
          <li>Item</li>
          <li>Don&#x2019;t mix sentences and individual items in a list.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>### Contractions

We encourage the use of contractions to make writing simpler and easier to read. However, don’t make a sentence harder to understand just to follow this rule. For example, “do not” can give more emphasis than “don’t,” when needed.

| Do | Don’t |
| :--- | :--- |
| it’s, can’t, wouldn’t, you’re, you’ve, haven’t, don’t | it is, cannot, would not, it’ll, should’ve |

### Numbers

Use “1, 2, 3” instead of “one, two, three” for numbers. One exception is when mixing uses of numbers, such as “Enter two 3s.”

| Do | Don’t |
| :--- | :--- |
| 3 new commits | Three new commits |
| Enter two 3s. | Enter 2 3s. |

### Punctuation overview

Use punctuation to add clarity or be grammatically correct.

| Punctuation mark | Copy and paste | HTML entity | Description |
| :--- | :--- | :--- | :--- |
| Period | **.** |  | Use in lists or modals with full and multiple sentences, and any sentence followed by a link or inline code.  Place inside quotation marks, unless you’re telling the reader what to enter and it’s ambiguous whether to include the period. |
| Comma | **,** |  | Place inside quotation marks.  Use a [serial comma](https://en.wikipedia.org/wiki/Serial_comma) in lists of three or more terms. |
| Exclamation point | **!** |  | Avoid exclamation points, as they tend to come across as shouting. Some exceptions include greetings or congratulatory messages. |
| Colon | **:** | `&#58;` | Omit from form labels. |
| Apostrophe | **’** | `&rsquo;` | Use for contractions \(I’m, you’re, ’89\) and to show possession.  To show possession, add an _’s_ to all singular common nouns and names, even if they already end in an _s_: “Look into this worker process’s log.” For singular proper names ending in _s_, use only an apostrophe: “James’ commits.” For plurals of a single letter, add an _’s_: “Dot your i’s and cross your t’s.”  Omit for decades or acronyms: “the 1990s”, “MRs.” |
| Quotation marks | **“**  **”**  **‘**  **’** | `&ldquo;`  `&rdquo;`  `&lsquo;`  `&rsquo;` | Use proper quotation marks \(also known as smart quotes, curly quotes, or typographer’s quotes\) for quotes. Single quotation marks are used for quotes inside of quotes.  The right single quotation mark symbol is also used for apostrophes.  Don’t use primes, straight quotes, or free-standing accents for quotation marks. |
| Straight quotes and accents | **"**  **'**  **\`**  **´** |  | Don’t use straight quotes or free-standing accents for primes or quotation marks.  Proper typography never uses straight quotes. They are left over from the age of typewriters, and their only modern use is for code. |
| Ellipsis | **…** | `&hellip;` | Use to indicate an action in progress \(“Downloading…”\) or incomplete or truncated text. No space before the ellipsis.  Omit from menu items or buttons that open a modal or start some other process. |
| Chevrons | **«**  **»**  **‹**  **›**  **&lt;**  **&gt;** | `&#171;`  `&#187;`  `&#8249;`  `&#8250;`  `&lt;`  `&gt;` | Omit from links or buttons that open another page or move to the next or previous step in a process. Also known as angle brackets, angular quote brackets, or guillemets. We use [icons](https://design.gitlab.com/foundations/iconography) in place of written chevrons. |
| Em dash | **—** | `&mdash;` | Avoid using dashes to separate text. If you must use dashes for this purpose — like this — use an em dash surrounded by spaces. |
| En dash | **–** | `&ndash;` | Use an en dash without spaces instead of a hyphen to indicate a range of values, such as numbers, times, and dates: “3–5 kg”, “8:00 AM–12:30 PM”, “10–17 Jan” |
| Hyphen | **-** |  | Use to represent negative numbers, or to avoid ambiguity in adjective-noun or noun-participle pairs. Example: “anti-inflammatory”; “5-mile walk.”  Omit in commonly understood terms and adverbs that end in _ly_: “frontend”, “greatly improved performance.”  Omit in the term “open source.” |
| Parentheses | **\( \)** |  | Use only to define acronyms or jargon: “Secure web connections are based on a technology called SSL \(the secure sockets layer\).”  Avoid other uses, and instead rewrite the text or use dashes or commas to set off the information. If parentheses are required: If the parenthetical is a complete, independent sentence, place the period inside the parentheses; if not, the period goes outside. |



## Voice and tone

Copy and messaging are meaningful aspects of the GitLab experience and the conversation with our users.

The copy for GitLab is clear and direct. We strike a balance between professional and friendly. We can empathize with users \(such as celebrating completing all items on the To-Do List\) while remaining respectful to the importance of their work. We are a trusted, friendly, helpful, and understanding coworker.

###  Active voice <a id="active-voice"></a>

Whenever possible, write in [active voice](https://www.grammarly.com/blog/active-vs-passive-voice/), instead of passive voice. Active voice is easier for users to understand and often results in shorter content.

Sometimes, using passive voice is appropriate. Make sure it’s an intentional choice that communicates the idea more clearly than active voice would—for example, when the system is the actor, rather than a person.

| Do | Don’t |
| :--- | :--- |
| **\(Active voice\)** Ask someone with write access to this repository to merge this request. | This request can be merged by someone with write access to this repository. |
| **\(Passive voice\)** The Kubernetes cluster is being created on Google Kubernetes Engine. | We are creating the Kubernetes cluster on Google Kubernetes Engine. |

###  Brevity <a id="brevity"></a>

Users will skim content, rather than read text carefully. Copy should be concise and short whenever possible. A long message or label is a red flag hinting at a design that needs improvement.

When familiar with a web app, users rely on muscle memory and may read even less when moving quickly. A good experience should quickly orient a user, regardless of their experience, to the purpose of the current screen. Understanding should happen without the user having to consciously read long strings of text.

In general, text is burdensome and adds cognitive load. This load is even more pronounced in a powerful productivity tool such as GitLab. We shouldn’t rely on words as a crutch to explain the purpose of a screen. Instead, the current navigation and composition of on-screen elements should get the user 95% there, with the remaining 5% being specific elements such as text.

Brevity is especially important for:

* Headers
* Button text
* Field labels
* Error messages

For each of these content types, look for ways you might rephrase text that seems too long. Also, eliminate unnecessary phrases like “in order to” and extra articles like “the” when they don’t add clarity.

| Do | Don’t |
| :--- | :--- |
| To link Sentry to GitLab, enter your Sentry URL and Auth Token. | In order to link Sentry to GitLab, enter your Sentry URL and Auth Token. |
| Use this token to validate received payloads. | Use this token to validate the received payloads. |

####  Avoid Latin abbreviations <a id="avoid-latin-abbreviations"></a>

While we aim to brief, we also avoid Latin abbreviations as they can be easily misinterpreted.

* Instead of “i.e.”, use “that is.”
* Instead of “e.g.”, use “for example.”
* Instead of “etc.”, either use “and so on” or consider editing it out, since it can be vague.

###  Clear error messages <a id="clear-error-messages"></a>

When something goes wrong, it’s important for us to be clear about what happened, why it happened, and what the next steps to take may be. Vague messages frustrate users and can even block them from completing their task.

When writing an error message, leave out extraneous words like _sorry_ and _please_. This makes errors easier to read and understand.

| Do | Don’t |
| :--- | :--- |
| Unable to complete your request. Enter a valid email address. | 400 Bad Request |
| Enter your email address to sign up with GitLab. | Please enter your email address to sign up with GitLab. |

###  Parallelism <a id="parallelism"></a>

[Parallel structure](https://writingcenter.gmu.edu/guides/parallel-structure) ensures that related content takes the same grammatical form; for example, all related items in a list are either a noun or a verb, not a mixture of both. Maintaining parallelism is important, because it’s grammatically correct and much easier to read.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Do</th>
      <th style="text-align:left">Don&#x2019;t</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>A project is where you:</p>
        <ul>
          <li>House your files</li>
          <li>Plan your work</li>
          <li>Publish your documentation</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>A project is where you:</p>
        <ul>
          <li>House your files</li>
          <li>Plan your work</li>
          <li>Publishing your documentation</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>###  Objective focused <a id="objective-focused"></a>

When users engage with our product, they’re focused on getting tasks done, thinking first in terms of the problem they’re trying to solve, and then how to solve it. Objective-focused content that starts with the task first and then offers the solution can make it easier for users to quickly find and understand the information they need.

| Do | Don’t |
| :--- | :--- |
| Monitor your errors by integrating with Sentry | Integrate with Sentry to monitor your errors |
| To see what’s changed, choose a branch or enter a commit. | Choose a branch or enter a commit to see what’s changed. |

###  Point of view <a id="point-of-view"></a>

In most cases, it’s appropriate to use the [second-person](https://www.quickanddirtytips.com/education/grammar/first-second-and-third-person?page=1) point of view, because it’s friendly and easy to understand.

The words “you,” “your,” and “yours” indicate that you’re writing in second person. It’s important to note that in UI copy, the “you” is often implied rather than stated. For example, instead of “You can track time with quick actions,” you might instruct users to “Track time with quick actions.”

To write in second person, focus on eliminating words like “can” or “will” from content.

| Do | Don’t |
| :--- | :--- |
| To get started, link this page to your Jaeger server. | Users can get started by linking this page to their Jaeger server. |

###  Verb tenses <a id="verb-tenses"></a>

####  Recent past \(instant feedback\) <a id="recent-past-(instant-feedback)"></a>

For a status update on something that has just happened in response to a user action or when a user is otherwise watching for an update, use the **present perfect** tense. This is ideal for toast messages and terminal output.

There are two options:

* When brevity is the priority, use only the noun and verb \(omitting articles and prepositions\); for example, “Pipeline scheduled.”
* When you want to use a full phrase for a human feel, use a complete sentence; for example, “The pipeline has been scheduled.”

####  Distant past \(earlier than instant feedback\) <a id="distant-past-(earlier-than-instant-feedback)"></a>

Use **past tense**.

| Do | Don’t |
| :--- | :--- |
| The pipeline was last run on October 3. | The pipeline has been run on October 3. |

####  State <a id="state"></a>

Use **present tense**.

| Do | Don’t |
| :--- | :--- |
| The pipeline is scheduled to run on October 3. | The pipeline will be run on October 3. |

####  Instructions <a id="instructions"></a>

Use the **present tense** with an imperative form \(also known as a command\).

| Do | Don’t |
| :--- | :--- |
| Click the Designs tab. | You will need to click the Designs tab. |
| To see what’s changed, choose a branch or enter a commit. | Choosing a branch or entering a commit will show you what’s changed. |

