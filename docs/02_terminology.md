---

---

## Terminology and Definitions

### Signals

- **Trigger**
Represents any type of signal, usually but not always impulsive, that "triggers" the seismic system.

- **Event**
Indiscriminately, represent any association triggers occurring within a predefined time window.

- **Seismic Event (mining induced)**
Usually refers to a mining induced event that results from the interaction of stress (increase or decrease) and the rock mass that can be linked to a series of phenomena including but not limited to:

     - **Rock/Strain burst**:  The violent ejection of rock that is a primary concern in mines.
  
     - **Slip motion (Fault slip)**: Movement along existing geological features.

     - **Fall of ground**: A broad term that effectively captures events like rock falls.

     - **Tensile or compressive fracturing**: The breakage of the rock as a result of compressive or tensile forces.

    - **Shear rupture**: A rupture along weaknesses in the rock that results in a shear motion.

     - **Pillar crushing/damage**:  Fracturing of the rock inside a pillar, resulting in its integrity to be compromised or affected.


- **Blast (development, production, other)**
Refers to a man made controlled explosion linked to the development of excavation or the extraction of ore. 

### Seismological Objects and Formats

- **Waveforms**  
A time series representation of seismic wave amplitudes detected by sensors in microseismic monitoring. Originating from subsurface events like rock fractures.

- **Catalog/Seismic Bulletin**  
  A curated collection of detected and processed microseismic events, systematically listing key parameters such as event origin time, location, magnitude, corner frequency, and energy. Derived from waveform analysis, the catalog serves as a comprehensive record of seismicity.

- **Inventory**  
  A structured repository detailing the metadata of seismic networks, stations, and their associated instrumentation. It encompasses station location, operational time periods, instrument response, and channel configurations.

- **SEED**  
  A standardized format for representing and exchanging digital seismological data encompassing waveform records and related metadata. Established by the Federation of Digital Seismographic Networks (FDSN), SEED (Standard for the Exchange of Earthquake Data) is widely adopted for its ability to consolidate seismic data and its associated station and instrument information into a unified structure, ensuring consistency and interoperability in seismological research and monitoring.

- **MiniSEED**  
  A subset of the SEED format specifically designed for the exchange and storage of seismic waveform data. While the broader SEED standard encompasses data and comprehensive metadata, MiniSEED focuses solely on time series data, making it more compact and suitable for efficient data transmission and storage. Despite its simplicity, MiniSEED retains the essential headers for data identification and integrity, ensuring its applicability in diverse seismological applications.

- **QuakeML**  
  A standardized XML-based data format developed for representing and exchanging seismological data related to earthquakes. By covering event parameters like origins, magnitudes, and phase picks, QuakeML aims to facilitate interoperability and consistency in sharing and processing seismic event information across various seismological tools and platforms. Its structured schema ensures that earthquake-related data are described comprehensively yet flexibly, catering to diverse seismological research and monitoring needs.

- **StationXML**  
  A modern XML-based format designed for the representation and exchange of metadata associated with seismic stations, networks, and associated instruments. Evolved as a successor to the SEED format's metadata component, StationXML provides a detailed description of station configurations, instrument response information, and operational time periods, among other attributes. Its structured framework ensures a comprehensive and consistent portrayal of the seismic data acquisition chain, promoting accurate data interpretation and seamless exchange across seismological applications.

- **HDF5 (Hierarchical Data Format version 5)**  
  An advanced data model, library, and file format designed for storing and organizing large volumes of complex data, including arrays of numbers, multidimensional datasets, and metadata. HDF5 is optimized for high performance and flexibility, allowing for efficient storage and retrieval across diverse platforms and languages. Its hierarchical structure supports grouping related objects and tagging with rich metadata, making it a widely adopted choice for scientific computing applications where complex datasets and their associated metadata need to be integrated.

- **ASDF (Adaptable Seismic Data Format)**  
  A modern data format explicitly designed for seismological data and related metadata. Building on the HDF5 infrastructure, ASDF is tailored for efficiency, scalability, and adaptability in both storage and processing of seismic data. It facilitates the integration of raw waveforms, processed data products, event parameters, and station metadata within a single file structure. The format's adaptability and hierarchical structure ensure consistent and optimized handling of diverse seismic datasets, making it a valuable choice for advanced seismological research and applications.

### Equipment

- **Sensor**  
  A device specifically designed to detect or measure a physical property and convert this input into an electrical signal. A sensor (e.g., geophone element) is responsible for directly detecting seismic waves and transducing them into voltage variations based on its sensitivity. Example: a 4.5 Hz geophone.

- **Instrument**  
  A comprehensive setup encompassing one or multiple sensors and associated components, including casings, and internal electronics if applicable. In microseismic monitoring, an instrument refers to the entire arrangement employed for seismic detection. Its response combines the characteristics of the individual sensors. Example: a tri-axial dual element geophone.

- **Location**
Represents a location where an instrument is deployed. The location could refer to an instrument.

- **Station**
A logical or physical grouping of instruments deployed at one or multiple "locations". In the most minimalist case, a station can comprise only one instrument.

- **Network**
A logical grouping of multiple stations used to detect, locate and characterized events.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM2Mjg4OTM0LC0yMDMwOTQxMTc5LDM2OT
QzOTY5MiwxNjY5Njg5OTAwLC0xMDc4MzY4MDU2XX0=
-->