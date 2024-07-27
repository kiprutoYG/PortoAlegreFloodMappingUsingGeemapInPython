# Flood mapping using Geemap in Python - Porto Alegre, Brazil
Using Sentinel 2 satellite imagery to derive the Modified Normalized Difference Water Index (MNDWI) that enabled the delineation of inundated areas in Porto Alegre, Brazil during the El Nino season of 2024.

- Data
    To tackle this flood mapping challenge, I harnessed the power of several key datasets and tools:

      1. Sentinel-2 Imagery:
          These high-resolution satellite images, provided by the European Space Agency's Copernicus program, offered a bird's-eye view of Porto Alegre before, during, and after the floods. With its 10-meter spatial resolution and frequent revisit times, Sentinel-2                  allowed us to track the flood's progression and extent with remarkable detail.

      2. Python:
          This versatile programming language served as the backbone of our analysis. Using various Python libraries, we processed satellite imagery, performed calculations, and created visualizations to bring our flood map to life.

      3.Global Surface Water (GSW) Dataset:
          Developed by the European Commission's Joint Research Centre, this dataset provides historical information on the Earth's surface water. It helped us understand Porto Alegre's typical water patterns and identify anomalies during the El Niño event.

      4. ESA Land Cover:
          The European Space Agency's global land cover map offered crucial context for our flood analysis. By understanding the different types of land use in Porto Alegre—urban areas, vegetation, bare soil, etc.—we could better interpret how the flood affected various             parts of the city.

    By combining these powerful datasets and tools, we were able to create a comprehensive picture of the 2024 El Niño floods in Porto Alegre.


- Methodology
    Here's an overview of the methodology:

  ![methodology](https://github.com/user-attachments/assets/7664fefc-fcfe-4231-b569-b2a075704138)


- Results
    The results obtained were in form of maps depicting:
    1. Porto Alegre before the flood
        ![beforeflood1](https://github.com/user-attachments/assets/cf85fef6-c5d1-4984-9375-546ae35f5701)

       
    2. Porto Alegre after the flood
       ![afterflood1](https://github.com/user-attachments/assets/eb1ea963-10e9-4827-88b2-82bb91c379f3)
       

    3. Porto Alegre permanent water
       ![permwaterporto1](https://github.com/user-attachments/assets/1222868a-4a71-452e-8b48-a96fec33fd73)
       

    4. Porto Alegre flooded areas
       ![floodedporto1](https://github.com/user-attachments/assets/5a02a68b-22fb-4588-a112-4f1d8cd9b0c9)
       

    5. Land use types affected by the flood
       ![landuses](https://github.com/user-attachments/assets/48ebb9ca-78e5-4fe4-9c29-bb026fa5cfc3)


  The flood was found to have inundated 69.791km2, representing 13% of the whole Porto Alegre area.
