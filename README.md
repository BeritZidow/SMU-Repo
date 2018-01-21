# stat6306introdatascience
Files and projects for Stat 6306 Introduction to Data Science

# R code for profile bar chart
Cats <- character(8)
Cats <- c("Viz", "CP", "Math","stats","ML","DomExp","comm","PresSkills")
Scores <- c(4, 4, 2, 3, 2, 3, 5, 5)

# Fitting Labels 
par(las=2) # make label text perpendicular to axis
par(mar=c(5,8,4,2)) # increase y-axis margin.
barplot(Scores, main="Profile", horiz=FALSE,
        names.arg= Cats)

