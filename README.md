# carla-ecsd-figures
Figures for CARLA Extended CARLA Scenario Dataset (ECSD) - Bachelor thesis

## Experimental Data

The complete experimental results (model responses, scores, safety metrics) are available in Google Sheets:

🔗 [**ECSD Experimental Results - Google Sheets**](https://docs.google.com/spreadsheets/d/1oQPf4v3Y2HLIZzj1QDnRi4RL9bXLqqNzroxCodPlCHY/edit?usp=sharing)

The dataset includes:
- Evaluation of LLaVA, BLIP-2, and KOSMOS-2 on 3CSim baseline (80 images)
- Evaluation of the same models on ECSD scenarios (S1-S10)
- Safety scores and False Negative Rates
- Error classification per scenario and per model
- Raw model responses for all prompt types

## Scenarios Overview

| ID | Name | Main Difficulty |
| :--- | :--- | :--- |
| S1 | Flying Lumber from Truck | Rapid occlusion, non-standard flying object |
| S2 | Deer Leaps Across Highway at Night | Dark animal, headlight glare, rain |
| S3 | Child Runs Onto Road at Dusk | Small object, transitional lighting |
| S4 | Parking Lot — Car Reverses Into Path | Full occlusion, zero reaction time |
| S5 | Glare + Hidden Vehicle on Turn | Glare, dark vehicle, poor visibility |
| S6 | Ambulance Runs Red Light | Non-standard behavior, flashing lights |
| S7 | Accident Scene — Ego Swerves | Occlusion, no time to react |
| S8 | Animal Swarm on Road | Multiple small objects, non-standard agent |
| S9 | Flooded Road with Hidden Depth | Environmental hazard, no explicit agent |
| S10 | Motorcyclist Lane Splitting | Small profile, non-standard behavior |

## Citation

If you use these figures, the dataset, or the scenarios in your research, please cite:

```bibtex
@thesis{Telizhyn2026,
  author  = {Yuliia Telizhyn},
  title   = {CARLA Simulator Scenarios for Testing Autonomous Mobility Systems},
  school  = {Technical University of Košice},
  year    = {2026}
}
