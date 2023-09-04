# richmondway
A dataset containing the number of times the word f*ck was used in Ted Lasso by Roy Kent

# Package installation
devtools::install_github("deepshamenghani/richmondway") 

# Accessing data
data(richmondway)

# Description
A dataset containing the number of times the word f-ck was used in Ted Lasso by Roy Kent.

# Usage
richmondway
Format
A data frame with 34 rows and 16 columns.

Character
Single value - Roy Kent

Episode_order
The order of episodes from the 1st to the last

Season
The season 1,2 or 3 associated with the count

Episode
The episode within the season associated with the count

Season_Episode
Season and episode as a combined variable

F_count_RK
Roy Kent's F-ck count in that season and episode

F_count_total
Total F-ck count by all characters combined including Roy Kent in that season and episode

cum_rk_season
Roy Kent's cumulative F-ck count within that season

cum_total_season
Cumulative total F-ck count by all characters combined including Roy Kent within that season

cum_rk_overall
Roy Kent's cumulative F-ck count across all episodes and seasons until that episode

cum_total_overall
Cumulative total F-ck count by all characters combined including Roy Kent across all episodes and seasons until that episode

F_score
Roy Kent's F-count divided by the total F-count in the episode

F_perc
F-score as percentage

Dating_flag
Flag of yes or no for Whether during the episode Roy Kent was dating the characted Keeley

Coaching_flag
Flag of yes or no for Whether during the episode Roy Kent was coaching the team

Imdb_rating
Imdb rating of that episode

Source
Created by Deepsha Menghani by watching the show and counting the number of F-cks used in sentences and as gestures

