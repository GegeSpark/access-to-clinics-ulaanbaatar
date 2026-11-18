# access-to-clinics-ulaanbaatar
QGIS analysis of clinics or hospitals within walking distance in each Ulaanbaatar district, using OpenStreetMap data.

<img width="1425" height="1077" alt="adadadawea" src="https://github.com/user-attachments/assets/b0aa2459-fa8e-4475-9797-0165bcae2860" />
<img width="1425" height="1077" alt="resesesa" src="https://github.com/user-attachments/assets/2d834ddf-bd47-4c3f-92fb-d56439a87b66" />

Walking access to mapped health facilities is very uneven across the city. Bayangol has by far the highest coverage, with 52% of its area within 1000 m of a facility along the road network. Chingeltei follows with 15%. All other districts are below 7%.

All data came from OpenStreetMap, downloaded with the QuickOSM plugin in QGIS:
Health facilities: features tagged amenity = hospital, clinic or doctors.
Road network: highway lines suitable for walking, with motorways removed. 
District boundaries: administrative boundaries for Ulaanbaatar's districts (duureg).
Data was downloaded on 13th of November, 2026. OpenStreetMap is edited by volunteers, so completeness varies by area.

The results suggest that formally mapped health facilities are concentrated in the central districts, while the outer districts have limited walking access by area. Because of the limitations above, these results are best read as a comparison of mapped access, not as a measure of actual need.
