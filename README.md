# Analyzing First Street Foundation's flood insurance data and ZCTA characteristics

Story with Rebecca Hersher and Sophia Schmidt https://www.npr.org/2021/02/22/966428165/a-looming-disaster-new-data-reveal-where-flood-damage-is-an-existential-threat

First Street Foundation shared with NPR data about the cost of structural damage that are project to do to flood-prone properties on the zip code level.

Their national report with methodology and data overview published on Feb. 22nd.https://firststreet.org/flood-lab/published-research/highlights-from-the-cost-of-climate-americas-growing-flood-risk/

Here's where they host the datasets https://registry.opendata.aws/fsf-flood-risk/

Structural damage of homes is measured by average annualized loss, or AAL. Here is their paper detailing how they assessed AAL https://www.mdpi.com/2225-1154/8/10/116/htm.

Flood prone properties are properties that have 1/100 FF, which is FSF’s assessment of risk for 100 year floods.

The flood prone properties at 60% of the zctas currently are not paying as enough premium to cover their AAL in aggregate, and since they are the accepted insurance pool of the national flood insurance program, we want to know what’s different about the communities where the properties are getting the better and worse deals. A fair deal is when AAL equals the yearly flood insurance premium; a good deal is when AAL>flood insurance premium, and a bad deal is when AAL< flood insurance premium.

The analysis is presented in Jupyter Notebook 20210301_nfip_fsf_analysis and datasets used at the time of publication are in the folder.
