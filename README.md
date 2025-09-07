#######################################			
## Metadata for caterpillar collections	included as part of the Lepidoptera monitoring program 
## in the Sierra Nevada and Great Basin, USA.	
#######################################			
			
Details below are for this data files:			
			
CaterpillarPlots2009_2024.csv			
			
These data are available: https://github.com/LeeDyerUNR/Plots-for-multitrophic-interactions-in-the-Sierra-Nevada-and-Great-Basin-USA			
		
############################			
## LTREB-PLOT.csv = CaterpillarPlots2009_2024.csv	
############################			
			
This file contains plant data associated with either (1) general collections at a given focal site or adjacent locality, or (2) plots used to sample plant diversity and richness within a defined area at focal long-term monitoring sites. Each row represents an instance of collection on a given plant species at a given location. The number of individuals belonging to a species may vary by row (see “N” below).
			
plot_num – Unique value representing a plot a plant is associated with.

Plot/PlaceName – Label or nickname for a plot, used primarily for book-keeping.

Person – Name of collector(s).

Site – Long-term monitoring site (or alternative location) where collection occurred or where the plot was located.

plot_diam – Diameter (in meters) of the circular plot in which plants were sampled.

year, month, day – Date of collection (redundant with date).

date – Date of collection in day–month–year format.

lat, long – Decimal latitude and longitude of collection.

time_of_day – Time of day a plant was sampled; for plots, the starting time of the plot was used for all plants.

elev – Elevation at collection site.

tree_ID – Unique ID for a specific plant individual.

center_plant_gen – Dominant plant genus near the center of a plot, often providing canopy cover or ecological context (optional).

plant_order, plant_family, plant_genus, plant_sp – Taxonomic classifications for the plant.

Hplant – Most specific plant name provided; usually matches plant_sp, but can be a common name when species ID was not possible (e.g., “unknown Fabales,” “Geranium”).

PlantIND – Unique plant identifier for a site and date. This links to caterpillar records (PlantIND column in LTREB_2009_2025-Rearing_Comprehensive.csv).

<- or -> – Field mark used for directional notes 

N – Number of plant individuals in this collection instance. If blank, assumed to be 1.

Time_Coll – Time (in minutes) spent collecting from the plant(s).

N_coll – Number of collectors working during the Time_Coll interval.

height, width, length – Plant dimensions in feet. If N > 1, values represent averages.

N SWEEPS (b&f) – Number of sweep net passes (“back & forth”) if sweep netting was used. Blank = not swept (beating was standard).

percent_sampled – Percentage of the plant(s) sampled.

num_leaf – Total number of leaves on a plant or plants.

Leaf_Count_total, Leaf_Count_Per, Per, Unit, leaf_per_sqm, sqmeters, %Plot – Various leaf count and coverage metrics that need scripts to use properly and to yield total leaves, per-unit counts, leaves per m², and similar metrics. 

dbh – Diameter at breast height (DBH) of plant individual(s).

dbh_units – Units used for DBH (likely cm).

Text – External leaf temperature samples; pipe-delimited values in °F.

Tint – Internal leaf temperature samples; pipe-delimited values in °F.

ENVext – External environmental air temperature; pipe-delimited values in °F.

ENVint – Internal environmental air temperature; pipe-delimited values in °F.

HUMext – External leaf-surface humidity; pipe-delimited values in percent.

HUMint – Internal leaf-surface humidity; pipe-delimited values in percent.

DEWext – External leaf dew point; pipe-delimited values in °F.

DEWint – Internal leaf dew point; pipe-delimited values in °F.

tree_age – Estimated age of tree (years).

canopy_cover – Percentage canopy cover.

tree_biomass_volume – Biomass volume estimate for tree(s).

percent_filled_biomass – Percentage of tree biomass volume filled.

total_volume_biomass – Total biomass volume for tree(s).

shrub_cov – Shrub cover.

percent_veg_cover – Percent cover of vegetation.

shrub_div – Shrub diversity.

wildflower_present – Presence/absence of wildflowers.

wildflower_abun – Abundance of wildflowers.

num_leaves_samp – Number of leaves sampled.

leaf_area – Area of sampled leaves.

clim – Climate or microclimate code.

plotter – Name/ID of the person who plotted the data.

notes – Field notes.

LEAVES, TOTAL – Complex leaf counts and summary totals.

PLOT NOTES – Free-text plot notes.

Underground – Notes on underground vegetation or root sampling.

abundance – Abundance of plants observed.

foliage_yn – Indicator if foliage was present (yes/no).

LEAF_@_foot – Leaf counts near ground level (1 foot).

groundtype – Ground type (substrate classification).


###SAME INFORMATION IN TABLE FORMAT:
| Column                   | Description                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------- |
| plot\_num                | Unique plot identifier                                                                          |
| Plot/PlaceName           | Label or nickname for a plot (book-keeping only, not always used)                               |
| Person                   | Name of collector(s)                                                                            |
| Site                     | Monitoring site or alternative location of collection                                           |
| plot\_diam               | Diameter (m) of circular plot where plants were sampled                                         |
| year                     | Year of collection                                                                              |
| month                    | Month of collection                                                                             |
| day                      | Day of collection                                                                               |
| date                     | Date in day–month–year format                                                                   |
| lat                      | Decimal latitude                                                                                |
| long                     | Decimal longitude                                                                               |
| time\_of\_day            | Time of day plant was sampled; for plots, the starting time for all plants                      |
| elev                     | Elevation at collection site                                                                    |
| tree\_ID                 | Unique identifier for a specific plant individual                                               |
| center\_plant\_gen       | Dominant plant genus at plot center (often provides canopy cover; optional)                     |
| plant\_order             | Plant order                                                                                     |
| plant\_family            | Plant family                                                                                    |
| plant\_genus             | Plant genus                                                                                     |
| plant\_sp                | Plant species epithet                                                                           |
| Hplant                   | Most specific name provided for plant (species name or common name if unknown)                  |
| PlantIND                 | Unique plant identifier for site and date; links to caterpillar data (PlantIND in rearing file) |
| <- or ->                 | Field mark               |
| N                        | Number of plant individuals represented; blank = assumed 1                                      |
| Time\_Coll               | Time (minutes) spent collecting from plant(s)                                                   |
| N\_coll                  | Number of collectors during the Time\_Coll interval                                             |
| height                   | Plant height in feet (average if N > 1)                                                         |
| width                    | Plant width in feet (average if N > 1)                                                          |
| length                   | Plant length in feet (average if N > 1)                                                         |
| N SWEEPS (b\&f)          | Number of sweep net passes (back & forth); blank = not swept                                    |
| percent\_sampled         | Percentage of plant(s) sampled                                                                  |
| num\_leaf                | Total number of leaves on plant(s)                                                              |
| Leaf\_Count\_total       | Total leaf count (duplicate of num\_leaf in some cases)                                         |
| Leaf\_Count\_Per         | Per-unit leaf count                                                                             |
| Per                      | Unit basis for leaf counts (paired with Leaf\_Count\_Per)                                       |
| Unit                     | Unit of measurement used in leaf counts                                                         |
| leaf\_per\_sqm           | Leaves per square meter                                                                         |
| sqmeters                 | Area of plant sampled in square meters                                                          |
| %Plot                    | Percent of total plot sampled                                                                   |
| dbh                      | Diameter at breast height of plant individual(s)                                                |
| dbh\_units               | Units for DBH (likely cm)                                                                       |
| Text                     | External leaf temperature samples (°F, pipe-delimited)                                          |
| Tint                     | Internal leaf temperature samples (°F, pipe-delimited)                                          |
| ENVext                   | External environmental air temperature (°F, pipe-delimited)                                     |
| ENVint                   | Internal environmental air temperature (°F, pipe-delimited)                                     |
| HUMext                   | External leaf-surface humidity (% humidity, pipe-delimited)                                     |
| HUMint                   | Internal leaf-surface humidity (% humidity, pipe-delimited)                                     |
| DEWext                   | External leaf dew point (°F, pipe-delimited)                                                    |
| DEWint                   | Internal leaf dew point (°F, pipe-delimited)                                                    |
| tree\_age                | Estimated tree age (years)                                                                      |
| canopy\_cover            | Percentage of canopy cover                                                                      |
| tree\_biomass\_volume    | Estimated tree biomass volume                                                                   |
| percent\_filled\_biomass | Percentage of tree biomass volume filled                                                        |
| total\_volume\_biomass   | Total biomass volume of tree(s)                                                                 |
| shrub\_cov               | Shrub cover                                                                                     |
| percent\_veg\_cover      | Percent vegetation cover                                                                        |
| shrub\_div               | Shrub diversity                                                                                 |
| wildflower\_present      | Presence/absence of wildflowers                                                                 |
| wildflower\_abun         | Wildflower abundance                                                                            |
| num\_leaves\_samp        | Number of leaves sampled                                                                        |
| leaf\_area               | Area of sampled leaves                                                                          |
| clim                     | Climate or microclimate code                                                                    |
| plotter                  | Name/ID of person recording plot data                                                           |
| notes                    | Field notes                                                                                     |
| LEAVES                   | Leaf count (duplicate field)                                                                    |
| TOTAL                    | Total count (duplicate field)                                                                   |
| PLOT NOTES               | Free-text plot notes                                                                            |
| Underground              | Notes on underground vegetation or roots                                                        |
| abundance                | Abundance of plants observed                                                                    |
| foliage\_yn              | Indicator if foliage was present (yes/no)                                                       |
| LEAF\_@\_foot            | Leaf counts near ground level (\~1 foot)                                                        |
| groundtype               | Ground substrate type                                                                           |


