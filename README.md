# App-analysis
This is a python function based analysis solution. The file analyzes the Google playstore apps and the apple store apps.
The code default function build is to study free apps, and make reasonable provision/suggestion to a company that generates revenue from producing free apps as reliance is on users using the app. It checks for successful free apps by `user-ratings`, `genres`, etc but most importantly, the `price` column since free apps is major in our analysis of the google and apple apps.

Data cleaning was done for incorrectly shifted rows.

The code uses functions approach to make it easy to analyze both data using a single function with a few arguments adjustment.

## Files
You would find in the `app data` folder the `AppleStore.csv` file (comma delimeted) as well as the `googleplaystore.csv` file 

The codes are served using the Jupyter Notebook `.ipynb` extension.

Explanation of the columns include:

For the Apple Apps, the headers are explained below:

| Header | Description  |
| :-----:| :---------- |
| "id" | App ID |
| "track_name" | App Name |
| "size_bytes" | Size (in Bytes) |
| "currency" | Currency Type |
| "price" | Price amount |
| "rating_count_tot" | User Rating counts (for all version) |
| "rating_count_ver" | User Rating counts (for current version) |
| "user_rating" | Average User Rating value (for all version) |
| "user_rating_ver" | Average User Rating value (for current version) |
| "ver" | Latest version code |
| "cont_rating" | Content Rating |
| "prime_genre" | Primary Genre |
| "sup_devices.num" | Number of supporting devices |
| "ipadSc_urls.num" | Number of screenshots showed for display |
| "lang.num" | Number of supported languages |
| "vpp_lic" | Vpp Device Based Licensing Enabled |

For the google Apps, the headers are explained below:

| Header | Description |
| :---    | ---- |
| App | Application name |
| Category | Category the app belongs to  | 
| Rating | Overall user rating of the app (as when scraped) | 
| Reviews | Number of user reviews for the app (as when scraped) | 
| Size | Size of the app (as when scraped) | 
| Installs | Number of user downloads/installs for the app (as when scraped) | 
| Type | Paid or Free | 
| Price | Price of the app (as when scraped) | 
| Content Rating | Age group the app is targeted at - Children / Mature 21+ / Adult | 
| Genres | An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres. | 
| Last Updated | Date when the app was last updated on Play Store (as when scraped) | 
| Current Ver | Current version of the app available on Play Store (as when scraped) | 
| Android Ver | Min required Android version (as when scraped) | 

* You may practise with a few column headers, to make your own provisions and analysis using our functions.

* Also ensure that the `opened_file` variable points accurately using an absolute or a relative file path to the files in the app data folders when offline

* Code is found in the **`AppAnalysis.ipynb`** file

***Happy coding...***
