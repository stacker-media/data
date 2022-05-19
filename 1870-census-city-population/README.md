**Description**

This dataset is a transcribed version of the data from Table XXV of the Ninth Census of the United States, completed in 1870, and contains a breakdown of city population data. The original PDF version of this data is available through the U.S. Census Bureau and can be found [here](https://www2.census.gov/library/publications/decennial/1870/population/1870a-58.pdf). Though this data was previously very difficult to analyze due to the poor quality of the PDF and the unusual formatting, it is now publicly available and can be used to explore how metropolitan areas have grown and changed during the last 150 years. Consider diving into a single state for a granular approach, or examining how the working population of a region in 1870 has influenced the economy there today.

**Methodology**

To transcribe the data, Stacker staff first used [Amazon Textract](https://aws.amazon.com/textract/). This returned a typewritten dataset in CSV format, but contained some gaps, errors, and unusual formatting due to the double columns on the PDF pages. This base transcription was reformatted, corrected, and checked by hand, resulting in this final product.

**Keep in touch**

This is the fourth in a series of &quot;Stacker Data Drops&quot; where we&#39;ll help journalists tell stories about their local communities. To be alerted whenever we drop a new dataset, sign up [here](https://stackerdata.umso.co/).

**About Stacker**

[Stacker](http://www.stacker.com/) is a newswire on a mission to produce and distribute engaging data journalism to the world&#39;s news organizations. Founded in 2017, Stacker combines data analysis with rich editorial context, drawing on authoritative sources and subject matter experts to drive storytelling. We operate a free newswire for local journalists who can syndicate - or remix - stories to their readers. If you&#39;re interested in becoming a Stacker Publishing Partner, contact Ken Romano at [kromano@stacker.com](mailto:kromano@stacker.com). You can also review our Editorial Standards [here](https://stacker.com/editorial-standards).

**Dictionary**

The dataset includes 10 columns and 1,547 rows. The columns are variables that describe the city, township, or other civil division. All are listed below with descriptions where necessary. The rows are the individual civil divisions.

1. Civil Divisions: name of the city, township, or otherwise classified civil division
2. All ages Total: total population of the civil division
3. All ages Male: total male population of the civil division
4. All ages Female: total female population of the civil division
5. 5 to 18 Male: male population of the civil division, ages 5-18
6. 5 to 18 Female: female population of the civil division, ages 5-18
7. 18 to 45 Male: male population of the civil division, ages 18-45
8. 21 and upward Male: male population of the civil division, ages 21 and up
9. State: state or territory where the civil division is located
10. County: county where the civil division is located
