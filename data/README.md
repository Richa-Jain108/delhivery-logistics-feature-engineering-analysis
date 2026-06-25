
## 📊 Dataset

The dataset used in this project is not included in the repository because it exceeds GitHub's web upload size limit.

You can download the original dataset here:

🔗 **[Delhivery Logistics Dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/551/original/delhivery_data.csv)**

### Dataset Overview

The dataset contains operational and routing information for Delhivery shipments. Each record represents a delivery segment and includes trip details, routing estimates, actual delivery performance, and location-specific information.

### Column Description

| Feature                            | Description                                                                                                                                |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **data**                           | Indicates whether the record belongs to the training or testing dataset.                                                                   |
| **trip_creation_time**             | Timestamp when the trip was created.                                                                                                       |
| **route_schedule_uuid**            | Unique identifier for a specific route schedule.                                                                                           |
| **route_type**                     | Transportation mode used for the shipment (FTL or Carting).                                                                                |
| **trip_uuid**                      | Unique identifier for a delivery trip. A single trip may include multiple source and destination centers.                                  |
| **source_center**                  | Unique ID of the source warehouse.                                                                                                         |
| **source_name**                    | Name of the source warehouse/location.                                                                                                     |
| **destination_center**             | Unique ID of the destination warehouse.                                                                                                    |
| **destination_name**               | Name of the destination warehouse/location.                                                                                                |
| **od_start_time**                  | Timestamp when the shipment started from the source.                                                                                       |
| **od_end_time**                    | Timestamp when the shipment reached the destination.                                                                                       |
| **start_scan_to_end_scan**         | Total delivery time from source scan to destination scan.                                                                                  |
| **is_cutoff**                      | Internal system field (purpose not specified).                                                                                             |
| **cutoff_factor**                  | Internal system field (purpose not specified).                                                                                             |
| **cutoff_timestamp**               | Internal system timestamp (purpose not specified).                                                                                         |
| **actual_distance_to_destination** | Actual road distance (in kilometers) between the source and destination warehouses.                                                        |
| **actual_time**                    | Actual cumulative delivery time for the shipment.                                                                                          |
| **osrm_time**                      | Estimated cumulative travel time calculated using the Open Source Routing Machine (OSRM), considering road network and traffic conditions. |
| **osrm_distance**                  | Estimated cumulative travel distance calculated using the OSRM routing engine.                                                             |
| **factor**                         | Internal system field (purpose not specified).                                                                                             |
| **segment_actual_time**            | Actual delivery time for an individual trip segment.                                                                                       |
| **segment_osrm_time**              | Estimated travel time for an individual trip segment using OSRM.                                                                           |
| **segment_osrm_distance**          | Estimated travel distance for an individual trip segment using OSRM.                                                                       |
| **segment_factor**                 | Internal system field (purpose not specified).                                                                                             |

### Transportation Types

| Route Type                | Description                                                                                                                                         |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **FTL (Full Truck Load)** | A shipment that occupies an entire truck, allowing direct transportation with no intermediate pickups or drop-offs, resulting in faster deliveries. |
| **Carting**               | A transportation mode that uses smaller vehicles (carts) for localized pickups and deliveries within a distribution network.                        |
