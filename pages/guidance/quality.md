---
icon: lucide/scan-eye
---

# Quality Guidelines

## The Four Rules

### 1. Prefer papers from **top conferences** { .lighter-h }

These are conferences ranked A or above by ICORE. For security, these are mainly:

- ACM Conference on Computer and Communications Security (CCS) - A*
- IEEE Symposium on Security and Privacy (S&P) - A*
- USENIX Security Symposium (USENIX Security) - A*
- Network and Distributed System Security Symposium (NDSS) - A*
- Advances in Cryptology (CRYPTO) - A*
-  International Conference on the Theory and Application of Cryptographic Techniques (EuroCrypt) - A*
- ACM Asia Conference on Computer and Communications Security (AsiaCCS) - A
- IEEE European Symposium on Security and Privacy (EuroS&P) - A
- Symposium On Usable Privacy and Security (SOUPS) - A

For the full list of security conferences, <a href="https://portal.core.edu.au/conf-ranks/?search=4604&by=all&source=ICORE2026&sort=arank&page=1" target="_blank">search for the *field of research* (FoR) code "4604"</a> on the ICORE Conference Portal.

B-level conferences may be acceptable if you have read a substantial portion of the paper and you are confident in your assessment of its quality. See [Rule 4:lucide-chevron-down:](#4-assess-the-paper-directly-yourself).

### 2. If selecting a journal paper, check the **journal's reputation** { .lighter-h }

Journals are less preferred in computer science because almost everyone publishes at conferences. However, there are occasionally some gems to be found.

Reviews in particular are well-suited to the reading group setting as they may present a general overview of an unfamiliar topic, and these are usually published in journals. However, many bad review articles also exist, so please read at least a few sections before nominating such a paper.

The main metric for journal reputation is the <a href="https://www.scimagojr.com/journalrank.php?area=1700" target="_blank">SCImago ranking</a>. Prefer journals ranked as Q1. Papers from a journal ranked Q2 may be acceptable if you have performed a thorough assessment of quality. See [Rule 4:lucide-chevron-down:](#4-assess-the-paper-directly-yourself).

### 3. Make sure the venue and publisher are **non-predatory** { .lighter-h }

Predatory venues exploit the &ldquo;publish or perish&rdquo; culture in academia and will accept nearly any paper for the right fee. There are many, many such venues. Just because a conference has a big-name publisher like IEEE or ACM does not mean it has acceptable peer review standards.

??? warning "IEEE venues"

    IEEE in particular seems to have a substantial problem with small fraudulent venues exploiting its name and reputation. There are countless articles on IEEE Xplore which aren't worth the digital paper they are printed on. It is the publisher with the most articles flagged by the <a href="https://www.irit.fr/~Guillaume.Cabanac/problematic-paper-screener" target="_blank">Problematic Paper Screener</a> by a wide margin **across all disciplines** (not just computer science and electronics engineering).

    See:

    - Frederik Joelving, &ldquo;<a href="https://retractionwatch.com/2023/06/15/plague-of-anomalies-in-conference-proceedings-hint-at-systemic-issues/" target="_blank">Plague of anomalies in conference proceedings hint at ‘systemic issues’</a>&rdquo;, _Retraction Watch_, 15 June 2023.
    - W. Swart, G. Cabanac, O. Fraisier-Vannier and G. Hubert, &ldquo;How a Tortured Conference Becomes a Series: An Analysis of Conference Manipulations&rdquo;, _2025 ACM/IEEE Joint Conference on Digital Libraries (JCDL)_, Dekalb, IL, USA, 2025, pp. 11-19, doi: <a href="https://doi.org/10.1109/JCDL67857.2025.00012" target="_blank">10.1109/JCDL67857.2025.00012</a>.

This should not be a concern if you stick to the top conferences and journals. However, sometimes good papers can be found at smaller and newly-established venues. When considering a paper from one of these venues, check if the venue has been assessed by the <a href="https://kanalregister.hkdir.no/en" target="_blank">Norwegian Register</a> or the <a href="https://jfp.csc.fi/jufoportal" target="_blank">Finnish Publication Forum</a>. A level of 1 or higher indicates that the venue meets basic academic and peer review standards.

There are certain publishers which are known for their questionable venues, most of which you should avoid entirely. These include:

- <a href="http://www.scirp.org" rel="nofollow noreferrer" target="_blank">Scientific Research Publishing</a> (SCIRP)
- <a href="http://www.mdpi.com" rel="nofollow noreferrer" target="_blank">Multidisciplinary Digital Publishing Institute</a> (MDPI) &#42;&#42;
- <a href="http://www.iaria.org" rel="nofollow noreferrer" target="_blank">International Academy, Research, and Industry Association</a> (IARIA)
- <a href="http://eai.eu" rel="nofollow noreferrer" target="_blank">European Alliance for Innovation</a> (EAI)
- <a href="http://www.wseas.org" rel="nofollow noreferrer" target="_blank">World Scientific and Engineering Academy and Society</a> (WSEAS)

No exhaustive catalog of predatory publishers exists, but you can check <a href="https://beallslist.net/" target="_blank">Beall's List</a>. Note that the absence of a publisher on this list does not mean it's non-predatory.

<small>&#42;&#42; MDPI is highly contentious, largely because of their quick turnaround for reviews. Some argue this is just due to their unique business model. On the other hand, many of their venues have recently been downgraded to level zero by the Finnish Publication Forum. If you choose an MDPI paper, please take extra care in your due diligence.</small>

### 4. Assess the paper **directly** yourself { .lighter-h }

Unfortunately, things like venue rating are merely *indicators* of quality and are not definitive. Just as there are good papers at unknown venues, there are bad ones to be found at major ones.

You can check a paper against the <a href="https://www.irit.fr/~Guillaume.Cabanac/problematic-paper-screener" target="_blank">Problematic Paper Screener (PPS)</a>, and see if there are any comments about the paper on <a href="https://pubpeer.com/" target="_blank">PubPeer</a>. Be aware, however, that the PPS only checks for certain classes of quality issues. Similarly, you cannot expect that all poor-quality papers will have been noticed by a PubPeer user.

At the end of the day, you will have to make an assessment about the paper yourself. Even if you are trying to make a quick judgement, you should read the introduction and one other section at the least&mdash;and don't just skim read. Note that the abstract is the most visible part of the paper and so red flags will often be elsewhere.

Some things to consider:

- How many authors are listed? In most fields you can expect to see a small handful. A dozen or more might indicate a problem. (There are exceptions, e.g., large author lists are sometimes seen on AI papers.)
- Do the figures/diagrams/tables appear to make sense?
- What is the main contribution of the paper? Does it appear to be substantial?
- Is the text written well? Or are there issues with spelling, grammar, sentence structure, formatting, etc. which are obvious even on a first read-through?
- If the paper is difficult to read, is it because the area is unfamiliar? Or, do you think it might be to obscure the weaknesses of the paper?
- Of the referenced sources, which appear to be the most foundational? Look up their DOIs. Do the papers appear reputable? Is there evidence the authors have engaged deeply with these sources?

The more "fringe" its venue, the more diligent you should be when assessing the quality of a paper.

## Automated Checker

Many of the checks mentioned above can be done in a single step by running your paper through <a href="https://litmus.snyman.ca" target="_blank">Litmus</a>. Give it a paper's DOI and it will tell you the venue's ICORE, SCImago, Norwegian and Finnish ratings, find relevant corrections, retractions and expressions of concern issued by the publisher, and check the paper itself for common issues.
