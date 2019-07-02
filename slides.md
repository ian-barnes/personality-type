---
title: Personality type & software development
theme: moon
revealOptions:
  transition: 'none'
css: slides.css
---

## Personality type, software development and computing education

---

"Perl was created for someone like you,by someone like you, with the
collaboration of many other someones like you.

&mdash; Larry Wall, in the
Introduction to *Learning Perl*

---

Not by or for anyone even remotely like me...

```perl
print((($line=join("",<>))=~s/.*\n/index($`,$&)>=$[?"":$&/ge&&$line));
```

```perl
print((($line=join("",<>))=~s/.*\n/index($`,$&)>=$[?"":$&/ge&&$line));
```

```perl
($l=join("",<>))=~s/.*\n/index($`,$&)>=$[||print$&/ge;
```

---

"Wanted: Young, skinny, wiry fellows not over 18. Must be expert riders willing
to risk death daily. Orphan preferred. Wages $25 per week."

&mdash; Pony Express advertisement, 1860

---

"We realize the skills, intellect and personality we seek are rare, and our
compensation plan reflects that. In return, we expect TOTAL AND ABSOLUTE
COMMITMENT to project success — overcoming all obstacles to create applications
on time and within budget."

&mdash; Software developer advertisement, 1995

---

- Stereotype of programmer: nerdy, socially awkward, working all night, fuelled
  by pizza and soft drinks...

- Students consistently rate computing jobs at the bottom of the list of career
  choices

- Worldwide shortage of programmers

- Serious gender imbalance: women even less attracted to programming than men

---

## Questions

- Why are so few people attracted to programming?

- What sort of people are attracted to programming?

- Do the stereotypes put people off?

- Is there something about the way programming is taught that puts people off?

Note: Software development doesn't just need hard-core coding skills &mdash; is
programming turning away people who would otherwise have good careers as
analysts, designers, user-interface designers...?

---

## History of personality type

- Plato (c. 350 BC)

- Aristotle (c. 330 BC)

- Galen (c. 200 AD) "humours"

---

## The four humours

![The four humours (Image: Wikipedia)](https://upload.wikimedia.org/wikipedia/commons/a/a1/Humorism.svg)

---

## Humours and temperaments

| Humour | Season | Element | Organ | Qualities | Temperament | Characteristics |
|--------|--------|---------|-------|-----------|-------------|-----------------|
| Blood  | Spring | Air | Liver | Warm & moist | Sanguine | Courageous, Hopeful, Amorous |
| Yellow bile | Summer | Fire | Spleen | Warm & dry | Choleric | Angry, Bad tempered |
| Black bile | Autumn | Earth | Gall bladder | Cold & dry | Melancholic | Despondent, Sleepless, Irritable |
| Phlegm | Winter | Water | Brain/Lungs | Cold & moist | Phlegmatic | Calm, Unemotional |

---

## History

- Jung (1920) "Psychological type"

  - Only by understanding our differences can we get beyond intolerance and
    achieve respect and cooperation]

- Katherine Briggs & Isabel Briggs Myers (1962) "The Myers-Briggs Type Indicator"

  - Close to the spirit of Jung
  - Made it systematic

---

## The four axes

Introvert (I) vs Extrovert (E)

Sensate (S) vs Intuitive (N)

Thinker (T) vs Feeler (F)

Judger (J) vs Perceiver (P)

Note:

- Each is a continuum: preferences can be weak or strong
- None is good or bad

---

## Extroversion vs Introversion

| Extrovert (E)                  | Introvert (I)                        |
|---------------------------------|---------------------------------------|
| Expressive                      | Reserved                              |
| Energised by prolonged contact  | Drained...                            |
| Drained by time alone           | Engergised...                         |
| Speak before (or as) they think | Think before they speak               |
| External motivation             | Internal motivation                   |
| Process ideas by talking        | Can't process while anyone is talking |
| Need contact                    | Need time alone                       |

---

If their needs (for contact/solitude) are not met:

- E's become depressed
- I's become anxious, irritable and confused

Our culture was largely created by E's for E's: Extroversion is seen as
good/desirable, introversion as bad/shameful/something to be fixed

---

## Sensing vs Intuition

| Sensates (S)             | Intuitives (I)                                  |
|--------------------------|-------------------------------------------------|
| Observant / What *is*    | Imaginative / What could be                     |
| Body                     | Mind                                            |
| Quantitative             | Qualitative                                     |
| Experiment               | Theory                                          |
| Facts in the real world  | Theories, patterns, ideas                       |
| Attention to detail      | Bored by detail                                 |
| Not interested in theory | Facts are only interesting in context of theory |
| "Trees"                  | "Forest"                                        |

---

- There are more S's than N's in the world
- N's at their best: Einstein
- N's taken to an extreme: John Nash (A beautiful mind)

---

## Thinking vs Feeling

| Thinkers (T)       | Feelers (F)          |
|--------------------|----------------------|
| Tough-minded       | Friendly             |
| Objective          | Sympathetic          |
| Practical          | Personal             |
| "Get the job done" | That can feel brutal |
| Being right        | Values and feelings  |

---

- F's will compromise to avoid hurting someone's feelings
- Extreme T's will lose friends over arguments about trivia

- This is about how people instinctively make decisions
- This is the polarity with a strong gender bias

---

## Judging vs Perceiving

| Judgers (J)                  | Perceivers (P)                        |
|------------------------------|---------------------------------------|
| Scheduling / planning        | Looking around for alternatives       |
| Work steadily                | Work in bursts of creativity          |
| Love plans and stick to them | Can't stand plans                     |
| Feel lost without plans      | Feel trapped by plans                 |
| Hate to change plans         | Prefer to be flexible                 |
| Like to make decisions early | Put off decisions as long as possible |

---

- According to J's, they are organised while P's are chaotic
- According to P's, they are flexible while J's are rigid

---

## The 16 types

|                 |                |                 |                    |
|-----------------|----------------|-----------------|--------------------|
| ISTJ Inspector  | ISFJ Protector | INFJ Counsellor | INTJ Mastermind    |
| ISTP Crafter    | ISFP Composer  | INFP Healer     | INTP Architect     |
| ESTP Promoter   | ESFP Performer | ENFP Champion   | ENTP Inventor      |
| ESTJ Supervisor | ESFJ Provider  | ENFJ Teacher    | ENTJ Field Marshal |

---

## The four temperaments revisited

- SJ Melancholic / "Guardian": ISTJ, ISFJ, ESTJ, ESFJ
- SP Sanguine / "Artisan": ISTP, ISFP, ESTP, ESFP
- NF Choleric / "Idealist": INFJ, INFP, ENFJ, ENFP
- NT Phlegmatic / "Rationalist": INTJ, INTP, ENTJ, ENTP

---

## Frequencies of the preferences

|                  |                  |
|------------------|------------------|
| Extrovert 45-53% | Introvert 47-55% |
| Sensate 66-74%   | iNtuitive 26-34% |
| Thinker 40-50%   | Feeler 50-60%    |
| Judger 54-60%    | Perceiver 40-46% |

Note: This data is for the US. Frequencies might be different in other
countries.

Source: <http://www.capt.org/mbti-assessment/estimated-frequencies.htm>

---

## Frequencies of the types

|             |            |           |           |
|-------------|------------|-----------|-----------|
| ISTJ 11-14% | ISFJ 9-14% | INFJ 1-3% | INTJ 2-4% |
| ISTP 4-6%   | ISFP 5-9%  | INFP 4-5% | INTP 3-5% |
| ESTP 4-5%   | ESFP 4-9%  | ENFP 6-8% | ENTP 2-5% |
| ESTJ 8-12%  | ESFJ 9-13% | ENFJ 2-5% | ENTJ 2-5% |

Source: <http://www.capt.org/mbti-assessment/estimated-frequencies.htm>

---

## Frequencies for software developers

|                | Software developers | General population |
|----------------|---------------------|--------------------|
| Introverts (I) | > 50%               | about 50%          |
| Thinkers (T)   | 80-90%              | < 50%              |
| Intuitives (N) | about 50%           | 25-34%             |
| ISTJ           | 25-40%              | 11-14%             |

---

## Internal Google study

"... top three MBTI types: 23.6% are INTJ, 12.5% are ENTJ, and 10.7% are INTP.
The general population is 3% INTJ, 3.5% ENTJ, and 4% INTP."

---

## How does this relate to computing?

---

## Sensing vs iNtuiting

- Tools, including languages, need to be adapted to the user
- Perl was created by an S for other S's
- Eiffel was created by an N for other N's
- Design vs implementation

---

## Perceiving vs Judging

- Traditional software engineering processes were created by J's
- CMM: Organisations need J's to get to Level 3, but then can't get beyond that
- Extreme programming & other agile methods: Process for P's?

---

## Feeling vs Thinking

- Correctness: Need T's (F's may feel bad about finding or reporting other
  people's bugs)
- Teamwork: need F's (T's may tend to offend their team-mates)
- Client interaction: need F's, or well educated / trained T's

---

## Introvert vs Extrovert

- Physical environment (e.g. cubicles, shared offices) Introverts need solitude
- Interaction with colleagues (e.g. long meetings are impossible for introverts)
- Computer interface
- Interaction with clients

---

## Type in computing education

Perceiving vs Judging:

- It may not help to force "rigid" J methods on all students

Feeling vs Thinking:

- It might help to balance types in groups for team projects

Sensing vs iNtuiting:

- To S's, learning = memorising: "Understanding? What does that even mean?"

- Most computing students are S's / Most lecturers are N's (?)

- Can programming language choice influence the way students think about
  programming?

---

## More thoughts

- Soft skills vs hard skills: don't want to put off F's in early stages of a
  course &mdash; will need them later
- Maturity can mean being able to choose how to act (from either side of a
  polarity), in other words transcending type
- When stressed, people can sometimes act as their opposite (e.g. N acts like an
  S, I acts like an E), but generaly not effectively
- How does gender stereotyping fit with all this?

---

## Further reading

1. Steve McConnell, "Orphans Preferred", (Chapter 7 of *Professional Software
   Development*, Boston: Addison-Wesley, 2004). Available online at:
   <https://www.gamasutra.com/view/feature/131820/orphans_preferred.php>

2. Gerald Weinberg, *Quality Software Management*, Volume 3: *Congruent
   Action* (New York: Dorset House, 1994).

---

## Want to know your type?

<https://keirsey.com/>
