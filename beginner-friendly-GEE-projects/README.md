🌍 Google Earth Engine (GEE) Learning Notes

This repository is a collection of my notes and hands-on projects while learning Google Earth Engine (GEE). The lessons are designed for beginners and focus on understanding how GEE works, not just copying code.

Each project introduces a few new concepts and builds on the previous one, helping you develop a strong foundation in remote sensing and geospatial analysis.





🎯 Who Is This Repository For?

This repository is intended for:

Beginners learning Google Earth Engine.
Students studying GIS or Remote Sensing.
Anyone interested in satellite imagery and geospatial analysis.

No previous experience with Google Earth Engine is required.


List of projects: 


🌱 Level 1 – Getting Comfortable with GEE
1. Display a Satellite Image
    • Load a Landsat or Sentinel-2 image.
    • Change the visualization (true color vs false color).
    • Learn about bands.
Skills: Image loading, Map, visualization.

2. Zoom to Your City
    • Display your hometown or any city.
    • Add markers and polygons.
Skills: Geometry, Map.centerObject().

3. Compare Two Satellite Images
    • Show one image from summer and another from winter.
Skills: Date filtering.

4. Remove Clouds
    • Display an image before and after cloud masking.
Skills: Cloud filtering.

5. Clip an Image
   •  Clipped image (only your study area)
Skills: Clipping the study Area

🌿 Level 2 – Working with Vegetation
6. Calculate NDVI
    • Create a vegetation map.
Skills: Band math.

7. Compare NDVI in Different Seasons
    • See how vegetation changes during the year.
Skills: Time filtering.

8. Find Areas with Healthy Vegetation
    • Highlight places with high NDVI values.
Skills: Thresholding.

💧 Level 3 – Water Analysis
9. Calculate NDWI
    • Detect rivers, lakes, and reservoirs.

10. Compare Water Before and After Rain
    • Observe changes in a lake or reservoir.

11. Measure Lake Area
    • Estimate how the surface area changes over time.
Skills: Area calculation.

🌍 Level 4 – Land and Environment
12. Land Cover Visualization
    • Display a global land cover dataset.
Learn what each class means (forest, urban, cropland, water...).

13. Find Urban Areas
    • Display only built-up regions.

14. Surface Temperature Map
    • Use Landsat thermal bands to estimate land surface temperature.

15. Elevation Map
    • Display terrain using a Digital Elevation Model (DEM).

🌎 Level 5 – Time Series
16. Create an NDVI Time Series
    • Plot vegetation changes over one year.
Learn Charts.

17. Monthly Greenest Image
    • Build a monthly vegetation composite.
Learn ImageCollections.

18. Create an Annual Composite
    • Combine all images from one year into a single cloud-free image.

🔥 Level 6 – Environmental Applications
19. Detect Burned Areas
    • Compare images before and after a wildfire.

20. Monitor Deforestation
    • Compare forest cover between two different years.

21. Mini Environmental Monitoring Dashboard
Combine:
    • Satellite imagery
    • NDVI
    • NDWI
    • Land cover
    • Elevation
    • Charts