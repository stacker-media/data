<p><strong><span><span><span><span><span><span>Description</span></span></span></span></span></span></strong></p>

<p><span><span><span><span><span><span>Stacker brought together data from the Federal Emergency Management Agency’s National Risk Index and the National Register of Historic Places to identify historic sites located in high risk regions for flooding.</span></span></span></span></span></span></p>

<p><span><span><span><strong><span><span>Methodology</span></span></strong></span></span></span></p>

<p><span><span><span><span><span><span>Our dataset merges the </span></span></span></span></span></span><a href="https://www.fema.gov/sites/default/files/documents/fema_national-risk-index_technical-documentation.pdf"><span><span><span><span><span><span><span><span>National Risk Index</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span> from FEMA with the </span></span></span></span></span></span><a href="https://www.nps.gov/subjects/nationalregister/index.htm"><span><span><span><span><span><span><span><span>National Register of Historic Places</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span> to identify historic buildings, sites, and districts located in census tracts considered to be at very high or relatively high risk for coastal or riverine flooding. FEMA cited geospatial data, historic occurrence data, and machine-learning models to estimate disaster risk for communities across the U.S.; Stacker looked at what this means for historic areas in at-risk regions.&nbsp;</span></span></span></span></span></span></p>

<p><span><span><span><span><span><span>There are more than 96,000 listings on the National Register. Our analysis focuses on 8,739 of those listings: sites, buildings, and districts categorized as nationally significant. </span></span></span></span></span></span><a href="https://stacker.com"><span><span><span><span><span><span><span><span>Stacker</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span> used longitudinal and latitudinal data provided by the National Register and reverse-geocoded the location data through the </span></span></span></span></span></span><a href="https://www.fcc.gov/census-block-conversions-api"><span><span><span><span><span><span><span><span>FCC’s census block API</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span> to determine which census tract each is located in. Stacker then filtered the merged data to only include sites located in either high risk or relatively high risk for coastal or riverine flooding. In addition to republishing Stacker’s accompanying story, journalists can expand upon the raw data in the following ways:</span></span></span></span></span></span></p>

<ul>
	<li><span><span><span><span><span><span>Search for any trends in the types of historic sites in high flood risk areas. The National Register lists areas of significance for most sites and additionally highlights whose history the site is particularly relevant to (military, Black, government, etc.).</span></span></span></span></span></span></li>
	<li><span><span><span><span><span><span>Dive more deeply into specific historic sites on the list. Has the site already experienced flooding? Are there resiliency plans in place?</span></span></span></span></span></span></li>
</ul>

<p><span><span><span><strong><span><span>Keep in touch</span></span></strong></span></span></span></p>

<p><span><span><span><span><span><span>This is the second in a series of "Stacker Data Drops" where we'll help journalists tell stories about their local communities. To be alerted whenever we drop a new dataset, sign up </span></span></span></span></span></span><a href="https://stackerdata.umso.co/"><span><span><span><span><span><span><span><span>here</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span>.</span></span></span></span></span></span></p>

<p><span><span><span><strong><span><span>About Stacker</span></span></strong></span></span></span></p>

<p><a href="http://www.stacker.com/"><span><span><span><span><span><span><span><span>Stacker</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span> is a newswire on a mission to produce and distribute engaging data journalism to the world's news organizations. Founded in 2017, Stacker combines data analysis with rich editorial context, drawing on authoritative sources and subject matter experts to drive storytelling. We operate a free newswire for local journalists who can syndicate - or remix - stories to their readers. If you're interested in becoming a Stacker Publishing Partner, contact Ken Romano at kromano@stacker.com. You can also review our Editorial Standards </span></span></span></span></span></span><a href="https://stacker.com/editorial-standards"><span><span><span><span><span><span><span><span>here</span></span></span></span></span></span></span></span></a><span><span><span><span><span><span>.</span></span></span></span></span></span></p>

<p><span><span><span><strong><span><span>Dictionary</span></span></strong></span></span></span></p>

<ul>
	<li>Ref#:&nbsp;Nation Register for Historic Places ID</li>
	<li>Property Name:&nbsp;Name of historic site/building/district</li>
	<li>State:&nbsp;State</li>
	<li>County: County</li>
	<li>City: City</li>
	<li>Street &amp; Number: Address</li>
	<li>Listed Date:&nbsp;Date added to registry</li>
	<li>Area of Significance:&nbsp;Category of historical significance</li>
	<li>geometry: Latitude and longitude coordinates</li>
	<li>longitude: Longitude</li>
	<li>latitude: Latitude</li>
	<li>fipsBlock:&nbsp;Census Block Group FIPS code for site's location</li>
	<li>fipsTract:&nbsp;Census Tract FIPS code for site's location</li>
	<li>STCOFIPS:&nbsp;State/county FIPS code for site's location</li>
	<li>CFLD_AFREQ:&nbsp;Average number of recorded Coastal Flooding hazard occurrences (event-days) in census tract per year over the period of record (24 years) (from National Risk Index)</li>
	<li>CFLD_RISKS:&nbsp;Numerical score of coastal flood risk</li>
	<li>CFLD_RISKR:&nbsp;Rating of coastal flood risk</li>
	<li>RFLD_AFREQ: Average number of recorded Riverine Flooding hazard occurrences (event-days) in census tract per year over the period of record (24 years) (from National Risk Index)</li>
	<li>RFLD_RISKS:&nbsp;Numerical score of riverine flood risk</li>
	<li>RFLD_RISKR:&nbsp;Rating of coastal flood risk</li>
</ul>
