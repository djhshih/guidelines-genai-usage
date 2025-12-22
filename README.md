# Guidelines on GenAI usage in science

While GenAI can provide productivity gain when used appropriately, it has also amplified the creation of unprofessional 
work dubbed "AI slop," without little effort from the users.

When GenAI makes something up that is not true, we call it "hallucination," personalifying GenAI with the use of this word.
In fact, GenAI does *not* hallucinate, for the simple reason that GenAI is not a person.
Rather, GenAI can *fabricate* information, and fabrication has serious ramifications in science.

The quality of work produced by GenAI can sometimes be impressive, especially in the context of writing 
text that need not be grounded in facts or generating images that need not be accurate. 
However, it is important that remember that AI-generated work often contains fabricated facts and data, 
because GenAI models are trained to generate text or images that are *plausible* but not necessiarily accurate.
Therefore, using GenAI in scientific work requires forethought and care.

At best, creating AI slop reflects poorly on your professionalism and quality of work; at worst, it causes you to commit misconduct.

## Misconducts

The definitions of scientific misconducts remain unchanged in the era of GenAI. Common misconducts include
- **Fabrication**: making up data, results, facts, or citations
- **Plagiarism**: explicitly or implicitly claiming other people's work as your own,
  such as using other's people's work without proper *attribution*
- **Copyright violation**: using other people's work without *permission* from the copyright owners

## Good applications

### Writing

- Revising and polishing the language of a piece of writing
- Drafting bureaucratic letters
- Language translation (e.g. to [English][sci-trans-en], [Simplified Chinese][sci-trans-zh-cn], or [Traditional Chinese][sci-trans-zh-hk])
- Critiquing your work (but ask the GenAI agent to be critical)
- [Sounding compassionate and empathetic][compassionate-ai]

[sci-trans-en]: https://poe.com/sci-trans-en
[sci-trans-zh-cn]: https://poe.com/sci-trans-zh-cn
[sci-trans-zh-hk]: https://poe.com/sci-trans-zh-hk
[compassionate-ai]: https://doi.org/10.1038/s44271-024-00182-6

### Coding

- Helping with the extraction of structured data from unstructured text ([example][matchminer-patient])
- Creating web page layout and design
- Writing a small block of code to do a specific, well-defined task, while supported by carefully designed [unit tests][unit-tests]
- Applying well-documented programming APIs to perform a specific task, especially a Python or REST API

[matchminer-patient]: https://github.com/sumedhasaxena/matchminer-patient
[unit-tests]: https://www.dataquest.io/blog/unit-tests-python/

### Best practices

- Remember that *you* are reponsible for *your* work
- Declare any use of GenAI
- Keep a draft of your work before polishing it with GenAI
- Fact check *everything* produced by GenAI, *comprehensively*, not selectively or randomly
- Use the appropriate tone for the intended purpose of the writing; scientific writing should not read like casual writing
- Avoid sounding like GenAI with the excessive use of em dashes and certain phrases

## Poor applications

GenAI tools are deficient in logical reasoning, critical thinking, and factual communication, so you should avoid using 
GenAI for applications that require these skills.

| Applications | Weaknesses | Alternatives |
|--------------|------------|-------------|
| writing personal statements | insincerity, verbosity, and fabrication | write them yourself |
| fact checking and quality control | inaccuracy | do it yourself |
| data interpretation | absurdity | do it yourself |
| mathematical derivation | lack of rigor | SageMath or Wolfram One |

## Non-applications

| Non-Applications | Potential misconducts | Alternatives |
|------------------|----------------------|-------------|
| summarizing scientific papers | fact fabrication | just read the abstract |
| gathering data | data fabrication | use search engines |
| analyzing data | results fabrication | write the analysis code, possibly with some GenAI assistance |
| generating scientific images | [copyright violation][npg-policy] | use vector-based image generation tool (e.g. Affinity Designer, Biorender) |
| writing or drafting papers | [fact][fact-fab] and [citation][citation-fab] fabrication | write the paper yourself first and polish with GenAI |

[npg-policy]: https://www.nature.com/nature-portfolio/editorial-policies/ai#generative-ai-images
[fact-fab]: https://www.nature.com/articles/d41586-025-02906-y
[citation-fab]: https://hongkongfp.com/2025/12/18/university-of-hong-kong-professor-steps-down-from-associate-deanship-after-ai-generated-references-scandal/

## Other examples of misconducts

GenAI misconducts that are easiest to identify involve fabricating facts and citations.

In the legal field, many lawyers have been fired or sanctioned due to fabricating citations,
while using GenAI
(e.g. in
[Colorado](https://www.businessinsider.com/young-lawyer-fired-using-chatgpt-job-work-hallucinations-errors-2023-11),
[New York](https://www.reuters.com/legal/new-york-lawyers-sanctioned-using-fake-chatgpt-cases-legal-brief-2023-06-22/),
[Utah](https://www.theguardian.com/us-news/2025/may/31/utah-lawyer-chatgpt-ai-court-brief),
[Australia](https://www.theguardian.com/law/2025/sep/03/lawyer-caught-using-ai-generated-false-citations-in-court-case-penalised-in-australian-first),
[Singapore](https://www.channelnewsasia.com/singapore/lawyer-ordered-pay-800-opposing-cite-fictitious-authority-gen-ai-5381241)
.)

In science, the repercussions of GenAI misconducts are, in fact, even higher. Science is built on a foundation of trust, and
when that trust is eroded, it is nearly impossible to re-gain it. Think about it, when you read a scientific paper,
how do you really know that the reported results are not completely fabricated?

## Bottom line

Fabrication, plagiarism, and copyright violation are all serious misconducts, whether you use GenAI or not.
GenAI just makes it easier for you to commit these misconducts.
