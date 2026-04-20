# tutorials-and-talks
This project contains continuing professional development (CPD) training and talks about topics in data science and visualization, which I have given.
There are also links to some additional resources.
Feel free to contact me via LinkedIn (www.linkedin.com/in/roy-ruddle-9973457b) if you would like to attend any of the events the next time they run, or would like to discuss some bespoke training or talk.
See my website (https://raruddle.wordpress.com/) for lots more information.

## Resources
The **[6-step Data Quality Method](https://github.com/royruddle/6-step-data-quality-method)** that describes 69 data quality/profiling tasks in plain English, with a downloadable Excel checklist. The tasks are grouped into these six recommended steps:
1. Is anything obviously wrong (look at your data and any documentation)?
2. Watch out for special values
3. Is any data missing?
4. Check each variable
5. Check combinations of variables
6. Profile the cleaned data

Software:
- The **ACE** interactive set visualization software (written in Java; https://doi.org/10.5518/1150), which we used with epidemiologists and NHS Digital to gain new insights into [patterns of missing data in a large hospital dataset](http://dx.doi.org/10.1136/bmjopen-2022-064887).
- The **setvis** Python package (https://pypi.org/project/setvis/), which has similar functionality to ACE for general purpose set visualization, works with in-memory datasets and PostgresSQL databases, and is [very memory efficient](https://joss.theoj.org/papers/10.21105/joss.06925).
- The **vizdataquality** Python package (https://pypi.org/project/vizdataquality/), which implements the above [6-step method for efficiently and rigorously investigating data quality](https://github.com/royruddle/6-step-data-quality-method), and helps you to visually document your investigations as a webpage, in Latex or Word.

A 22-minute film called **Visualizing the Quality of Data** (https://www.youtube.com/watch?v=PnNMfCRWL7k)

## Data visualization masterclass

This 1-hour talk will teach you about different types of chart and visual encoding, common mistakes people make and when to break the rules. By attending you will learn how to choose good visualizations designs, to analyse and present your data effectively. Some of the examples use [vizdataquality](https://pypi.org/project/vizdataquality/). You may download a [summary of the mistakes, tips and rule-breaking](https://github.com/royruddle/tutorials-and-talks/blob/main/viz_masterclass/viz_masterclass_summary.pdf).

Previous dates:
- 14th March 2025, University of Leeds, Leeds, UK (hybrid)
- 18th November 2025, University of Leeds, Leeds, UK (hybrid)

Next date:
- TBC


## Talks about data quality

Do you know that there are more than 100 ways in which data can be of ``low'' quality?
That is one reason why data preparation often takes more than half of a data science project’s time.
Through 10+ year's of research, I have developed a method and software (see *Resources*) for investigating data quality in an efficient yet rigorous manner.
I have also given a number of talks about investigating data quality, including:
- How good is my data and how can I check it? 6th October 2020 (industry organised hackathon) and 21st July 2020 (LIDA-Alan Turing Institute Data Centre Collaboration Event).
- How can you rigorously profile and investigate the quality of your data? 14th March 2024 (Consumer Data Research Centre), 15th May 2024 (LIDA Data Scientist Development Programme), 18th June 2024 (Alan Turing Institute tech talk)
- New perspectives on data science for business, 22nd September 2025, Leeds Digital Festival, Leeds, UK (in-person). This talk's aim was to ``open your eyes about the many ways your data might be `wrong' and describe six steps for rigorously and efficiently checking data quality'', showcasing the [6-step Data Quality Method](https://github.com/royruddle/6-step-data-quality-method).
- How should I investigate data? In this tech talk I demonstrated the openly available [6-step Data Quality Method](https://github.com/royruddle/6-step-data-quality-method) and associated [vizdataquality Python package](https://pypi.org/project/vizdataquality/).
  - 30th September 2025, Leeds Data Science Meetup/Digital Festival, Leeds, UK (in-person).
  - 29th January 2026, North East Data Scientsts Meetup, Newcastle, UK (in-person). [Slides](https://github.com/royruddle/tutorials-and-talks/blob/main/data_quality_talks/how_should_i_investigate_data_2026_2x2.pdf).
  - 2nd April 2026, Nottingham DS & AI Meetup, UK (in-person).

Next dates:
- 23rd April 2026, online talk for RSS Manchester local group [register](https://rss.org.uk/training-events/events/events-2026/local-groups/data-quality-how-to-save-time-and-simultaneously-i/)
- 28th April 2026, RSS Glasgow local group [register](https://rss.org.uk/training-events/events/events-2026/local-groups/a-practical-guide-to-characterising-data-and-inves/)
- 20th May 2026, [Digital Footprints 2026](https://store.leeds.ac.uk/conferences-and-events/environment/geography/df26-digital-footprints-2026), York, UK
- 26th June 2026, [Datalyst 2026](https://www.eventbrite.co.uk/e/datalyst-2026-tickets-1982878006495?aff=oddtdtcreator&keep_tld=true), Newcastle, UK

## Training workshop: Data quality

In this 1-day interactive course you will learn the why, what, when and how of investigating data quality. You will put your knowledge into practice in a series of challenges that cover tabular, spatial and longitudinal data. The workshop follows the [6-step Data Quality Method](https://github.com/royruddle/6-step-data-quality-method), using [vizdataquality](https://pypi.org/project/vizdataquality/) and other software to provide solutions to the challenges. The workshop objectives are:
-	To understand the range of tasks you need to perform to investigate data quality
-	To learn about computational and visualization techniques you can use
-	To gain experience of an efficient and rigorous workflow
-	To learn how to communicate your findings

**Is this workshop for me?** The workshop is open to everyone, irrespective of your level of knowledge about data quality. However, you will get the most out of the course if you have familiarised yourself with the [6-step Data Quality Method](https://github.com/royruddle/6-step-data-quality-method), which was written by a team that I led.
No prior technical knowledge is assumed for this workshop.
You may use any software for the practical work and you need to bring a laptop to use for that practical work, with the software installed.

Previous dates:
- 2nd April 2025, University of Leeds, Leeds, UK (in-person)
- 12th December 2025, University of Leeds, Leeds, UK (in-person)

Next dates (one-day courses, starting 09:30 and ending 16:30; [book here](https://store.leeds.ac.uk/conferences-and-events/faculty-of-medicine-health/lida-leeds-institute-for-data-analytics)):
- 28th May 2026, Edinburgh, UK
- 15th June 2026, Manchester, UK
- 16th June 2026, Birmingham, UK
- 23rd June 2026, London, UK

## Training workshop: Visualization for explainable AI (XAI)

This half-day workshop was developed by the Making Visualization Scalable (MAVIS) for explaining machine learning classification models project (https://gtr.ukri.org/projects?ref=EP%2FX029689%2F1).
The learning objectives were for attendees to understand: (1) How XAI requirements vary across stakeholders, (2) How visualization is used in XAI, (3) The types of issue and blooper that occur in XAI visualization, and (4) Scalability – how to make visualization effective for large/complex models.

Here are some of the workshop materials:
- [Taxonomy of XAI tasks and questions](https://github.com/royruddle/tutorials-and-talks/blob/main/xai_visualization_tutorial/XAI_tasks_and_questions.pdf)
- [References](https://github.com/royruddle/tutorials-and-talks/blob/main/xai_visualization_tutorial/XAI_viz_references.pdf)

**Is this workshop for me?** The workshop is open to everyone, irrespective of their level of knowledge about XAI and visualization.

Previous dates:
- 7th October 2025, University of Leeds, Leeds, UK (in-person)
- 3rd November 2025, IEEE VIS Conference, Vienna, Austria (in-person)

Next date:
- EuroVis 2026 conference, Nottingham, UK (in-person). Exact date TBC.

I also give short talks about Visualization for Explainable AI, based on the tutorial's content. E.g., at the N8 Universities' [Best Practices in AI](https://rse.shef.ac.uk/events/seminar-2025-11-11-best-practices-in-ai-afternoon-2.html) event on 11th November 2025.

## Training workshop: Tableau visualization

This 1-day interactive workshop provides a practical introduction to data visualization with Tableau Desktop, an industry-leading visualization tool. You will learn how to create effective visualizations by avoiding common mistakes and how to use Tableau by creating visualizations that range from bar and line charts to heat maps and geographic maps. You’ll then have the opportunity to apply your knowledge by tackling a series of data analysis ‘challenges’.

**Is this workshop for me?** No prior knowledge is assumed, other than having basic IT skills. However, you will get the most out of the workshop if you complete in advance Tableau's *Get Started* tutorial (https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-home.htm).

Previous dates:
- 8th February 2017, University of Leeds, Leeds, UK (in-person)
- 14th February 2018, University of Leeds, Leeds, UK (in-person)
- 27th February 2019, University of Leeds, Leeds, UK (in-person)
- 13th September 2019, Alan Turing Institute, London, UK (in-person)
- 2nd March 2020, University of Leeds, Leeds, UK (in-person)
- 17th March 2021, University of Leeds, Leeds, UK (online)
- 28th April 2022, University of Leeds, Leeds, UK (online)
- 28th April 2023, University of Leeds, Leeds, UK (in-person)
- 7th June 2024, University of Leeds, Leeds, UK (in-person)
- 30th May 2025, University of Leeds, Leeds, UK (in-person)
- 5th February 2026, University of Leeds, Leeds, UK (in-person)

Half-day versions of this workshop were run for the *Leeds Data Science Society* on 15th November 2017, 11th June 2018 (twice), 13th March 2019 (twice) and 11th March 2020.
