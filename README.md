# Retail revenue dataset
This is the documentation for <a href="https://github.com/reschultzed/retailrevenue/blob/main/retailrevenue.csv"><b>retailrevenue.csv</b></a> and <a href="https://github.com/reschultzed/retailrevenue/blob/main/retailrevenue-trades.csv"><b>retailrevenue-trades.csv</b></a>, which together make up a thorough historical dataset of the annual revenues of the largest retailers in the United States.

<b>Uses</b>

The primary purpose of this dataset is to allow users to create historical rankings of the largest retailers in the United States, as well as to track changes over time in the financial situation of individual companies. With over 19,000 data points representing over 600 distinct companies in all sectors of the retail industry, extending from 1902 through 2022, the opportunities for comparison are immense.

<b>Rules for inclusion</b>

This is intended as a comprehensive dataset of the revenues of major retailers in the United States. A "major" retailer is defined as one which, at any point in its history, had an annual revenue of one billion United States dollars at the 2020 value, or the equivalent thereof when adjusted for inflation. However, not all listed companies meet this criterion, and some companies that do are not included because of the difficulty of identifying them. A "retailer" does not need to be a for-profit company, a publicly traded entity, or even a single corporation – for franchised retail chains operating under a single brand, systemwide revenues are used instead of the corporate income of the franchisor. The data includes companies based in the United States as well as the U.S. operations of companies based in other countries. Note that the data for U.S.-based companies includes their non-U.S. operations, while the data for non-U.S.-based companies does not.

<b>Companies, names, and continuity</b>

The name of the company referenced by each data point is included in the first column of the dataset. Since company names change over time, the <b>Lineage</b> column gives each company a short and consistent identifier that can be used to track the history of a company across years. As a result, the first column is able to also include brief parenthetical notes, indicating where necessary that a data point is estimated, that the figure has been converted from a non-U.S. currency, or that the retailer is a subsidiary of a non-retail company whose revenues are otherwise not listed.

The <b>retailrevenue-trades</b> dataset is included to further help with comparisons between companies across years. It lists mergers and splits involving the companies included in the dataset. This information is key for understanding why certain companies appear and disappear from the main dataset.

<b>Industry sectors and subsectors</b>

Each data point is categorized by the primary sector and subsector of the retail industry in which the company in question primarily operated at the relevant time. If a company operates in multiple sectors, the one which makes up the largest share of their revenue is used; if none of these distinct lines of business are significantly larger than the others, the data point is categorized as "Diverse". The categorization may change over time for a given company as its business model changes. Using this categorization system, the user can easily compare companies within similar lines of business, or exclude sectors from the ranking in accordance with varying definitions of what constitutes a retailer.

The seven primary sectors into which the data is categorized are as follows:
* <b>Catalog</b>, indicating retailers whose primary mode of business is selling goods outside of physical retail locations to be delivered to customers by mail. Subsectors are <b>Electronic</b> (covering e-commerce on the Internet and television shopping channels), <b>Mail order</b>, and <b>Showroom</b>.
* <b>Convenience</b>, indicating retailers that operate convenience stores, including sales of automobile fuel as well as merchandise. No subsectors are included.
* <b>General</b>, indicating general merchandise retailers. Subsectors are <b>Closeout</b> stores, <b>Department</b> stores, <b>Discount</b> stores, <b>Drugstore</b> and pharmacy stores, <b>Off-price</b> stores, <b>Rent-to-own</b> stores, <b>Variety</b> stores, <b>Wholesale club</b> and warehouse stores, and <b>Diverse</b> companies.
* <b>Grocery</b>, indicating retailers that primarily sell food intended to be prepared by the customer and consumed outside the premises. No subsectors are included.
* <b>Restaurant</b>, indicating businesses that primarily sell prepared food for immediate consumption. Subsectors are <b>Cafeteria</b>, <b>Dining</b> (covering restaurants that prioritize a formal sit-down dining experience), <b>Entertainment</b> (covering restaurants that specialize in additional entertainment experiences), <b>Fast casual</b>, and <b>Fast food</b>.
* <b>Specialty</b>, indicating traditionally formatted retailers that specialize in a particular type of products. Subsectors are <b>Apparel</b> and accessory and beauty stores, <b>Auto parts</b> and repair shops, <b>Charity</b> stores and thrift stores, <b>Craft</b> and hobby stores, <b>Electronics</b> stores, <b>Farm</b> and ranch supply stores, <b>Furnishings</b> (covering furniture and home decor stores), <b>Hardware</b> (covering home improvement and garden supply stores), <b>Jewelry</b> stores, <b>Media</b> (covering video stores, record and music stores, video game stores, and bookstores), <b>Office supply</b> stores, <b>Optical</b> centers, <b>Pets</b> and pet supply stores, <b>Shoe</b> stores, <b>Sporting goods</b> stores, <b>Toys</b>, and <b>Diverse</b> companies</b>.
* <b>Vehicle</b>, indicating dealerships selling private vehicles. Subsectors are <b>Automotive</b> and <b>Boating</b> dealerships.

<b>Dates</b>

Companies report their revenues during fiscal years, which are twelve-month periods that often do not line up with the calendar year. For the sake of comparability across companies, any fiscal year ending after June 15th of a given calendar year is taken as the data point for that calendar year, while any fiscal period ending before June 15th is taken as the data point for the previous year.

<b>Data sources</b>

Whenever possible, official and precise data on company revenues is used. This data can be found in sources such as the Securities and Exchange Commission's <a href="https://www.sec.gov/edgar/searchedgar/companysearch.html">EDGAR</a> online filing system,  the <a href="https://archive.org/details/@archiveofannualreports">archiveofannualreports</a> collection on the Internet Archive, Moody's Corporate Manuals as found on <a href="https://www.mergentarchives.com">Mergent Archives</a>, other corporate reports and publications, and newspaper reports such as those found on <a href="https://www.newspapers.com">Newspapers.com</a> and the online archive of <a href="https://www.nytimes.com"><i>The New York Times</i></a>.

Where official data is not publicly available, data is estimated through a variety of techniques, including extrapolation and interpolation from official data, as well as comparison with store counts and other non-financial information. These estimates are original, but are made with awareness of and comparison to similar estimates by the National Retail Federation, <i>Forbes</i>, <i>Discount Store News</i>, Kurt Salmon Associates, Technomic, <i>QSR</i> magazine, <i>Restaurants and Institutions</i>, <i>Nation's Restaurant News</i>, <i>Restaurant Business</i>, <i>Franchise Times</i>, <i>Supermarket News</i>, <i>Convenience Store News</i>, <i>Automotive News</i>, and other trade and industry sources.

<b>Contact me</b>

This dataset is the work of Ben Schultz, a public historian and the founder of <a href="https://www.bluepageswiki.org">Bluepages</a>, a collaborative wiki-style historical directory of the world and extremely early work-in-progress. If you have any suggestions for companies that should be included in this data, corrections regarding incorrect data, or any other comments that would help me make this dataset the best it can possibly be, I want to hear from you. You can reach me at <a href="mailto:reschultzed%40gmail.com">reschultzed<i></i>@<i></i>gmail.com</a>.

This data is released into the public domain under a Creative Commons Zero license.
