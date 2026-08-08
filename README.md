# Awesome-Solid-Waste-Routing

## Top Solid Waste Routing Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Waste Collection Route Optimization, Fleet Dispatch, Service Verification & Municipal/Commercial Hauling*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Solid Waste Routing**. These tools optimize collection routes, manage dispatch and fleet operations, capture proof-of-service, handle missed pickups and exceptions, support residential/commercial/recycling streams, and improve efficiency for municipalities and private haulers.



**Examples** include Routeware, Rubicon, AMCS, Evreka, Soft-Pak, ReCollect, RouteSmart, Waste Logics, Recycle Track Systems, and Tower Systems (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for vehicle routing (VRP), open routing engines, waste-specific optimizers, map-based planning, and self-hosted logistics tooling — ideal for municipalities, haulers, operations researchers, and developers building transparent, controllable waste collection systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
|---------|-------------|---------|-----------------|
| **[Routeware](https://www.routeware.com/)** | Comprehensive waste and recycling operations platform offering route optimization, dispatch, service verification, fleet tools, and resident engagement for municipal and commercial fleets. | Custom / Contact Sales | N/A |
| **[Rubicon](https://www.rubicon.com/)** | Digital waste and recycling platform providing routing, dispatch, proof-of-service, analytics, and smart-city capabilities for haulers and municipalities. | Custom / Contact Sales | N/A |
| **[AMCS](https://www.amcsgroup.com/)** | Enterprise waste management platform with advanced routing, dispatch, weighbridge integration, multi-stream operations, and sustainability/ESG reporting. | Custom / Contact Sales | N/A |
| **[Evreka](https://evreka.co/)** | Smart waste management and IoT-enabled platform supporting route optimization, sensor-based collection, and operational visibility for cities and operators. | Custom / Contact Sales | N/A |
| **[Soft-Pak](https://www.soft-pak.com/)** | Waste industry software focused on route management, fleet intelligence, service verification, billing, and connected truck operations. | Custom / Contact Sales | N/A |
| **[ReCollect](https://recollect.net/)** | Resident-facing and municipal collection platform emphasizing curbside schedules, service communication, and operational support for waste programs. | Custom / Contact Sales | N/A |
| **[RouteSmart](https://www.routesmart.com/)** | Specialized route planning and optimization software widely used for waste collection sequencing, missed-service reporting, and high-density stop networks. | Custom / Contact Sales | N/A |
| **[Waste Logics](https://www.wastelogics.com/)** | Waste management software covering routing, scheduling, fleet operations, and business processes for haulers and recyclers. | Custom / Contact Sales | N/A |
| **[Recycle Track Systems (RTS)](https://www.rts.com/)** | Technology-enabled waste and recycling services platform with tracking, routing support, and digital tools for commercial and municipal customers. | Custom / Contact Sales | N/A |
| **[Tower Systems](https://www.towersystems.com/)** | Waste industry software solutions supporting operational management, routing, and related back-office functions for collection companies. | Custom / Contact Sales | N/A |



## Open-Source GitHub Projects



- **[OSRM (Open Source Routing Machine)](https://github.com/Project-OSRM/osrm-backend)**  

  High-performance open-source routing engine built on OpenStreetMap data, widely used as the foundation for custom vehicle routing and matrix calculations.



- **[VROOM](https://github.com/VROOM-Project/vroom)**  

  Open-source Vehicle Routing Problem solver that integrates with OSRM/OpenRouteService for capacitated, time-window, and multi-vehicle optimization.



- **[Google OR-Tools](https://github.com/google/or-tools)**  

  Powerful open-source optimization suite including vehicle routing, constraint programming, and solvers frequently applied to waste collection VRP variants.



- **[OpenRouteService](https://github.com/GIScience/openrouteservice)**  

  Open-source routing service based on OpenStreetMap offering directions, isochrones, matrices, and optimization APIs suitable for fleet planning.



- **[GraphHopper](https://github.com/graphhopper/graphhopper)**  

  Fast open-source routing engine with Java and other bindings, supporting custom profiles and matrix calculations for logistics applications.



- **[PyVRP](https://github.com/PyVRP/PyVRP)**  

  High-quality open-source Python VRP solver focused on performance and research-grade vehicle routing problems, including waste-style instances.



- **[pgRouting](https://github.com/pgRouting/pgrouting)**  

  Open-source extension for PostGIS/PostgreSQL that provides routing and network analysis functions useful for geospatial waste route planning.



- **[Urban-Waste-Collection](https://github.com/N-Wouda/Urban-Waste-Collection)**  

  Research codebase for integrated container selection and routing policies in urban solid waste collection, with simulation and OSRM support.



- **[Refuse-Collection-Vehicle-Route-Optimization](https://github.com/fabmid/Refuse-Collection-Vehicle-Route-Optimization)**  

  Tool leveraging OSRM and VROOM to optimize refuse collection vehicle routes from address data and analyze distances.



- **[VRP Trash Collection projects](https://github.com/cvvergara/vrp-trash-collection)**  

  Implementations of capacitated multi-trip time-window VRPs specifically modeled for garbage collection (depot → containers → dump cycles).



- **[Multi-Vehicle-Routing](https://github.com/ai4smlab/Multi-Vehicle-Routing)**  

  Full-stack open playground for VRP with OR-Tools, Pyomo, VROOM solvers, map frontend, and distance-matrix adapters.



- **[docker-ors-vroom](https://github.com/stefanocudini/docker-ors-vroom)**  

  Ready-to-run Docker setup combining OpenRouteService and VROOM for testing and deploying vehicle routing solutions.



### Additional Strong Open-Source Options



- **OR-Tools + OSRM/VROOM** stacks for custom capacitated waste collection solvers.

- **OpenStreetMap + Geofabrik** data pipelines for local road networks and travel-time matrices.

- **Genetic algorithms, local search, and metaheuristics** notebooks applied to garbage collection VRPs.

- **Valhalla** and other FOSS routing engines for alternative matrix and pathfinding backends.

- Community **waste-collection simulation**, **sensor-driven dynamic routing**, and **e-waste reverse logistics** optimizers.

- Many academic and municipal pilot repositories implementing multi-trip, time-window, and dump-site constrained VRPs.



**Frameworks for building custom systems**: Combine **OSRM or OpenRouteService** for road networks and matrices, **VROOM / OR-Tools / PyVRP** for optimization, a simple dispatch UI or GIS layer, and optional IoT fill-level inputs to create a complete open-source solid waste routing platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Waste routing systems must comply with local environmental, safety, labor, and data-privacy regulations.

- Self-hosted open-source solutions require accurate map data, proper operational validation, and reliable fleet integration.



---



**Made for municipal fleet managers, private haulers, operations researchers, and waste technology developers.**  

Let's make solid waste collection routing more efficient, transparent, and sustainable.
