# ABA-EVIDENCE-MAP.md

Author: Kevin “Andie” Williams, with C (Claude)
Status: Draft v0.1 — unverified claims mapped, gaps named
Project: Tiny Door — You Have Another Option
Evidence standard: proof, not citation
See also: `rfc/proof-not-citation-standard.md`

-----

## Purpose

This file maps specific claims about ABA to the sources in REFERENCES.md.

For each claim it records:

- which sources in the current list touch it;
- what those sources actually prove;
- what they do not prove;
- how the claim should be worded in reader-facing prose;
- what is missing and must be found before the claim can be made.

The working rule is not what can be cited. It is what can be proved.

A source that touches a topic is not a source that proves a claim.
A source that proves a claim must be read, its actual content confirmed,
and its limitations named.

This map is not a proof store. It is a gap register and a scrutiny record.
It does not become a proof store until each entry has been verified and signed off.

-----

## Claim Status Key

|Status        |Meaning                                                                                       |
|--------------|----------------------------------------------------------------------------------------------|
|`PROVABLE`    |Source read, content confirmed, claim language calibrated to evidence                         |
|`SUPPORTABLE` |Source exists and is directionally relevant; language must be softened to match evidence level|
|`CONTESTED`   |Source exists but has methodological limitations that must be named in book                   |
|`THIN`        |Source is advocacy, journalism, or lay; not peer-reviewed; must be labeled as such            |
|`MISSING`     |No adequate source currently in REFERENCES.md; must be found before claim is made             |
|`WRONG SOURCE`|Source in list does not support this claim; must be corrected or removed                      |

-----

## Claim A: ABA shares developmental origins with conversion therapy for gay people

**Claim as currently implied in book:**
ABA and conversion therapy were developed by the same person using the same behavioral framework.

**Sources in current list:**

- Ref 127: Wikipedia — Ole Ivar Lovaas
- Ref 128: LA Times obituary
- Ref 129: crimeandjustice.org.uk — content unverified; URL suggests criminology journal but actual article not confirmed

**Status: SUPPORTABLE for historical fact / THIN for harm inference**

**What these sources prove:**
Lovaas worked on both interventions. The LA Times obituary is a published record.
Wikipedia is not a citable source but points toward primary sources.
The historical connection between ABA and aversion-based behavioral methods is
well-documented in the scholarly literature on behavior analysis history.

**What these sources do not prove:**
That modern ABA practitioners share Lovaas’s intentions.
That all current ABA is equivalent to conversion therapy.
That harm to Autistic people is equivalent in mechanism or severity to harm
documented in conversion therapy for LGBTQ+ people (though the argument has
been made and is worth naming).

**Book treatment:**

> “ABA was developed by the same researcher who also developed aversion-based
> behavioral interventions targeting gay men. The behavioral logic — extinguish
> unwanted behavior, reinforce desired behavior — is the same in both.”

This is supportable with the LA Times obituary and academic sources on Lovaas.
The word “same” requires precision: same researcher, same behavioral framework,
not necessarily same intent or same outcomes.

**Action required:**

- Confirm ref 129 content before citing.
- Add: Rekers & Lovaas (1974) is the primary source documenting both lines of work
  and is frequently cited in conversion therapy scholarship. Locate and read it.
- Add: Zucker (2008) or similar conversion therapy history source for framework comparison.

-----

## Claim B: ABA is legally classified as conversion therapy in some jurisdictions

**Claim as currently implied in book:**
Some laws banning conversion therapy explicitly cover ABA or ABA-style interventions.

**Sources in current list:**

- Ref 37: bornperfect.org — conversion therapy ban tracker (advocacy org)
- Ref 38: Victorian legislation (Change or Suppression Practices Prohibition Bill 2020)
- Ref 39: equality caucus country list
- Ref 140: Cambridge law journal — legal/clinical personhood for autistic and trans children in Ontario

**Status: SUPPORTABLE with jurisdiction precision / THIN without it**

**What these sources prove:**
Ref 38 is actual legislation. It can be cited directly for what the Victorian law
covers. Ref 140 is peer-reviewed legal scholarship making the ABA/conversion therapy
argument in a Canadian legal context.

**What these sources do not prove:**
That ABA is universally classified as conversion therapy.
That any US federal law classifies ABA this way.
That individual practitioners have been prosecuted under these laws.

**Book treatment:**

> “In at least one jurisdiction — Victoria, Australia — legislation banning
> conversion practices has been interpreted to cover behavioral interventions that
> suppress identity expression in autistic people. Legal scholars have made the
> same argument in Canadian courts.”

Do not write: “ABA is conversion therapy and is banned.” That is not what the
sources prove at this time.

**Action required:**

- Read ref 38 (Victorian bill) for exact definitional language before quoting it.
- Read ref 140 for the specific legal argument made and its outcome.
- Verify whether any US state ban explicitly names ABA.

-----

## Claim C: ABA causes PTSD or trauma symptoms in Autistic people

**Claim as currently implied in book:**
ABA exposure is associated with PTSD symptoms in Autistic people.

**Sources in current list:**

- Ref 55: embrace-autism.com — lay/advocacy website
- Ref 147: PMC7368197 — **WRONG SOURCE**

**Status: MISSING adequate peer-reviewed source / WRONG SOURCE identified**

**Critical error:**
Ref 147 (PMC7368197) does not support this claim. It is a 2020 PNAS article
about synaptic pruning in brain development (Sakai, 2020). It has no connection
to ABA or PTSD. This reference must be corrected or removed from any claim about
ABA harm.

**What ref 55 proves:**
Nothing at the peer-reviewed level. It is a lay summary on an advocacy website.
It may accurately represent the autistic community’s reported experience, but it
cannot carry a clinical claim.

**What is missing:**
The primary peer-reviewed source for this claim is:

> Kupferstein, H. (2018). Evidence of increased PTSD symptoms in autistic adults
> whose caregivers administered applied behavior analysis. *Advances in Autism*,
> 4(1), 5–14. <https://doi.org/10.1108/AIA-08-2017-0016>

**Status of Kupferstein (2018):** CONTESTED
This study is real peer-reviewed research published in a legitimate journal.
It found a correlation between ABA exposure and PTSD checklist scores in
retrospective self-report data. It has been widely cited by critics of ABA.

However, it has documented methodological limitations that must be named:

- Self-selected sample recruited through Autistic advocacy networks
- Retrospective self-report for both ABA exposure and PTSD symptoms
- No control for confounding variables (trauma history, diagnosis severity, etc.)
- Single study; not yet replicated

**Book treatment:**

> “At least one peer-reviewed study has found a correlation between ABA exposure
> and elevated PTSD symptoms in Autistic adults. The study’s methodology has been
> criticized, and it has not been replicated. Autistic adults have also reported
> these experiences in their own words, consistently and in large numbers.”

Do not write: “Research proves ABA causes PTSD.” The word “causes” requires
evidence that this single contested study does not provide.
Do write: survivor testimony is real evidence, clearly labeled as such.

**Action required:**

- Add Kupferstein (2018) to REFERENCES.md.
- Fix or remove ref 147.
- Search for any replication studies or systematic reviews citing Kupferstein.
- Consider adding: Devita-Raeburn (2016), The Atlantic, for journalistic
  documentation of the PTSD debate — labeled as journalism.

-----

## Claim D: ABA prioritizes compliance and behavioral appearance over wellbeing

**Claim as currently implied in book:**
ABA is structured to produce behaviors that look neurotypical, not to improve
autistic quality of life or self-determined wellbeing.

**Sources in current list:**

- Ref 135: Fortune (2022) — investigative journalism on ABA industry
- Ref 136: Forbes (2023) — journalism on ABA industry financial practices
- Ref 138: Frontiers in Psychiatry (2023) — peer-reviewed perspective on clinician
  autonomy and autistic client autonomy in mental health treatment
- Ref 141: Springer article — content unverified
- Refs 142–146: Advocacy and lived experience sources

**Status: SUPPORTABLE with correct source labeling**

**What these sources prove:**
Refs 135–136 document financial incentives within the ABA industry that critics
argue misalign practitioner motivation with client welfare. These are journalism,
not clinical trials, and should be labeled as investigative reporting.

Ref 138 (McVey et al., 2023, Frontiers in Psychiatry) is a peer-reviewed
perspective article arguing that autistic clients’ treatment autonomy is routinely
subordinated to caregiver preferences. It is not specific to ABA but is directly
relevant to the structural critique. It is a perspective article, not a trial —
this must be noted.

Refs 142–146 are advocacy sources and lived experience testimony. These are
legitimate forms of evidence for what autistic people report experiencing. They
should not be presented as clinical research.

**What these sources do not prove:**
That every ABA practitioner or program operates this way.
That compliance focus is unique to ABA versus other pediatric behavioral interventions.
That ABA outcomes data systematically measures compliance rather than wellbeing
(though critics make this argument — it needs a source if stated as fact).

**Book treatment:**

> “Autistic adults who experienced ABA as children have described it consistently
> as focused on making them appear less autistic rather than on reducing their
> distress or building their self-knowledge. Investigative reporting has documented
> financial structures within the ABA industry that critics say incentivize hours
> over outcomes. A 2023 peer-reviewed perspective in Frontiers in Psychiatry found
> that autistic clients’ own treatment goals are routinely overridden by caregiver
> preferences in mental health settings.”

**Action required:**

- Read and confirm ref 141 content before citing.
- Add: any peer-reviewed outcome study that measures ABA outcomes against
  self-determined wellbeing versus behavioral compliance. This is a known gap
  in the literature; naming that gap is itself an honest move.
- Consider: Bottema-Beutel et al. (2021) on outcome measurement in autism
  intervention research is relevant here.

-----

## Claim E: ABA practitioners are often undertrained relative to intervention intensity

**Claim as currently implied in book:**
The Registered Behavior Technician (RBT) credential requires minimal training
for a role that involves intensive, consequential behavioral intervention with
Autistic children.

**Sources in current list:**

- Ref 148: discoveryaba.com — average RBT salary
- Ref 149: NCES — education statistics
- Ref 150: psychcentral.com — mental health professional statistics
- Ref 151: thetreetop.com — ABA therapist demographics
- Ref 152: songbirdcare.com — RBT certification
- Ref 153: elemy.com — ABA therapist degree requirements
- Ref 154: edsource.org — teacher credential comparison (California)

**Status: PROVABLE for the credential facts / THIN for the harm inference**

**What these sources prove:**
The RBT certification requires 40 hours of training. This is a publicly documented
credentialing standard from the Behavior Analyst Certification Board (BACB).
The comparison to teacher credentialing requirements is factually supportable.

**What these sources do not prove:**
That low credentials cause harm.
That all RBTs are unprepared or harmful.
That BCBA supervision (required by the credential) is inadequate.

**Book treatment:**

> “A Registered Behavior Technician — the front-line provider in most ABA programs
> — can begin working with an Autistic child after 40 hours of training. A
> California teacher requires over 600 hours of supervised practice before
> independent licensure.”

This is a factual comparison. It supports a question — is this enough? — without
asserting a causal harm claim the data does not support.

**Action required:**

- Verify the 40-hour figure directly against BACB published credentialing standards.
  Use BACB.com as the primary source, not ABA industry websites.
- Add BACB as a direct source.

-----

## Claim F: ABA’s origins include aversive conditioning including electric shock

**Claim as currently implied in book:**
Early ABA used aversive interventions including electric shock.
Some programs continued using these methods into the recent past.

**Sources in current list:**

- Ref 126: docplayer — Lovaas interview (“A Conversation with Ivar Lovaas”)
- Ref 127: Wikipedia — Ole Ivar Lovaas
- Ref 128: LA Times obituary

**Status: PROVABLE for early history / requires temporal precision for recent history**

**What these sources prove:**
Lovaas used electric shock and aversive conditioning. This is documented in his
own published work and interviews. The LA Times obituary references this directly.
Ref 126 is a primary source — Lovaas in his own words — but its content must be
confirmed before quoting.

**What these sources do not prove:**
That current mainstream ABA uses electric shock.
The FDA banned the Graduated Electronic Decelerator (GED) device at the Judge
Rotenberg Center in 2020. That regulatory action is public record but is NOT
currently in REFERENCES.md.

**Book treatment:**

> “ABA’s founder used electric shock as an aversive stimulus. In his own words,
> he described it as a tool. Some programs continued using electric shock devices
> on autistic people until the FDA banned the practice in 2020.”

The 2020 date requires the FDA source. Do not write it without it.

**Action required:**

- Add: FDA (2020) final rule banning electrical stimulation devices for self-injurious
  or aggressive behavior. Available at FDA.gov.
- Confirm ref 126 content before quoting Lovaas directly.

-----

## Sources Requiring Content Verification Before Use

The following references are in REFERENCES.md but their actual content has not
been confirmed. Do not write claims based on these until they are read.

|Ref|URL                                                 |Reason for flag                                          |
|---|----------------------------------------------------|---------------------------------------------------------|
|126|docplayer.net/Lovaas-interview                      |Primary source claim depends on what he actually said    |
|129|crimeandjustice.org.uk                              |Journal article content unknown; URL alone proves nothing|
|130|onlinelibrary.wiley.com/doi/full/10.1002/jaba.768   |JABA article — may be ABA-favorable; read before citing  |
|141|link.springer.com/article/10.1007/s41252-021-00201-1|Content unverified                                       |

-----

## Sources That Must Be Added

|Claim                                      |Source to add                                       |Why                                                                 |
|-------------------------------------------|----------------------------------------------------|--------------------------------------------------------------------|
|ABA/PTSD association                       |Kupferstein (2018), *Advances in Autism*, 4(1), 5–14|Only peer-reviewed study directly measuring this; contested but real|
|ABA/conversion therapy framework comparison|Rekers & Lovaas (1974)                              |Primary source for both lines of Lovaas’s work                      |
|Electric shock ban                         |FDA (2020) final rule on GED device                 |Regulatory record for recent aversive use claim                     |
|Outcome measurement critique               |Bottema-Beutel et al. (2021)                        |Documents how ABA outcome research measures compliance proxies      |
|Conversion therapy legal classification    |Primary text of any US state ban                    |Verify whether any explicitly names ABA                             |

-----

## Sources That Must Be Corrected

|Ref|Current claim it is attached to|Actual content                                                            |Action                                           |
|---|-------------------------------|--------------------------------------------------------------------------|-------------------------------------------------|
|147|ABA/PTSD harm                  |Synaptic pruning in brain development (Sakai, 2020, PNAS) — no ABA content|Remove from ABA claim or replace with Kupferstein|

-----

## What This Map Is Not

This map does not settle the question of whether ABA harms Autistic people.

The evidence that it does — survivor testimony, the Kupferstein study, the
conversion therapy framework argument, the credential comparison, the financial
incentive documentation — is real and serious.

The evidence is also incomplete, contested, and in some places thin.

The book’s job is to hold both of those things at once:
to speak with teeth about what is documented,
and to speak with precision about what is not yet proved.

The reader deserves both.

-----

Status: Draft v0.1
Date: 2026-06-02
Next action: Verify flagged sources; add missing sources; update status column