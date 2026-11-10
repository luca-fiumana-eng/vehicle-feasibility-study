# Electric Tilting Vehicle — Engineering Feasibility Study

**Historical concept baseline:** December 2019  
**Document type:** Sanitised engineering portfolio case study  
**Scope:** Vehicle architecture, packaging, chassis design, FEM, ergonomics, industrialisation and preliminary business case.

> This is a retrospective portfolio document based on historical concept engineering material. Company and product identifiers have been removed from the report and slide headers. Technical values are reproduced as documented and should not be interpreted as current certified specifications or production validation. Images are retained from historical engineering documents and have been cropped to remove branded slide headers. Publish only where you hold the necessary rights.

## 1. Concept and vehicle architecture

The project investigated a compact, fully electric, four-wheel tilting vehicle with tandem seating and a modular body architecture. Open and roofed configurations were assessed, including alternative passenger-seat and restraint arrangements.

The reference electric powertrain used a motor in the 45–52 kW peak-power range and 110–157 Nm peak torque range, coupled to a differential. The battery concept centred on an approximately 14.4 kWh integrated pack, with optional modular capacity. A 1.3 kW standard charger and optional higher-power charging were considered. These are concept-stage reference values.

![Open and roofed concept renderings](assets/vehicle_concept_open_roofed.png)

*Open and roofed concept renderings.*

![Exterior design alternatives](assets/vehicle_concept_variants.png)

*Exterior design alternatives.*

## 2. Modular chassis and body integration

The chassis concept was designed to support different body and seating configurations. The integration work considered roof supports, fixing points, seat positioning, sliding-seat packaging and component interfaces.

![Chassis modularity – open configuration](assets/chassis_modularity_open.png)

*Chassis modularity – open configuration.*

![Chassis modularity – structural seat](assets/chassis_modularity_structural_seat.png)

*Chassis modularity – structural seat.*

![Chassis modularity – roofed configuration](assets/chassis_modularity_roofed.png)

*Chassis modularity – roofed configuration.*

![Roof structure and fixing-point concept](assets/roof_fixing_points.png)

*Roof structure and fixing-point concept.*

![Sliding-seat packaging](assets/sliding_seat_layout.png)

*Sliding-seat packaging.*

![Vehicle architecture and packaging overview](assets/vehicle_architecture_views.png)

*Vehicle architecture and packaging overview.*

![Upper-frame integration](assets/upper_frame_integration.png)

*Upper-frame integration.*

## 3. System breakdown and packaging feasibility

The visual bill of materials decomposed the vehicle into chassis, suspension, steering, powertrain, braking, electrical, bodywork, seating, roof and cargo systems. Packaging reviews addressed body/frame clearance, dynamic wheel envelopes, motor/differential installation and alternative battery layouts.

![Vehicle visual bill of materials and system breakdown](assets/visual_bom.png)

*Vehicle visual bill of materials and system breakdown.*

![Body/frame interference review](assets/body_frame_clearance.png)

*Body/frame interference review.*

![Rear wheel dynamic-envelope check](assets/rear_wheel_dynamic_envelope.png)

*Rear wheel dynamic-envelope check.*

![Front wheel dynamic-envelope check](assets/front_wheel_dynamic_envelope.png)

*Front wheel dynamic-envelope check.*

![Powertrain integration and packaging](assets/powertrain_packaging.png)

*Powertrain integration and packaging.*

![Battery layout feasibility matrix](assets/battery_packaging_matrix.png)

*Battery layout feasibility matrix.*

![Battery pack layout alternatives](assets/battery_packaging_options.png)

*Battery pack layout alternatives.*

![Central frame design](assets/central_frame_design.png)

*Central frame design.*

The body/frame review recorded a nominal 34.4 mm clearance in the evaluated configuration. The rear-wheel dynamic-envelope review recorded a maximum conflict of 112.5 mm, which required resolution. Battery options were compared against frame changes, wheelbase impact, mass, body modifications, cable routing and available volume.

## 4. Structural engineering and FEM

The lower frame was assessed as a welded steel structure (2 mm nominal thickness; material designation 36SMn14 in the source). The roof structure was assessed in aluminium alloy 7050-T73510 (3 mm nominal thickness). The preliminary model simplified the tilting hardware and swing arms as rigid bodies.

The documented load cases included frame vertical loading, braking at 1 g, torsion with a 100 Nm applied torque, upper-body vertical and transversal loading, and driver-seat vertical/transversal loads. The study reported approximately 11,792 Nm/° torsional stiffness for the analysed frame model. Driver-seat slide areas showed local stress concentrations and a recommendation to increase fasteners. Rollover protective structure assessment was still in progress in the December 2019 status.

![Lower frame preliminary FEM model](assets/lower_frame_fem_model.png)

*Lower frame preliminary FEM model.*

![FEM mass and load simplification](assets/lower_frame_fem_mass_model.png)

*FEM mass and load simplification.*

![Lower frame FEM mesh](assets/lower_frame_fem_mesh.png)

*Lower frame FEM mesh.*

![FEM – frame vertical load](assets/fem_frame_vertical_load.png)

*FEM – frame vertical load.*

![FEM – frame braking load](assets/fem_frame_braking_load.png)

*FEM – frame braking load.*

![FEM – frame torsional stiffness](assets/fem_frame_torsion.png)

*FEM – frame torsional stiffness.*

![FEM – upper body vertical load](assets/fem_upper_body_vertical.png)

*FEM – upper body vertical load.*

![FEM – upper body transversal load](assets/fem_upper_body_transversal.png)

*FEM – upper body transversal load.*

![FEM – driver seat vertical load](assets/fem_driver_seat_vertical.png)

*FEM – driver seat vertical load.*

![FEM – driver seat transversal load](assets/fem_driver_seat_transversal.png)

*FEM – driver seat transversal load.*

![Rollover protective structure assessment status](assets/fem_rollover_protection.png)

*Rollover protective structure assessment status.*

### Rear swing-arm FEM study

A separate aluminium-alloy rear swing-arm study documented the FEM model, load cases, results for two load conditions and torsional-stiffness assessment. These results belong to a component-level analysis and should not be conflated with the vehicle-level frame FEM results above.

![Swing-arm FEM model](assets/swingarm_fem_model.png)

*Swing-arm FEM model.*

![Swing-arm FEM load cases](assets/swingarm_fem_load_cases.png)

*Swing-arm FEM load cases.*

![Swing-arm FEM results – load case 1](assets/swingarm_fem_results_loadcase1.png)

*Swing-arm FEM results – load case 1.*

![Swing-arm FEM results – load case 2](assets/swingarm_fem_results_loadcase2.png)

*Swing-arm FEM results – load case 2.*

![Swing-arm torsional stiffness](assets/swingarm_torsional_stiffness.png)

*Swing-arm torsional stiffness.*

![Swing-arm FEM conclusion](assets/swingarm_fem_conclusion.png)

*Swing-arm FEM conclusion.*

## 5. Ergonomics and occupant packaging

The roofed-body study evaluated helmet clearance and driver accommodation. With the stated assumptions, available internal height was estimated at approximately 913 mm. A 1,784 mm driver-height reference and 50 mm helmet-to-roof clearance corresponded to approximately the 88.3rd percentile in the source population model.

![Ergonomic packaging and helmet clearance](assets/ergonomics_height_clearance.png)

*Ergonomic packaging and helmet clearance.*

![Driver accommodation percentile assessment](assets/ergonomics_driver_percentile.png)

*Driver accommodation percentile assessment.*

## 6. Mass and component complexity

The source comparison recorded 21 versus 13 body-plastic components and 28 versus 12 structural-frame components. The corresponding reported masses were 25.6 versus 5.75 kg for body plastics and 54 versus 22.5 kg for the frame. The source slides contain inconsistent percentage annotations; percentages should be recalculated from absolute values and the comparison boundaries verified before drawing firm conclusions.

![Bodywork component complexity](assets/bodywork_complexity.png)

*Bodywork component complexity.*

![Frame component complexity](assets/frame_complexity.png)

*Frame component complexity.*

## 7. Programme status, risks and next steps

At the December 2019 baseline, major packaging, frame design and several FEA activities were recorded as complete. Seat/belt integration, windscreen/wiper integration and aerodynamic CFD were still in progress; rollover protection was also open.

Key closure activities:

1. Resolve wheel dynamic-envelope conflicts and confirm all steering/tilting travel.
2. Freeze battery layout, retention, cooling/protection and HV routing with suppliers.
3. Complete rollover, fatigue, joint/weld and physical correlation activities.
4. Close seat-slide stress concentrations, restraints and belt anchorage.
5. Validate roof, glazing, wipers, visibility, sealing and aerodynamic loads.
6. Complete market-specific homologation assessment.
7. Obtain supplier quotations and confirm tooling/manufacturing feasibility.
8. Rebuild the business case with supplier-backed BOM and sensitivity scenarios.

## 8. Preliminary business case

The historical base case assumed 15,000 units over five years, average retail price of €28,400 and net revenue of €20,202 per unit. It reported €5.87 million R&D, €5.02 million tooling in the summary case, €10.89 million total investment, 2,791-unit break-even, 1.2-year payback and €41.3 million NPV. These are historical model outputs based on estimates, not independently audited results.

The detailed tooling table reports €4.02 million, which conflicts with the €5.02 million summary value and requires reconciliation. Supplier quotations were not yet available and OEM production tooling was excluded.

## 9. Overall feasibility conclusion

The concept demonstrated a credible engineering pathway to a prototype and detailed-validation phase. The strongest evidence is the breadth of completed architecture, packaging, chassis and preliminary FEM work. The remaining critical path included dynamic clearances, rollover protection, occupant restraints, aerodynamic validation, supplier confirmation, physical testing and homologation. The available material does **not** establish production readiness, homologation or commercial validation.

## Source and confidentiality note

This portfolio edition removes company/product naming from the report text and branded slide headers. The source figures and images are derived primarily from the December 2019 feasibility presentation, supplemented by a rear swing-arm aluminium-alloy FEM report and related technical material. Before making the repository public, confirm ownership and publication rights for all images, CAD screenshots, supplier references and engineering data.
