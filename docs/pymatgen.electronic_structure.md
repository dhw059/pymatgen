---
layout: default
title: pymatgen.electronic_structure.md
nav_exclude: true
---

# pymatgen.electronic_structure package

This package contains electronic structure related tools and analyses.

## Subpackages


* [pymatgen.electronic_structure.tests package](pymatgen.electronic_structure.tests.md)




    * [pymatgen.electronic_structure.tests.test_bandstructure module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_bandstructure)


        * [`BandStructureSymmLineTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest)


            * [`BandStructureSymmLineTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.setUp)


            * [`BandStructureSymmLineTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.tearDown)


            * [`BandStructureSymmLineTest.test_apply_scissor_insulator()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_apply_scissor_insulator)


            * [`BandStructureSymmLineTest.test_apply_scissor_spin_polarized()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_apply_scissor_spin_polarized)


            * [`BandStructureSymmLineTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_as_dict)


            * [`BandStructureSymmLineTest.test_basic()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_basic)


            * [`BandStructureSymmLineTest.test_get_band_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_band_gap)


            * [`BandStructureSymmLineTest.test_get_branch()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_branch)


            * [`BandStructureSymmLineTest.test_get_cbm()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_cbm)


            * [`BandStructureSymmLineTest.test_get_direct_band_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_direct_band_gap)


            * [`BandStructureSymmLineTest.test_get_direct_band_gap_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_direct_band_gap_dict)


            * [`BandStructureSymmLineTest.test_get_sym_eq_kpoints_and_degeneracy()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_sym_eq_kpoints_and_degeneracy)


            * [`BandStructureSymmLineTest.test_get_vbm()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_get_vbm)


            * [`BandStructureSymmLineTest.test_is_metal()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_is_metal)


            * [`BandStructureSymmLineTest.test_old_format_load()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_old_format_load)


            * [`BandStructureSymmLineTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.BandStructureSymmLineTest.test_properties)


        * [`KpointTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.KpointTest)


            * [`KpointTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.KpointTest.setUp)


            * [`KpointTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.KpointTest.test_as_dict)


            * [`KpointTest.test_from_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.KpointTest.test_from_dict)


            * [`KpointTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.KpointTest.test_properties)


        * [`LobsterBandStructureSymmLineTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest)


            * [`LobsterBandStructureSymmLineTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.setUp)


            * [`LobsterBandStructureSymmLineTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.tearDown)


            * [`LobsterBandStructureSymmLineTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_as_dict)


            * [`LobsterBandStructureSymmLineTest.test_basic()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_basic)


            * [`LobsterBandStructureSymmLineTest.test_get_band_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_band_gap)


            * [`LobsterBandStructureSymmLineTest.test_get_branch()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_branch)


            * [`LobsterBandStructureSymmLineTest.test_get_cbm()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_cbm)


            * [`LobsterBandStructureSymmLineTest.test_get_direct_band_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_direct_band_gap)


            * [`LobsterBandStructureSymmLineTest.test_get_direct_band_gap_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_direct_band_gap_dict)


            * [`LobsterBandStructureSymmLineTest.test_get_sym_eq_kpoints_and_degeneracy()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_sym_eq_kpoints_and_degeneracy)


            * [`LobsterBandStructureSymmLineTest.test_get_vbm()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_get_vbm)


            * [`LobsterBandStructureSymmLineTest.test_is_metal()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_is_metal)


            * [`LobsterBandStructureSymmLineTest.test_old_format_load()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_old_format_load)


            * [`LobsterBandStructureSymmLineTest.test_proj_bandstructure_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.LobsterBandStructureSymmLineTest.test_proj_bandstructure_plot)


        * [`ReconstructBandStructureTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.ReconstructBandStructureTest)


            * [`ReconstructBandStructureTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.ReconstructBandStructureTest.setUp)


            * [`ReconstructBandStructureTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.ReconstructBandStructureTest.tearDown)


            * [`ReconstructBandStructureTest.test_reconstruct_band_structure()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.ReconstructBandStructureTest.test_reconstruct_band_structure)


            * [`ReconstructBandStructureTest.test_vasprun_bs()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_bandstructure.ReconstructBandStructureTest.test_vasprun_bs)


    * [pymatgen.electronic_structure.tests.test_boltztrap module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_boltztrap)


        * [`BoltztrapAnalyzerTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest)


            * [`BoltztrapAnalyzerTest.setUpClass()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.setUpClass)


            * [`BoltztrapAnalyzerTest.tearDownClass()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.tearDownClass)


            * [`BoltztrapAnalyzerTest.test_extreme()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_extreme)


            * [`BoltztrapAnalyzerTest.test_get_average_eff_mass()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_average_eff_mass)


            * [`BoltztrapAnalyzerTest.test_get_carrier_concentration()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_carrier_concentration)


            * [`BoltztrapAnalyzerTest.test_get_complete_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_complete_dos)


            * [`BoltztrapAnalyzerTest.test_get_complexity_factor()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_complexity_factor)


            * [`BoltztrapAnalyzerTest.test_get_conductivity()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_conductivity)


            * [`BoltztrapAnalyzerTest.test_get_hall_carrier_concentration()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_hall_carrier_concentration)


            * [`BoltztrapAnalyzerTest.test_get_power_factor()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_power_factor)


            * [`BoltztrapAnalyzerTest.test_get_seebeck()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_seebeck)


            * [`BoltztrapAnalyzerTest.test_get_seebeck_eff_mass()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_seebeck_eff_mass)


            * [`BoltztrapAnalyzerTest.test_get_symm_bands()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_symm_bands)


            * [`BoltztrapAnalyzerTest.test_get_thermal_conductivity()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_thermal_conductivity)


            * [`BoltztrapAnalyzerTest.test_get_zt()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_get_zt)


            * [`BoltztrapAnalyzerTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_properties)


            * [`BoltztrapAnalyzerTest.test_to_from_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap.BoltztrapAnalyzerTest.test_to_from_dict)


    * [pymatgen.electronic_structure.tests.test_boltztrap2 module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_boltztrap2)


        * [`BandstructureLoaderTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BandstructureLoaderTest)


            * [`BandstructureLoaderTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BandstructureLoaderTest.setUp)


            * [`BandstructureLoaderTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BandstructureLoaderTest.tearDown)


            * [`BandstructureLoaderTest.test_get_volume()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BandstructureLoaderTest.test_get_volume)


            * [`BandstructureLoaderTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BandstructureLoaderTest.test_properties)


        * [`BztInterpolatorTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest)


            * [`BztInterpolatorTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.setUp)


            * [`BztInterpolatorTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.tearDown)


            * [`BztInterpolatorTest.test_get_band_structure()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.test_get_band_structure)


            * [`BztInterpolatorTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.test_properties)


            * [`BztInterpolatorTest.test_tot_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.test_tot_dos)


            * [`BztInterpolatorTest.test_tot_proj_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztInterpolatorTest.test_tot_proj_dos)


        * [`BztPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztPlotterTest)


            * [`BztPlotterTest.test_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztPlotterTest.test_plot)


        * [`BztTransportPropertiesTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztTransportPropertiesTest)


            * [`BztTransportPropertiesTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztTransportPropertiesTest.setUp)


            * [`BztTransportPropertiesTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztTransportPropertiesTest.tearDown)


            * [`BztTransportPropertiesTest.test_compute_properties_doping()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztTransportPropertiesTest.test_compute_properties_doping)


            * [`BztTransportPropertiesTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.BztTransportPropertiesTest.test_properties)


        * [`VasprunBSLoaderTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunBSLoaderTest)


            * [`VasprunBSLoaderTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunBSLoaderTest.setUp)


            * [`VasprunBSLoaderTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunBSLoaderTest.tearDown)


            * [`VasprunBSLoaderTest.test_get_volume()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunBSLoaderTest.test_get_volume)


            * [`VasprunBSLoaderTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunBSLoaderTest.test_properties)


        * [`VasprunLoaderTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest)


            * [`VasprunLoaderTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest.setUp)


            * [`VasprunLoaderTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest.tearDown)


            * [`VasprunLoaderTest.test_from_file()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest.test_from_file)


            * [`VasprunLoaderTest.test_get_volume()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest.test_get_volume)


            * [`VasprunLoaderTest.test_properties()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_boltztrap2.VasprunLoaderTest.test_properties)


    * [pymatgen.electronic_structure.tests.test_cohp module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_cohp)


        * [`CohpTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest)


            * [`CohpTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.setUp)


            * [`CohpTest.test_antibnd_states_below_efermi()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_antibnd_states_below_efermi)


            * [`CohpTest.test_as_from_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_as_from_dict)


            * [`CohpTest.test_attributes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_attributes)


            * [`CohpTest.test_get_icohp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_get_icohp)


            * [`CohpTest.test_get_interpolated_value()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_get_interpolated_value)


            * [`CohpTest.test_str()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CohpTest.test_str)


        * [`CombinedIcohpTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest)


            * [`CombinedIcohpTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.setUp)


            * [`CombinedIcohpTest.test_extremum_icohpvalue()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.test_extremum_icohpvalue)


            * [`CombinedIcohpTest.test_get_icohp_by_label()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.test_get_icohp_by_label)


            * [`CombinedIcohpTest.test_get_icohp_dict_by_bondlengths()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.test_get_icohp_dict_by_bondlengths)


            * [`CombinedIcohpTest.test_get_icohp_dict_of_site()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.test_get_icohp_dict_of_site)


            * [`CombinedIcohpTest.test_get_summed_icohp_by_label_list()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CombinedIcohpTest.test_get_summed_icohp_by_label_list)


        * [`CompleteCohpTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest)


            * [`CompleteCohpTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.setUp)


            * [`CompleteCohpTest.test_attributes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_attributes)


            * [`CompleteCohpTest.test_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_dict)


            * [`CompleteCohpTest.test_get_cohp_by_label()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_cohp_by_label)


            * [`CompleteCohpTest.test_get_cohp_by_label_summed_spin()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_cohp_by_label_summed_spin)


            * [`CompleteCohpTest.test_get_summed_cohp_by_label_and_orbital_list()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_summed_cohp_by_label_and_orbital_list)


            * [`CompleteCohpTest.test_get_summed_cohp_by_label_and_orbital_list_summed_spin_channels()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_summed_cohp_by_label_and_orbital_list_summed_spin_channels)


            * [`CompleteCohpTest.test_get_summed_cohp_by_label_list()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_summed_cohp_by_label_list)


            * [`CompleteCohpTest.test_get_summed_cohp_by_label_list_summed_spin()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_get_summed_cohp_by_label_list_summed_spin)


            * [`CompleteCohpTest.test_icohp_values()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_icohp_values)


            * [`CompleteCohpTest.test_orbital_resolved_cohp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_orbital_resolved_cohp)


            * [`CompleteCohpTest.test_orbital_resolved_cohp_summed_spin_channels()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.CompleteCohpTest.test_orbital_resolved_cohp_summed_spin_channels)


        * [`IcohpValueTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest)


            * [`IcohpValueTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest.setUp)


            * [`IcohpValueTest.test_attributes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest.test_attributes)


            * [`IcohpValueTest.test_icohpvalue()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest.test_icohpvalue)


            * [`IcohpValueTest.test_str()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest.test_str)


            * [`IcohpValueTest.test_summed_icohp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.IcohpValueTest.test_summed_icohp)


        * [`MethodTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.MethodTest)


            * [`MethodTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.MethodTest.setUp)


            * [`MethodTest.test_get_integrated_cohp_in_energy_range_full()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.MethodTest.test_get_integrated_cohp_in_energy_range_full)


            * [`MethodTest.test_get_integrated_cohp_in_energy_range_onefloat()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.MethodTest.test_get_integrated_cohp_in_energy_range_onefloat)


            * [`MethodTest.test_get_integrated_cohp_in_energy_range_whole_range()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_cohp.MethodTest.test_get_integrated_cohp_in_energy_range_whole_range)


    * [pymatgen.electronic_structure.tests.test_core module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_core)


        * [`MagmomTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest)


            * [`MagmomTest.test_equality()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_equality)


            * [`MagmomTest.test_get_consistent_set_and_saxis()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_get_consistent_set_and_saxis)


            * [`MagmomTest.test_get_moments()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_get_moments)


            * [`MagmomTest.test_have_consistent_saxis()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_have_consistent_saxis)


            * [`MagmomTest.test_init()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_init)


            * [`MagmomTest.test_is_collinear()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_is_collinear)


            * [`MagmomTest.test_negative()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_negative)


            * [`MagmomTest.test_relative_to_crystal_axes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.MagmomTest.test_relative_to_crystal_axes)


        * [`OrbitalTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.OrbitalTest)


            * [`OrbitalTest.test_cached()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.OrbitalTest.test_cached)


            * [`OrbitalTest.test_init()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.OrbitalTest.test_init)


        * [`SpinTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.SpinTest)


            * [`SpinTest.test_cached()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.SpinTest.test_cached)


            * [`SpinTest.test_from_int()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.SpinTest.test_from_int)


            * [`SpinTest.test_init()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_core.SpinTest.test_init)


    * [pymatgen.electronic_structure.tests.test_dos module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_dos)


        * [`CompleteDosTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest)


            * [`CompleteDosTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.setUp)


            * [`CompleteDosTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_as_dict)


            * [`CompleteDosTest.test_band_filling()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_band_filling)


            * [`CompleteDosTest.test_band_width()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_band_width)


            * [`CompleteDosTest.test_dos_fp_exceptions()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_dos_fp_exceptions)


            * [`CompleteDosTest.test_get_band_center()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_band_center)


            * [`CompleteDosTest.test_get_dos_fp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_dos_fp)


            * [`CompleteDosTest.test_get_dos_fp_similarity()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_dos_fp_similarity)


            * [`CompleteDosTest.test_get_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_gap)


            * [`CompleteDosTest.test_get_n_moment()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_n_moment)


            * [`CompleteDosTest.test_get_upper_band_edge()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_get_upper_band_edge)


            * [`CompleteDosTest.test_kurtosis()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_kurtosis)


            * [`CompleteDosTest.test_skewness()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_skewness)


            * [`CompleteDosTest.test_str()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_str)


            * [`CompleteDosTest.test_to_from_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.CompleteDosTest.test_to_from_dict)


        * [`DOSTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DOSTest)


            * [`DOSTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DOSTest.setUp)


            * [`DOSTest.test_get_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DOSTest.test_get_gap)


        * [`DosTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DosTest)


            * [`DosTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DosTest.setUp)


            * [`DosTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DosTest.test_as_dict)


            * [`DosTest.test_get_gap()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DosTest.test_get_gap)


            * [`DosTest.test_get_smeared_densities()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.DosTest.test_get_smeared_densities)


        * [`FermiDosTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.FermiDosTest)


            * [`FermiDosTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.FermiDosTest.setUp)


            * [`FermiDosTest.test_as_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.FermiDosTest.test_as_dict)


            * [`FermiDosTest.test_doping_fermi()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.FermiDosTest.test_doping_fermi)


        * [`LobsterCompleteDosTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest)


            * [`LobsterCompleteDosTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest.setUp)


            * [`LobsterCompleteDosTest.test_get_element_spd_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest.test_get_element_spd_dos)


            * [`LobsterCompleteDosTest.test_get_site_orbital_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest.test_get_site_orbital_dos)


            * [`LobsterCompleteDosTest.test_get_site_t2g_eg_resolved_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest.test_get_site_t2g_eg_resolved_dos)


            * [`LobsterCompleteDosTest.test_get_spd_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.LobsterCompleteDosTest.test_get_spd_dos)


        * [`SpinPolarizationTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.SpinPolarizationTest)


            * [`SpinPolarizationTest.test_spin_polarization()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_dos.SpinPolarizationTest.test_spin_polarization)


    * [pymatgen.electronic_structure.tests.test_plotter module](pymatgen.electronic_structure.tests.md#module-pymatgen.electronic_structure.tests.test_plotter)


        * [`BSDOSPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSDOSPlotterTest)


            * [`BSDOSPlotterTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSDOSPlotterTest.setUp)


            * [`BSDOSPlotterTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSDOSPlotterTest.tearDown)


            * [`BSDOSPlotterTest.test_methods()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSDOSPlotterTest.test_methods)


        * [`BSPlotterProjectedTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterProjectedTest)


            * [`BSPlotterProjectedTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterProjectedTest.setUp)


            * [`BSPlotterProjectedTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterProjectedTest.tearDown)


            * [`BSPlotterProjectedTest.test_methods()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterProjectedTest.test_methods)


        * [`BSPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest)


            * [`BSPlotterTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.setUp)


            * [`BSPlotterTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.tearDown)


            * [`BSPlotterTest.test_add_bs()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_add_bs)


            * [`BSPlotterTest.test_bs_plot_data()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_bs_plot_data)


            * [`BSPlotterTest.test_get_branch_steps()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_get_branch_steps)


            * [`BSPlotterTest.test_get_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_get_plot)


            * [`BSPlotterTest.test_get_ticks()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_get_ticks)


            * [`BSPlotterTest.test_interpolate_bands()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_interpolate_bands)


            * [`BSPlotterTest.test_rescale_distances()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BSPlotterTest.test_rescale_distances)


        * [`BoltztrapPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest)


            * [`BoltztrapPlotterTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.setUp)


            * [`BoltztrapPlotterTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.tearDown)


            * [`BoltztrapPlotterTest.test_plot_carriers()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_carriers)


            * [`BoltztrapPlotterTest.test_plot_complexity_factor_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_complexity_factor_mu)


            * [`BoltztrapPlotterTest.test_plot_conductivity_dop()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_conductivity_dop)


            * [`BoltztrapPlotterTest.test_plot_conductivity_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_conductivity_mu)


            * [`BoltztrapPlotterTest.test_plot_conductivity_temp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_conductivity_temp)


            * [`BoltztrapPlotterTest.test_plot_dos()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_dos)


            * [`BoltztrapPlotterTest.test_plot_eff_mass_dop()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_eff_mass_dop)


            * [`BoltztrapPlotterTest.test_plot_eff_mass_temp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_eff_mass_temp)


            * [`BoltztrapPlotterTest.test_plot_hall_carriers()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_hall_carriers)


            * [`BoltztrapPlotterTest.test_plot_power_factor_dop()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_power_factor_dop)


            * [`BoltztrapPlotterTest.test_plot_power_factor_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_power_factor_mu)


            * [`BoltztrapPlotterTest.test_plot_power_factor_temp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_power_factor_temp)


            * [`BoltztrapPlotterTest.test_plot_seebeck_dop()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_seebeck_dop)


            * [`BoltztrapPlotterTest.test_plot_seebeck_eff_mass_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_seebeck_eff_mass_mu)


            * [`BoltztrapPlotterTest.test_plot_seebeck_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_seebeck_mu)


            * [`BoltztrapPlotterTest.test_plot_seebeck_temp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_seebeck_temp)


            * [`BoltztrapPlotterTest.test_plot_zt_dop()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_zt_dop)


            * [`BoltztrapPlotterTest.test_plot_zt_mu()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_zt_mu)


            * [`BoltztrapPlotterTest.test_plot_zt_temp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.BoltztrapPlotterTest.test_plot_zt_temp)


        * [`CohpPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest)


            * [`CohpPlotterTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.setUp)


            * [`CohpPlotterTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.tearDown)


            * [`CohpPlotterTest.test_add_cohp_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.test_add_cohp_dict)


            * [`CohpPlotterTest.test_attributes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.test_attributes)


            * [`CohpPlotterTest.test_get_cohp_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.test_get_cohp_dict)


            * [`CohpPlotterTest.test_get_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.test_get_plot)


            * [`CohpPlotterTest.test_save_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.CohpPlotterTest.test_save_plot)


        * [`DosPlotterTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest)


            * [`DosPlotterTest.get_plot_attributes()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.get_plot_attributes)


            * [`DosPlotterTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.setUp)


            * [`DosPlotterTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.tearDown)


            * [`DosPlotterTest.test_add_dos_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.test_add_dos_dict)


            * [`DosPlotterTest.test_get_dos_dict()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.test_get_dos_dict)


            * [`DosPlotterTest.test_get_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.test_get_plot)


            * [`DosPlotterTest.test_get_plot_limits()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.DosPlotterTest.test_get_plot_limits)


        * [`PlotBZTest`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.PlotBZTest)


            * [`PlotBZTest.setUp()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.PlotBZTest.setUp)


            * [`PlotBZTest.tearDown()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.PlotBZTest.tearDown)


            * [`PlotBZTest.test_bz_plot()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.PlotBZTest.test_bz_plot)


            * [`PlotBZTest.test_fold_point()`](pymatgen.electronic_structure.tests.md#pymatgen.electronic_structure.tests.test_plotter.PlotBZTest.test_fold_point)



## pymatgen.electronic_structure.bandstructure module

This module provides classes to define everything related to band structures.


### _class_ pymatgen.electronic_structure.bandstructure.BandStructure(kpoints: np.ndarray, eigenvals: dict[Spin, np.ndarray], lattice: [Lattice](pymatgen.core.md#pymatgen.core.lattice.Lattice), efermi: float, labels_dict=None, coords_are_cartesian: bool = False, structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure) | None = None, projections: dict[Spin, np.ndarray] | None = None)
Bases: `object`

This is the most generic band structure data possible
it’s defined by a list of kpoints + energies for each of them.


### kpoints:()

### the list of kpoints (as Kpoint objects) in the band structure()

#### lattice_rec()
the reciprocal lattice of the band structure.


#### efermi()
the fermi energy


#### is_spin_polarized()
True if the band structure is spin-polarized, False otherwise


#### bands()
The energy eigenvalues as a {spin: ndarray}. Note that the use of an
ndarray is necessary for computational as well as memory efficiency
due to the large amount of numerical data. The indices of the ndarray
are [band_index, kpoint_index].


#### nb_bands()
returns the number of bands in the band structure


#### structure()
returns the structure


#### projections()
The projections as a {spin: ndarray}. Note that the use of an
ndarray is necessary for computational as well as memory efficiency
due to the large amount of numerical data. The indices of the ndarray
are [band_index, kpoint_index, orbital_index, ion_index].


* **Parameters**


    * **kpoints** – list of kpoint as numpy arrays, in frac_coords of the
    given lattice by default


    * **eigenvals** – dict of energies for spin up and spin down
    {Spin.up:[][],Spin.down:[][]}, the first index of the array
    [][] refers to the band and the second to the index of the
    kpoint. The kpoints are ordered according to the order of the
    kpoints array. If the band structure is not spin polarized, we
    only store one data set under Spin.up


    * **lattice** – The reciprocal lattice as a pymatgen Lattice object.
    Pymatgen uses the physics convention of reciprocal lattice vectors
    WITH a 2\*pi coefficient


    * **efermi** (*float*) – fermi energy


    * **labels_dict** – (dict) of {} this links a kpoint (in frac coords or
    Cartesian coordinates depending on the coords) to a label.


    * **coords_are_cartesian** – Whether coordinates are cartesian.


    * **structure** – The crystal structure (as a pymatgen Structure object)
    associated with the band structure. This is needed if we
    provide projections to the band structure


    * **projections** – dict of orbital projections as {spin: ndarray}. The
    indices of the ndarrayare [band_index, kpoint_index, orbital_index,
    ion_index].If the band structure is not spin polarized, we only
    store one data set under Spin.up.



#### as_dict()
JSON-serializable dict representation of BandStructure.


#### _classmethod_ from_dict(dct)
Create from dict.


* **Parameters**

    **dct** – A dict with all data for a band structure object.



* **Returns**

    A BandStructure object



#### _classmethod_ from_old_dict(dct)

* **Parameters**

    **dct** (*dict*) – A dict with all data for a band structure symmetry line object.



* **Returns**

    A BandStructureSymmLine object



#### get_band_gap()
Returns band gap data.


* **Returns**

    “energy”: band gap energy
    “direct”: A boolean telling if the gap is direct or not
    “transition”: kpoint labels of the transition (e.g., “\\Gamma-X”)



* **Return type**

    A dict {“energy”,”direct”,”transition”}



#### get_cbm()
Returns data about the CBM.


* **Returns**

    {“band_index”,”kpoint_index”,”kpoint”,”energy”}
    - “band_index”: A dict with spin keys pointing to a list of the
    indices of the band containing the CBM (please note that you
    can have several bands sharing the CBM) {Spin.up:[],
    Spin.down:[]}
    - “kpoint_index”: The list of indices in self.kpoints for the
    kpoint CBM. Please note that there can be several
    kpoint_indices relating to the same kpoint (e.g., Gamma can
    occur at different spots in the band structure line plot)
    - “kpoint”: The kpoint (as a kpoint object)
    - “energy”: The energy of the CBM
    - “projections”: The projections along sites and orbitals of the
    CBM if any projection data is available (else it is an empty
    dictionary). The format is similar to the projections field in
    BandStructure: {spin:{‘Orbital’: [proj]}} where the array
    [proj] is ordered according to the sites in structure



#### get_direct_band_gap()
Returns the direct band gap.


* **Returns**

    the value of the direct band gap



#### get_direct_band_gap_dict()
Returns a dictionary of information about the direct
band gap.


* **Returns**

    a dictionary of the band gaps indexed by spin
    along with their band indices and k-point index



#### get_kpoint_degeneracy(kpoint, cartesian=False, tol: float = 0.01)
Returns degeneracy of a given k-point based on structure symmetry
:param kpoint: coordinate of the k-point
:type kpoint: 1x3 array
:param cartesian: kpoint is in Cartesian or fractional coordinates
:type cartesian: bool
:param tol: tolerance below which coordinates are considered equal.
:type tol: float


* **Returns**

    degeneracy or None if structure is not available



* **Return type**

    (int or None)



#### get_projection_on_elements()
Method returning a dictionary of projections on elements.


* **Returns**

    [][{Element:values}],
    Spin.down:[][{Element:values}]} format
    if there is no projections in the band structure
    returns an empty dict



* **Return type**

    a dictionary in the {Spin.up



#### get_projections_on_elements_and_orbitals(el_orb_spec)
Method returning a dictionary of projections on elements and specific
orbitals.


* **Parameters**

    **el_orb_spec** – A dictionary of Elements and Orbitals for which we want
    to have projections on. It is given as: {Element:[orbitals]},
    e.g., {‘Cu’:[‘d’,’s’]}



* **Returns**

    A dictionary of projections on elements in the
    {Spin.up:[][{Element:{orb:values}}],
    Spin.down:[][{Element:{orb:values}}]} format
    if there is no projections in the band structure returns an empty
    dict.



#### get_sym_eq_kpoints(kpoint, cartesian=False, tol: float = 0.01)
Returns a list of unique symmetrically equivalent k-points.


* **Parameters**


    * **kpoint** (*1x3 array*) – coordinate of the k-point


    * **cartesian** (*bool*) – kpoint is in Cartesian or fractional coordinates


    * **tol** (*float*) – tolerance below which coordinates are considered equal



* **Returns**

    if structure is not available returns None



* **Return type**

    ([1x3 array] or None)



#### get_vbm()
Returns data about the VBM.


* **Returns**

    dict as {“band_index”,”kpoint_index”,”kpoint”,”energy”}
    - “band_index”: A dict with spin keys pointing to a list of the
    indices of the band containing the VBM (please note that you
    can have several bands sharing the VBM) {Spin.up:[],
    Spin.down:[]}
    - “kpoint_index”: The list of indices in self.kpoints for the
    kpoint VBM. Please note that there can be several
    kpoint_indices relating to the same kpoint (e.g., Gamma can
    occur at different spots in the band structure line plot)
    - “kpoint”: The kpoint (as a kpoint object)
    - “energy”: The energy of the VBM
    - “projections”: The projections along sites and orbitals of the
    VBM if any projection data is available (else it is an empty
    dictionary). The format is similar to the projections field in
    BandStructure: {spin:{‘Orbital’: [proj]}} where the array
    [proj] is ordered according to the sites in structure



#### is_metal(efermi_tol=0.0001)
Check if the band structure indicates a metal by looking if the fermi
level crosses a band.


* **Returns**

    True if a metal, False if not



### _class_ pymatgen.electronic_structure.bandstructure.BandStructureSymmLine(kpoints, eigenvals, lattice, efermi, labels_dict, coords_are_cartesian=False, structure=None, projections=None)
Bases: `BandStructure`, `MSONable`

This object stores band structures along selected (symmetry) lines in the
Brillouin zone. We call the different symmetry lines (ex: \\Gamma to Z)
“branches”.


* **Parameters**


    * **kpoints** – list of kpoint as numpy arrays, in frac_coords of the
    given lattice by default


    * **eigenvals** – dict of energies for spin up and spin down
    {Spin.up:[][],Spin.down:[][]}, the first index of the array
    [][] refers to the band and the second to the index of the
    kpoint. The kpoints are ordered according to the order of the
    kpoints array. If the band structure is not spin polarized, we
    only store one data set under Spin.up.


    * **lattice** – The reciprocal lattice.
    Pymatgen uses the physics convention of reciprocal lattice vectors
    WITH a 2\*pi coefficient


    * **efermi** – fermi energy


    * **labels_dict** – (dict) of {} this link a kpoint (in frac coords or
    Cartesian coordinates depending on the coords).


    * **coords_are_cartesian** – Whether coordinates are cartesian.


    * **structure** – The crystal structure (as a pymatgen Structure object)
    associated with the band structure. This is needed if we
    provide projections to the band structure.


    * **projections** – dict of orbital projections as {spin: ndarray}. The
    indices of the ndarray are [band_index, kpoint_index, orbital_index,
    ion_index].If the band structure is not spin polarized, we only
    store one data set under Spin.up.



#### apply_scissor(new_band_gap)
Apply a scissor operator (shift of the CBM) to fit the given band gap.
If it’s a metal, we look for the band crossing the Fermi level
and shift this one up. This will not work all the time for metals!


* **Parameters**

    **new_band_gap** – the band gap the scissor band structure need to have.



* **Returns**

    with the applied scissor shift



* **Return type**

    BandStructureSymmLine



#### as_dict()
JSON-serializable dict representation of BandStructureSymmLine.


#### get_branch(index)
Returns in what branch(es) is the kpoint. There can be several
branches.


* **Parameters**

    **index** – the kpoint index



* **Returns**

    A list of dictionaries [{“name”,”start_index”,”end_index”,”index”}]
    indicating all branches in which the k_point is. It takes into
    account the fact that one kpoint (e.g., \\Gamma) can be in several
    branches



#### get_equivalent_kpoints(index)
Returns the list of kpoint indices equivalent (meaning they are the
same frac coords) to the given one.


* **Parameters**

    **index** – the kpoint index



* **Returns**

    a list of equivalent indices


TODO: now it uses the label we might want to use coordinates instead
(in case there was a mislabel)


### _class_ pymatgen.electronic_structure.bandstructure.Kpoint(coords, lattice, to_unit_cell=False, coords_are_cartesian=False, label=None)
Bases: `MSONable`

Class to store kpoint objects. A kpoint is defined with a lattice and frac
or Cartesian coordinates syntax similar than the site object in
pymatgen.core.structure.


* **Parameters**


    * **coords** – coordinate of the kpoint as a numpy array


    * **lattice** – A pymatgen.core.lattice.Lattice lattice object representing
    the reciprocal lattice of the kpoint


    * **to_unit_cell** – Translates fractional coordinate to the basic unit
    cell, i.e., all fractional coordinates satisfy 0 <= a < 1.
    Defaults to False.


    * **coords_are_cartesian** – Boolean indicating if the coordinates given are
    in Cartesian or fractional coordinates (by default fractional)


    * **label** – the label of the kpoint if any (None by default).



#### _property_ a()
Fractional a coordinate of the kpoint.


#### as_dict()
JSON-serializable dict representation of a kpoint.


#### _property_ b()
Fractional b coordinate of the kpoint.


#### _property_ c()
Fractional c coordinate of the kpoint.


#### _property_ cart_coords()
The Cartesian coordinates of the kpoint as a numpy array.


#### _property_ frac_coords()
The fractional coordinates of the kpoint as a numpy array.


#### _classmethod_ from_dict(dct)
Create from dict.


* **Parameters**

    **dct** (*dict*) – A dict with all data for a kpoint object.



* **Returns**

    A Kpoint object



#### _property_ label()
The label associated with the kpoint.


#### _property_ lattice()
The lattice associated with the kpoint. It’s a
pymatgen.core.lattice.Lattice object.


### _class_ pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine(kpoints, eigenvals, lattice, efermi, labels_dict, coords_are_cartesian=False, structure=None, projections=None)
Bases: `BandStructureSymmLine`

Lobster subclass of BandStructure with customized functions.


* **Parameters**


    * **kpoints** – list of kpoint as numpy arrays, in frac_coords of the
    given lattice by default


    * **eigenvals** – dict of energies for spin up and spin down
    {Spin.up:[][],Spin.down:[][]}, the first index of the array
    [][] refers to the band and the second to the index of the
    kpoint. The kpoints are ordered according to the order of the
    kpoints array. If the band structure is not spin polarized, we
    only store one data set under Spin.up.


    * **lattice** – The reciprocal lattice.
    Pymatgen uses the physics convention of reciprocal lattice vectors
    WITH a 2\*pi coefficient


    * **efermi** – fermi energy


    * **labels_dict** – (dict) of {} this link a kpoint (in frac coords or
    Cartesian coordinates depending on the coords).


    * **coords_are_cartesian** – Whether coordinates are cartesian.


    * **structure** – The crystal structure (as a pymatgen Structure object)
    associated with the band structure. This is needed if we
    provide projections to the band structure.


    * **projections** – dict of orbital projections as {spin: ndarray}. The
    indices of the ndarray are [band_index, kpoint_index, orbital_index,
    ion_index].If the band structure is not spin polarized, we only
    store one data set under Spin.up.



#### as_dict()
JSON-serializable dict representation of BandStructureSymmLine.


#### _classmethod_ from_dict(dct)

* **Parameters**

    **dct** (*dict*) – A dict with all data for a band structure symmetry line
    object.



* **Returns**

    A BandStructureSymmLine object



#### _classmethod_ from_old_dict(dct)

* **Parameters**

    **dct** (*dict*) – A dict with all data for a band structure symmetry line
    object.



* **Returns**

    A BandStructureSymmLine object



#### get_projection_on_elements()
Method returning a dictionary of projections on elements.
It sums over all available orbitals for each element.


* **Returns**

    [][{Element:values}],
    Spin.down:[][{Element:values}]} format
    if there is no projections in the band structure
    returns an empty dict



* **Return type**

    a dictionary in the {Spin.up



#### get_projections_on_elements_and_orbitals(el_orb_spec)
Method returning a dictionary of projections on elements and specific
orbitals.


* **Parameters**

    **el_orb_spec** – A dictionary of Elements and Orbitals for which we want
    to have projections on. It is given as: {Element:[orbitals]},
    e.g., {‘Si’:[‘3s’,’3p’]} or {‘Si’:[‘3s’,’3p_x’, ‘3p_y’, ‘3p_z’]} depending on input files



* **Returns**

    A dictionary of projections on elements in the
    {Spin.up:[][{Element:{orb:values}}],
    Spin.down:[][{Element:{orb:values}}]} format
    if there is no projections in the band structure returns an empty
    dict.



### pymatgen.electronic_structure.bandstructure.get_reconstructed_band_structure(list_bs, efermi=None)
This method takes a list of band structures and reconstructs
one band structure object from all of them.

This is typically very useful when you split non self consistent
band structure runs in several independent jobs and want to merge back
the results


* **Parameters**


    * **list_bs** – A list of BandStructure or BandStructureSymmLine objects.


    * **efermi** – The Fermi energy of the reconstructed band structure. If
    None is assigned an average of all the Fermi energy in each
    object in the list_bs is used.



* **Returns**

    A BandStructure or BandStructureSymmLine object (depending on
    the type of the list_bs objects)


## pymatgen.electronic_structure.boltztrap module

This module provides classes to run and analyze boltztrap on pymatgen band
structure objects. Boltztrap is a software interpolating band structures and
computing materials properties from this band structure using Boltzmann
semi-classical transport theory.

Boltztrap has been developed by Georg Madsen.

[http://www.icams.de/content/research/software-development/boltztrap/](http://www.icams.de/content/research/software-development/boltztrap/)

You need version 1.2.3 or higher

References are:

```default
Madsen, G. K. H., and Singh, D. J. (2006).
BoltzTraP. A code for calculating band-structure dependent quantities.
Computer Physics Communications, 175, 67-71
```


### _class_ pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer(gap=None, mu_steps=None, cond=None, seebeck=None, kappa=None, hall=None, doping=None, mu_doping=None, seebeck_doping=None, cond_doping=None, kappa_doping=None, hall_doping=None, intrans=None, dos=None, dos_partial=None, carrier_conc=None, vol=None, warning=None, bz_bands=None, bz_kpoints=None, fermi_surface_data=None)
Bases: `object`

Class used to store all the data from a boltztrap run.

Constructor taking directly all the data generated by Boltztrap. You
won’t probably use it directly but instead use the from_files and
from_dict methods.


* **Parameters**


    * **gap** – The gap after interpolation in eV


    * **mu_steps** – The steps of electron chemical potential (or Fermi
    level) in eV.


    * **cond** – The electronic conductivity tensor divided by a constant
    relaxation time (sigma/tau) at different temperature and
    fermi levels.
    The format is {temperature: [array of 3x3 tensors at each
    Fermi level in mu_steps]}. The units are 1/(Ohm\*m\*s).


    * **seebeck** – The Seebeck tensor at different temperatures and fermi
    levels. The format is {temperature: [array of 3x3 tensors at
    each Fermi level in mu_steps]}. The units are V/K


    * **kappa** – The electronic thermal conductivity tensor divided by a
    constant relaxation time (kappa/tau) at different temperature
    and fermi levels. The format is {temperature: [array of 3x3
    tensors at each Fermi level in mu_steps]}
    The units are W/(m\*K\*s)


    * **hall** – The hall tensor at different temperature and fermi levels
    The format is {temperature: [array of 27 coefficients list at
    each Fermi level in mu_steps]}
    The units are m^3/C


    * **doping** – The different doping levels that have been given to
    Boltztrap. The format is {‘p’:[],’n’:[]} with an array of
    doping levels. The units are cm^-3


    * **mu_doping** – Gives the electron chemical potential (or Fermi level)
    for a given set of doping.
    Format is {‘p’:{temperature: [fermi levels],’n’:{temperature:
    [fermi levels]}}
    the Fermi level array is ordered according to the doping
    levels in doping units for doping are in cm^-3 and for Fermi
    level in eV


    * **seebeck_doping** – The Seebeck tensor at different temperatures and
    doping levels. The format is {‘p’: {temperature: [Seebeck
    tensors]}, ‘n’:{temperature: [Seebeck tensors]}}
    The [Seebeck tensors] array is ordered according to the
    doping levels in doping units for doping are in cm^-3 and for
    Seebeck in V/K


    * **cond_doping** – The electronic conductivity tensor divided by a
    constant relaxation time (sigma/tau) at different
    temperatures and doping levels
    The format is {‘p’:{temperature: [conductivity tensors]},
    ‘n’:{temperature: [conductivity tensors]}}
    The [conductivity tensors] array is ordered according to the
    doping levels in doping units for doping are in cm^-3 and for
    conductivity in 1/(Ohm\*m\*s)


    * **kappa_doping** – The thermal conductivity tensor divided by a constant
    relaxation time (kappa/tau) at different temperatures and
    doping levels.
    The format is {‘p’:{temperature: [thermal conductivity
    tensors]},’n’:{temperature: [thermal conductivity tensors]}}
    The [thermal conductivity tensors] array is ordered according
    to the doping levels in doping units for doping are in cm^-3
    and for thermal conductivity in W/(m\*K\*s)


    * **hall_doping** – The Hall tensor at different temperatures and doping
    levels.
    The format is {‘p’:{temperature: [Hall tensors]},
    ‘n’:{temperature: [Hall tensors]}}
    The [Hall tensors] array is ordered according to the doping
    levels in doping and each Hall tensor is represented by a 27
    coefficients list.
    The units are m^3/C


    * **intrans** – a dictionary of inputs e.g. {“scissor”: 0.0}


    * **carrier_conc** – The concentration of carriers in electron (or hole)
    per unit cell


    * **dos** – The dos computed by Boltztrap given as a pymatgen Dos object


    * **dos_partial** – Data for the partial DOS projected on sites and
    orbitals


    * **vol** – Volume of the unit cell in angstrom cube (A^3)


    * **warning** – string if BoltzTraP outputted a warning, else None


    * **bz_bands** – Data for interpolated bands on a k-point line
    (run_type=BANDS)


    * **bz_kpoints** – k-point in reciprocal coordinates for interpolated
    bands (run_type=BANDS)


    * **fermi_surface_data** – energy values in a 3D grid imported from the
    output .cube file.



#### as_dict()

* **Returns**

    MSONable dict.



#### _static_ check_acc_bzt_bands(sbs_bz, sbs_ref, warn_thr=(0.03, 0.03))
Compare sbs_bz BandStructureSymmLine calculated with boltztrap with
the sbs_ref BandStructureSymmLine as reference (from MP for
instance), computing correlation and energy difference for eight bands
around the gap (semiconductors) or Fermi level (metals).
warn_thr is a threshold to get a warning in the accuracy of Boltztap
interpolated bands.
Return a dictionary with these keys:
- “N”: the index of the band compared; inside each there are:

>
> * “Corr”: correlation coefficient for the 8 compared bands


> * “Dist”: energy distance for the 8 compared bands


> * “branch_name”: energy distance for that branch


* “avg_corr”: average of correlation coefficient over the 8 bands


* “avg_dist”: average of energy distance over the 8 bands


* “nb_list”: list of indexes of the 8 compared bands


* “acc_thr”: list of two float corresponding to the two warning

    thresholds in input


* “acc_err”: list of two bools:

    True if the avg_corr > warn_thr[0], and
    True if the avg_dist > warn_thr[1]

See also compare_sym_bands function doc.


#### _static_ from_dict(data)

* **Parameters**

    **data** – Dict representation.



* **Returns**

    BoltztrapAnalyzer



#### _static_ from_files(path_dir, dos_spin=1)
get a BoltztrapAnalyzer object from a set of files.


* **Parameters**


    * **path_dir** – directory where the boltztrap files are


    * **dos_spin** – in DOS mode, set to 1 for spin up and -1 for spin down



* **Returns**

    a BoltztrapAnalyzer object



#### get_average_eff_mass(output='eigs', doping_levels=True)
Gives the average effective mass tensor. We call it average because
it takes into account all the bands
and regions in the Brillouin zone. This is different than the standard
textbook effective mass which relates
often to only one (parabolic) band.
The average effective mass tensor is defined as the integrated
average of the second derivative of E(k)
This effective mass tensor takes into account:
-non-parabolicity
-multiple extrema
-multiple bands.

For more information about it. See:

Hautier, G., Miglio, A., Waroquiers, D., Rignanese, G., & Gonze,
X. (2014).
How Does Chemistry Influence Electron Effective Mass in Oxides?
A High-Throughput Computational Analysis. Chemistry of Materials,
26(19), 5447-5458. doi:10.1021/cm404079a

or

Hautier, G., Miglio, A., Ceder, G., Rignanese, G.-M., & Gonze,
X. (2013).
Identification and design principles of low hole effective mass
p-type transparent conducting oxides.
Nature Communications, 4, 2292. doi:10.1038/ncomms3292

Depending on the value of output, we have either the full 3x3
effective mass tensor,
its 3 eigenvalues or an average


* **Parameters**


    * **output** (*str*) – ‘eigs’ for eigenvalues, ‘tensor’ for the full


    * **average** (*tensor and 'average' for an*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –



* **Returns**

    {temp:[]},’n’:{temp:[]}}
    with an array of effective mass tensor, eigenvalues of average
    value (depending on output) for each temperature and for each
    doping level.
    The ‘p’ links to hole effective mass tensor and ‘n’ to electron
    effective mass tensor.



* **Return type**

    If doping_levels=True,a dictionary {‘p’



#### get_carrier_concentration()
gives the carrier concentration (in cm^-3).


* **Returns**

    []} with an array of carrier concentration
    (in cm^-3) at each temperature
    The array relates to each step of electron chemical potential



* **Return type**

    a dictionary {temp



#### get_complete_dos(structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure), analyzer_for_second_spin=None)
Gives a CompleteDos object with the DOS from the interpolated projected band structure.


* **Parameters**


    * **structure** – necessary to identify sites for projection


    * **analyzer_for_second_spin** – must be specified to have a CompleteDos with both Spin components



* **Returns**

    a CompleteDos object


Example of use in case of spin polarized case:

> BoltztrapRunner(bs=bs,nelec=10,run_type=”DOS”,spin=1).run(path_dir=’dos_up/’)
> an_up=BoltztrapAnalyzer.from_files(“dos_up/boltztrap/”,dos_spin=1)

> BoltztrapRunner(bs=bs,nelec=10,run_type=”DOS”,spin=-1).run(path_dir=’dos_dw/’)
> an_dw=BoltztrapAnalyzer.from_files(“dos_dw/boltztrap/”,dos_spin=-1)

> cdos=an_up.get_complete_dos(bs.structure,an_dw)


#### get_complexity_factor(output='average', temp=300, doping_levels=False, Lambda=0.5)
Fermi surface complexity factor respect to calculated as explained in Ref.
Gibbs, Z. M. et al., Effective mass and fermi surface complexity factor
from ab initio band structure calculations.
npj Computational Materials 3, 8 (2017).


* **Parameters**


    * **output** – ‘average’ returns the complexity factor calculated using the average
    of the three diagonal components of the seebeck and conductivity tensors.
    ‘tensor’ returns the complexity factor respect to the three
    diagonal components of seebeck and conductivity tensors.


    * **doping_levels** – False means that the complexity factor is calculated
    for every value of the chemical potential
    True means that the complexity factor is calculated
    for every value of the doping levels for both n and p types


    * **temp** – temperature of calculated seebeck and conductivity.


    * **Lambda** – fitting parameter used to model the scattering (0.5 means constant
    relaxation time).



* **Returns**

    a list of values for the complexity factor w.r.t the chemical potential,
    if doping_levels is set at False;
    a dict with n an p keys that contain a list of values for the complexity factor
    w.r.t the doping levels, if doping_levels is set at True;
    if ‘tensor’ is selected, each element of the lists is a list containing
    the three components of the complexity factor.



#### get_conductivity(output='eigs', doping_levels=True, relaxation_time=1e-14)
Gives the conductivity (1/Ohm\*m) in either a full 3x3 tensor
form, as 3 eigenvalues, or as the average value
(trace/3.0) If doping_levels=True, the results are given at
different p and n doping
levels (given by self.doping), otherwise it is given as a series
of electron chemical potential values.


* **Parameters**


    * **output** (*str*) – the type of output. ‘tensor’ give the full


    * **tensor** (*3x3*) –


    * **and** (*'eigs' its 3 eigenvalues*) –


    * **eigenvalues** (*'average' the average** of **the three*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –


    * **relaxation_time** (*float*) – constant relaxation time in secs



* **Returns**

    {‘p’:[],’n’:[]}}.
    The ‘p’ links to conductivity
    at p-type doping and ‘n’ to the conductivity at n-type
    doping. Otherwise,
    returns a {temp:[]} dictionary. The result contains either
    the sorted three eigenvalues of the symmetric
    conductivity tensor (format=’eigs’) or a full tensor (3x3
    array) (output=’tensor’) or as an average
    (output=’average’).
    The result includes a given constant relaxation time

    units are 1/Ohm\*m




* **Return type**

    If doping_levels=True, a dictionary {temp



#### get_extreme(target_prop, maximize=True, min_temp=None, max_temp=None, min_doping=None, max_doping=None, isotropy_tolerance=0.05, use_average=True)
This method takes in eigenvalues over a range of carriers,
temperatures, and doping levels, and tells you what is the “best”
value that can be achieved for the given target_property. Note that
this method searches the doping dict only, not the full mu dict.


* **Parameters**


    * **target_prop** – target property, i.e. “seebeck”, “power factor”,
    “conductivity”, “kappa”, or “zt”


    * **maximize** – True to maximize, False to minimize (e.g. kappa)


    * **min_temp** – minimum temperature allowed


    * **max_temp** – maximum temperature allowed


    * **min_doping** – minimum doping allowed (e.g., 1E18)


    * **max_doping** – maximum doping allowed (e.g., 1E20)


    * **isotropy_tolerance** – tolerance for isotropic (0.05 = 5%)


    * **use_average** – True for avg of eigenval, False for max eigenval



* **Returns**

    {“value”, “temperature”, “doping”, “isotropic”}



* **Return type**

    A dictionary with keys {“p”, “n”, “best”} with sub-keys



#### get_hall_carrier_concentration()
gives the Hall carrier concentration (in cm^-3). This is the trace of
the Hall tensor (see Boltztrap source code) Hall carrier concentration
are not always exactly the same than carrier concentration.


* **Returns**

    []} with an array of Hall carrier concentration
    (in cm^-3) at each temperature The array relates to each step of
    electron chemical potential



* **Return type**

    a dictionary {temp



#### get_mu_bounds(temp=300)

* **Parameters**

    **temp** – Temperature.



* **Returns**

    The chemical potential bounds at that temperature.



#### get_power_factor(output='eigs', doping_levels=True, relaxation_time=1e-14)
Gives the power factor (Seebeck^2 \* conductivity) in units
microW/(m\*K^2) in either a full 3x3 tensor form,
as 3 eigenvalues, or as the average value (trace/3.0) If
doping_levels=True, the results are given at
different p and n doping levels (given by self.doping), otherwise it
is given as a series of
electron chemical potential values.


* **Parameters**


    * **output** (*str*) – the type of output. ‘tensor’ give the full 3x3


    * **tensor** –


    * **and** (*'eigs' its 3 eigenvalues*) –


    * **eigenvalues** (*'average' the average** of **the three*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –


    * **relaxation_time** (*float*) – constant relaxation time in secs



* **Returns**

    {‘p’:[],’n’:[]}}. The
    ‘p’ links to power factor
    at p-type doping and ‘n’ to the conductivity at n-type doping.
    Otherwise,
    returns a {temp:[]} dictionary. The result contains either the
    sorted three eigenvalues of the symmetric
    power factor tensor (format=’eigs’) or a full tensor (3x3 array) (
    output=’tensor’) or as an average
    (output=’average’).
    The result includes a given constant relaxation time

    units are microW/(m K^2)




* **Return type**

    If doping_levels=True, a dictionary {temp



#### get_seebeck(output='eigs', doping_levels=True)
Gives the seebeck coefficient (microV/K) in either a
full 3x3 tensor form, as 3 eigenvalues, or as the average value
(trace/3.0) If doping_levels=True, the results are given at
different p and n doping
levels (given by self.doping), otherwise it is given as a series
of electron chemical potential values.


* **Parameters**


    * **output** (*str*) – the type of output. ‘tensor’ give the full


    * **tensor** (*3x3*) –


    * **and** (*'eigs' its 3 eigenvalues*) –


    * **eigenvalues** (*'average' the average** of **the three*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –



* **Returns**

    {‘p’:[],’n’:[]}}.
    The ‘p’ links to Seebeck at p-type doping
    and ‘n’ to the Seebeck at n-type doping. Otherwise, returns a
    {temp:[]} dictionary
    The result contains either the sorted three eigenvalues of
    the symmetric
    Seebeck tensor (output=’eigs’) or a full tensor (3x3 array) (
    output=’tensor’) or as an average
    (output=’average’).

    units are microV/K




* **Return type**

    If doping_levels=True, a dictionary {temp



#### get_seebeck_eff_mass(output='average', temp=300, doping_levels=False, Lambda=0.5)
Seebeck effective mass calculated as explained in Ref.
Gibbs, Z. M. et al., Effective mass and fermi surface complexity factor
from ab initio band structure calculations.
npj Computational Materials 3, 8 (2017).


* **Parameters**


    * **output** – ‘average’ returns the seebeck effective mass calculated using
    the average of the three diagonal components of the seebeck tensor.
    ‘tensor’ returns the seebeck effective mass respect to the three
    diagonal components of the seebeck tensor.


    * **doping_levels** – False means that the seebeck effective mass is calculated
    for every value of the chemical potential
    True means that the seebeck effective mass is calculated
    for every value of the doping levels for both n and p types


    * **temp** – temperature of calculated seebeck.


    * **Lambda** – fitting parameter used to model the scattering (0.5 means constant
    relaxation time).



* **Returns**

    a list of values for the seebeck effective mass w.r.t the chemical potential,
    if doping_levels is set at False;
    a dict with n an p keys that contain a list of values for the seebeck effective
    mass w.r.t the doping levels, if doping_levels is set at True;
    if ‘tensor’ is selected, each element of the lists is a list containing
    the three components of the seebeck effective mass.



#### get_symm_bands(structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure), efermi, kpt_line=None, labels_dict=None)
Function useful to read bands from Boltztrap output and get a
BandStructureSymmLine object comparable with that one from a DFT
calculation (if the same kpt_line is provided). Default kpt_line
and labels_dict is the standard path of high symmetry k-point for
the specified structure. They could be extracted from the
BandStructureSymmLine object that you want to compare with. efermi
variable must be specified to create the BandStructureSymmLine
object (usually it comes from DFT or Boltztrap calc).


#### get_thermal_conductivity(output='eigs', doping_levels=True, k_el=True, relaxation_time=1e-14)
Gives the electronic part of the thermal conductivity in either a
full 3x3 tensor form,
as 3 eigenvalues, or as the average value (trace/3.0) If
doping_levels=True, the results are given at
different p and n doping levels (given by self.doping), otherwise it
is given as a series of
electron chemical potential values.


* **Parameters**


    * **output** (*str*) – the type of output. ‘tensor’ give the full 3x3


    * **tensor** –


    * **and** (*'eigs' its 3 eigenvalues*) –


    * **eigenvalues** (*'average' the average** of **the three*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –


    * **k_el** (*bool*) – True for k_0-PF\*T, False for k_0


    * **relaxation_time** (*float*) – constant relaxation time in secs



* **Returns**

    {‘p’:[],’n’:[]}}. The
    ‘p’ links to thermal conductivity
    at p-type doping and ‘n’ to the thermal conductivity at n-type
    doping. Otherwise,
    returns a {temp:[]} dictionary. The result contains either the
    sorted three eigenvalues of the symmetric
    conductivity tensor (format=’eigs’) or a full tensor (3x3 array) (
    output=’tensor’) or as an average
    (output=’average’).
    The result includes a given constant relaxation time

    units are W/mK




* **Return type**

    If doping_levels=True, a dictionary {temp



#### get_zt(output='eigs', doping_levels=True, relaxation_time=1e-14, k_l=1)
Gives the ZT coefficient (S^2\*cond\*T/thermal cond) in either a full
3x3 tensor form,
as 3 eigenvalues, or as the average value (trace/3.0) If
doping_levels=True, the results are given at
different p and n doping levels (given by self.doping), otherwise it
is given as a series of
electron chemical potential values. We assume a constant relaxation
time and a constant
lattice thermal conductivity.


* **Parameters**


    * **output** (*str*) – the type of output. ‘tensor’ give the full 3x3


    * **tensor** –


    * **and** (*'eigs' its 3 eigenvalues*) –


    * **eigenvalues** (*'average' the average** of **the three*) –


    * **doping_levels** (*bool*) – True for the results to be given at


    * **levels** (*different doping*) –


    * **results** (*False for*) –


    * **potentials** (*at different electron chemical*) –


    * **relaxation_time** (*float*) – constant relaxation time in secs


    * **k_l** (*float*) – lattice thermal cond in W/(m\*K)



* **Returns**

    {‘p’:[],’n’:[]}}. The
    ‘p’ links to ZT
    at p-type doping and ‘n’ to the ZT at n-type doping. Otherwise,
    returns a {temp:[]} dictionary. The result contains either the
    sorted three eigenvalues of the symmetric
    ZT tensor (format=’eigs’) or a full tensor (3x3 array) (
    output=’tensor’) or as an average
    (output=’average’).
    The result includes a given constant relaxation time and lattice
    thermal conductivity



* **Return type**

    If doping_levels=True, a dictionary {temp



#### _static_ parse_cond_and_hall(path_dir, doping_levels=None)
Parses the conductivity and Hall tensors
:param path_dir: Path containing .condtens / .halltens files
:param doping_levels: ([float]) - doping lvls, parse outtrans to get this.


* **Returns**

    mu_steps, cond, seebeck, kappa, hall, pn_doping_levels,
    mu_doping, seebeck_doping, cond_doping, kappa_doping,
    hall_doping, carrier_conc



#### _static_ parse_intrans(path_dir)
Parses boltztrap.intrans mainly to extract the value of scissor applied
to the bands or some other inputs.


* **Parameters**

    **path_dir** – (str) dir containing the boltztrap.intrans file



* **Returns**

    a dictionary containing various inputs that had

        been used in the Boltztrap run.




* **Return type**

    intrans (dict)



#### _static_ parse_outputtrans(path_dir)
Parses .outputtrans file.


* **Parameters**

    **path_dir** – dir containing boltztrap.outputtrans



* **Returns**

    tuple - (run_type, warning, efermi, gap, doping_levels)



#### _static_ parse_struct(path_dir)
Parses boltztrap.struct file (only the volume).


* **Parameters**

    **path_dir** – (str) dir containing the boltztrap.struct file



* **Returns**

    (float) volume



#### _static_ parse_transdos(path_dir, efermi, dos_spin=1, trim_dos=False)
Parses .transdos (total DOS) and .transdos_x_y (partial DOS) files
:param path_dir: (str) dir containing DOS files
:param efermi: (float) Fermi energy
:param dos_spin: (int) -1 for spin down, +1 for spin up
:param trim_dos: (bool) whether to post-process / trim DOS.


* **Returns**

    tuple - (DOS, dict of partial DOS)



### _exception_ pymatgen.electronic_structure.boltztrap.BoltztrapError()
Bases: `Exception`

Exception class for boltztrap.
Raised when the boltztrap gives an error.


### _class_ pymatgen.electronic_structure.boltztrap.BoltztrapRunner(bs, nelec, dos_type='HISTO', energy_grid=0.005, lpfac=10, run_type='BOLTZ', band_nb=None, tauref=0, tauexp=0, tauen=0, soc=False, doping=None, energy_span_around_fermi=1.5, scissor=0.0, kpt_line=None, spin=None, cond_band=False, tmax=1300, tgrid=50, symprec=0.001, cb_cut=10, timeout=7200)
Bases: `MSONable`

This class is used to run Boltztrap on a band structure object.


* **Parameters**


    * **bs** – A band structure object


    * **nelec** – the number of electrons


    * **dos_type** – two options for the band structure integration: “HISTO”
    (histogram) or “TETRA” using the tetrahedon method. TETRA
    typically gives better results (especially for DOSes)
    but takes more time


    * **energy_grid** – the energy steps used for the integration (eV)


    * **lpfac** – the number of interpolation points in the real space. By
    default 10 gives 10 time more points in the real space than
    the number of kpoints given in reciprocal space


    * **run_type** – type of boltztrap usage. by default
    - BOLTZ: (default) compute transport coefficients
    - BANDS: interpolate all bands contained in the energy range
    specified in energy_span_around_fermi variable, along specified
    k-points
    - DOS: compute total and partial dos (custom BoltzTraP code
    needed!)
    - FERMI: compute fermi surface or more correctly to
    get certain bands interpolated


    * **band_nb** – indicates a band number. Used for Fermi Surface interpolation
    (run_type=”FERMI”)


    * **spin** – specific spin component (1: up, -1: down) of the band selected
    in FERMI mode (mandatory).


    * **cond_band** – if a conduction band is specified in FERMI mode,
    set this variable as True


    * **tauref** – reference relaxation time. Only set to a value different than
    zero if we want to model beyond the constant relaxation time.


    * **tauexp** – exponent for the energy in the non-constant relaxation time
    approach


    * **tauen** – reference energy for the non-constant relaxation time approach


    * **soc** – results from spin-orbit coupling (soc) computations give
    typically non-polarized (no spin up or down) results but single
    electron occupations. If the band structure comes from a soc
    computation, you should set soc to True (default False)


    * **doping** – the fixed doping levels you want to compute. Boltztrap provides
    both transport values depending on electron chemical potential
    (fermi energy) and for a series of fixed carrier
    concentrations. By default, this is set to 1e16 to 1e22 in
    increments of factors of 10.


    * **energy_span_around_fermi** – usually the interpolation is not needed on the entire energy
    range but on a specific range around the Fermi level.
    This energy gives this range in eV. by default it is 1.5 eV.
    If DOS or BANDS type are selected, this range is automatically
    set to cover the entire energy range.


    * **scissor** – scissor to apply to the band gap (eV). This applies a scissor
    operation moving the band edges without changing the band
    shape. This is useful to correct the often underestimated band
    gap in DFT. Default is 0.0 (no scissor)


    * **kpt_line** – list of fractional coordinates of kpoints as arrays or list of
    Kpoint objects for BANDS mode calculation (standard path of
    high symmetry k-points is automatically set as default)


    * **tmax** – Maximum temperature (K) for calculation (default=1300)


    * **tgrid** – Temperature interval for calculation (default=50)


    * **symprec** – 1e-3 is the default in pymatgen. If the kmesh has been
    generated using a different symprec, it has to be specified
    to avoid a “factorization error” in BoltzTraP calculation.
    If a kmesh that spans the whole Brillouin zone has been used,
    or to disable all the symmetries, set symprec to None.


    * **cb_cut** – by default 10% of the highest conduction bands are
    removed because they are often not accurate.
    Tune cb_cut to change the percentage (0-100) of bands
    that are removed.


    * **timeout** – overall time limit (in seconds): mainly to avoid infinite
    loop when trying to find Fermi levels.



#### as_dict()

* **Returns**

    MSONable dict



#### _property_ bs()
The BandStructure


* **Type**

    return



#### _property_ nelec()
Number of electrons


* **Type**

    return



#### run(path_dir=None, convergence=True, write_input=True, clear_dir=False, max_lpfac=150, min_egrid=5e-05)
Write inputs (optional), run BoltzTraP, and ensure
convergence (optional).


* **Parameters**


    * **path_dir** (*str*) – directory in which to run BoltzTraP


    * **convergence** (*bool*) – whether to check convergence and make
    corrections if needed


    * **write_input** – (bool) whether to write input files before the run
    (required for convergence mode)


    * **clear_dir** – (bool) whether to remove all files in the path_dir
    before starting


    * **max_lpfac** – (float) maximum lpfac value to try before reducing egrid
    in convergence mode


    * **min_egrid** – (float) minimum egrid value to try before giving up in
    convergence mode



#### write_def(output_file)
Writes the def to an output file.


* **Parameters**

    **output_file** – Filename



#### write_energy(output_file)
Writes the energy to an output file.


* **Parameters**

    **output_file** – Filename



#### write_input(output_dir)
Writes the input files.


* **Parameters**

    **output_dir** – Directory to write the input files.



#### write_intrans(output_file)
Writes the intrans to an output file.


* **Parameters**

    **output_file** – Filename



#### write_proj(output_file_proj, output_file_def)
Writes the projections to an output file.


* **Parameters**

    **output_file** – Filename



#### write_struct(output_file)
Writes the structure to an output file.


* **Parameters**

    **output_file** – Filename



### pymatgen.electronic_structure.boltztrap.compare_sym_bands(bands_obj, bands_ref_obj, nb=None)
Compute the mean of correlation between bzt and vasp bandstructure on
sym line, for all bands and locally (for each branches) the difference
squared (%) if nb is specified.


### pymatgen.electronic_structure.boltztrap.eta_from_seebeck(seeb, Lambda)
It takes a value of seebeck and adjusts the analytic seebeck until it’s equal
Returns: eta where the two seebeck coefficients are equal
(reduced chemical potential).


### pymatgen.electronic_structure.boltztrap.read_cube_file(filename)

* **Parameters**

    **filename** – Cube filename



* **Returns**

    Energy data.



### pymatgen.electronic_structure.boltztrap.seebeck_eff_mass_from_carr(eta, n, T, Lambda)
Calculate seebeck effective mass at a certain carrier concentration
eta in kB\*T units, n in cm-3, T in K, returns mass in m0 units.


### pymatgen.electronic_structure.boltztrap.seebeck_eff_mass_from_seebeck_carr(seeb, n, T, Lambda)
Find the chemical potential where analytic and calculated seebeck are identical
and then calculate the seebeck effective mass at that chemical potential and
a certain carrier concentration n.


### pymatgen.electronic_structure.boltztrap.seebeck_spb(eta, Lambda=0.5)
Seebeck analytic formula in the single parabolic model.

## pymatgen.electronic_structure.boltztrap2 module

## pymatgen.electronic_structure.cohp module

This module defines classes to represent crystal orbital Hamilton
populations (COHP) and integrated COHP (ICOHP), but can also be used
for crystal orbital overlap populations (COOP) or crystal orbital bond indices (COBIs).
If you use this module, please cite:
J. George, G. Petretto, A. Naik, M. Esters, A. J. Jackson, R. Nelson, R. Dronskowski, G.-M. Rignanese, G. Hautier,
“Automated Bonding Analysis with Crystal Orbital Hamilton Populations”,
ChemPlusChem 2022, e202200123,
DOI: 10.1002/cplu.202200123.


### _class_ pymatgen.electronic_structure.cohp.Cohp(efermi, energies, cohp, are_coops=False, are_cobis=False, icohp=None)
Bases: `MSONable`

Basic COHP object.


* **Parameters**


    * **are_coops** – Indicates whether this object describes COOPs.


    * **are_cobis** – Indicates whether this object describes COBIs.


    * **efermi** – Fermi energy.


    * **energies** – A sequence of energies.


    * **(****{Spin** (*icohp*) – np.array}): representing the COHP for each spin.


    * **(****{Spin** – np.array}): representing the ICOHP for each spin.



#### as_dict()
JSON-serializable dict representation of COHP.


#### _classmethod_ from_dict(dct)
Returns a COHP object from a dict representation of the COHP.


#### get_cohp(spin=None, integrated=False)
Returns the COHP or ICOHP for a particular spin.


* **Parameters**


    * **spin** – Spin. Can be parsed as spin object, integer (-1/1)
    or str (“up”/”down”)


    * **integrated** – Return COHP (False) or ICOHP (True)



* **Returns**

    Returns the CHOP or ICOHP for the input spin. If Spin is
    None and both spins are present, both spins will be returned
    as a dictionary.



#### get_icohp(spin=None)
Convenient alternative to get the ICOHP for a particular spin.


#### get_interpolated_value(energy, integrated=False)
Returns the COHP for a particular energy.


* **Parameters**


    * **energy** – Energy to return the COHP value for.


    * **integrated** – Return COHP (False) or ICOHP (True)



#### has_antibnd_states_below_efermi(spin=None, limit=0.01)
Returns dict indicating if there are antibonding states below the Fermi level depending on the spin

    spin: Spin
    limit: -COHP smaller -limit will be considered.


### _class_ pymatgen.electronic_structure.cohp.CompleteCohp(structure, avg_cohp, cohp_dict, bonds=None, are_coops=False, are_cobis=False, orb_res_cohp=None)
Bases: `Cohp`

A wrapper class that defines an average COHP, and individual COHPs.

<!-- attribute: are_coops

Indicates whether the object is consisting of COOPs. -->
<!-- attribute: are_cobis

Indicates whether the object is consisting of COBIs. -->
<!-- attribute: efermi

Fermi energy -->
<!-- attribute: energies

Sequence of energies -->
<!-- attribute: structure

Structure associated with the COHPs. -->
<!-- attribute: cohp, icohp

The average COHP/ICOHP. -->
<!-- attribute: all_cohps

A dict of COHPs for individual bonds of the form {label: COHP} -->
<!-- attribute: orb_res_cohp

Orbital-resolved COHPs. -->

* **Parameters**


    * **structure** – Structure associated with this COHP.


    * **avg_cohp** – The average cohp as a COHP object.


    * **cohp_dict** – A dict of COHP objects for individual bonds of the form
    {label: COHP}


    * **bonds** – A dict containing information on the bonds of the form
    {label: {key: val}}. The key-val pair can be any information
    the user wants to put in, but typically contains the sites,
    the bond length, and the number of bonds. If nothing is
    supplied, it will default to an empty dict.


    * **are_coops** – indicates whether the Cohp objects are COOPs.
    Defaults to False for COHPs.


    * **are_cobis** – indicates whether the Cohp objects are COBIs.
    Defaults to False for COHPs.


    * **orb_res_cohp** – Orbital-resolved COHPs.



#### as_dict()
JSON-serializable dict representation of CompleteCohp.


#### _classmethod_ from_dict(d)
Returns CompleteCohp object from dict representation.


#### _classmethod_ from_file(fmt, filename=None, structure_file=None, are_coops=False, are_cobis=False)
Creates a CompleteCohp object from an output file of a COHP
calculation. Valid formats are either LMTO (for the Stuttgart
LMTO-ASA code) or LOBSTER (for the LOBSTER code).


* **Parameters**


    * **fmt** – A string for the code that was used to calculate
    the COHPs so that the output file can be handled
    correctly. Can take the values “LMTO” or “LOBSTER”.


    * **filename** – Name of the COHP output file. Defaults to COPL
    for LMTO and COHPCAR.lobster/COOPCAR.lobster for LOBSTER.


    * **structure_file** – Name of the file containing the structure.
    If no file name is given, use CTRL for LMTO and POSCAR
    for LOBSTER.


    * **are_coops** – Indicates whether the populations are COOPs or
    COHPs. Defaults to False for COHPs.


    * **are_cobis** – Indicates whether the populations are COBIs or
    COHPs. Defaults to False for COHPs.



* **Returns**

    A CompleteCohp object.



#### get_cohp_by_label(label, summed_spin_channels=False)
Get specific COHP object.


* **Parameters**


    * **label** – string (for newer Lobster versions: a number)


    * **summed_spin_channels** – bool, will sum the spin channels and return the sum in Spin.up if true



* **Returns**

    Returns the COHP object to simplify plotting



#### get_orbital_resolved_cohp(label, orbitals, summed_spin_channels=False)
Get orbital-resolved COHP.


* **Parameters**


    * **label** – bond label (Lobster: labels as in ICOHPLIST/ICOOPLIST.lobster).


    * **orbitals** – The orbitals as a label, or list or tuple of the form
    [(n1, orbital1), (n2, orbital2)]. Orbitals can either be str,
    int, or Orbital.


    * **summed_spin_channels** – bool, will sum the spin channels and return the sum in Spin.up if true



* **Returns**

    A Cohp object if CompleteCohp contains orbital-resolved cohp,
    or None if it doesn’t.


Note: It currently assumes that orbitals are str if they aren’t the

    other valid types. This is not ideal, but the easiest way to
    avoid unicode issues between python 2 and python 3.


#### get_summed_cohp_by_label_and_orbital_list(label_list, orbital_list, divisor=1, summed_spin_channels=False)
Returns a COHP object that includes a summed COHP divided by divisor.


* **Parameters**


    * **label_list** – list of labels for the COHP that should be included in the summed cohp


    * **orbital_list** – list of orbitals for the COHPs that should be included in the summed cohp (same order as
    label_list)


    * **divisor** – float/int, the summed cohp will be divided by this divisor


    * **summed_spin_channels** – bool, will sum the spin channels and return the sum in Spin.up if true



* **Returns**

    Returns a COHP object including a summed COHP



#### get_summed_cohp_by_label_list(label_list, divisor=1, summed_spin_channels=False)
Returns a COHP object that includes a summed COHP divided by divisor.


* **Parameters**


    * **label_list** – list of labels for the COHP that should be included in the summed cohp


    * **divisor** – float/int, the summed cohp will be divided by this divisor


    * **summed_spin_channels** – bool, will sum the spin channels and return the sum in Spin.up if true



* **Returns**

    Returns a COHP object including a summed COHP



### _class_ pymatgen.electronic_structure.cohp.IcohpCollection(list_labels, list_atom1, list_atom2, list_length, list_translation, list_num, list_icohp, is_spin_polarized, list_orb_icohp=None, are_coops=False, are_cobis=False)
Bases: `MSONable`

Class to store IcohpValues.


#### are_coops()

### Boolean to indicate if these are ICOOPs()

#### are_cobis()

### Boolean to indicate if these are ICOOPs()

#### is_spin_polarized()

### Boolean to indicate if the Lobster calculation was done spin polarized or not()

* **Parameters**


    * **list_labels** – list of labels for ICOHP/ICOOP values


    * **list_atom1** – list of str of atomnames e.g. “O1”


    * **list_atom2** – list of str of atomnames e.g. “O1”


    * **list_length** – list of lengths of corresponding bonds in Angstrom


    * **list_translation** – list of translation list, e.g. [0,0,0]


    * **list_num** – list of equivalent bonds, usually 1 starting from Lobster 3.0.0


    * **list_icohp** – list of dict={Spin.up: icohpvalue for spin.up, Spin.down: icohpvalue for spin.down}


    * **is_spin_polarized** – Boolean to indicate if the Lobster calculation was done spin polarized or not Boolean to
    indicate if the Lobster calculation was done spin polarized or not


    * **list_orb_icohp** – list of dict={[str(Orbital1)-str(Orbital2)]: {“icohp”:{Spin.up: icohpvalue for spin.up,
    Spin.down: icohpvalue for spin.down}, “orbitals”:[Orbital1, Orbital2]}}


    * **are_coops** – Boolean to indicate whether ICOOPs are stored


    * **are_cobis** – Boolean to indicate whether ICOBIs are stored.



#### _property_ are_cobis(_: boo_ )
Whether this a cobi.


* **Type**

    return



#### _property_ are_coops(_: boo_ )
Whether this is a coop.


* **Type**

    return



#### extremum_icohpvalue(summed_spin_channels=True, spin=Spin.up)
get ICOHP/ICOOP of strongest bond
:param summed_spin_channels: Boolean to indicate whether the ICOHPs/ICOOPs of both spin channels should be summed.
:param spin: if summed_spin_channels is equal to False, this spin indicates which spin channel should be returned


* **Returns**

    lowest ICOHP/largest ICOOP value (i.e. ICOHP/ICOOP value of strongest bond)



#### get_icohp_by_label(label, summed_spin_channels=True, spin=Spin.up, orbitals=None)
get an icohp value for a certain bond as indicated by the label (bond labels starting by “1” as in
ICOHPLIST/ICOOPLIST).


* **Parameters**


    * **label** – label in str format (usually the bond number in Icohplist.lobster/Icooplist.lobster


    * **summed_spin_channels** – Boolean to indicate whether the ICOHPs/ICOOPs of both spin channels should be summed


    * **spin** – if summed_spin_channels is equal to False, this spin indicates which spin channel should be returned


    * **orbitals** – List of Orbital or “str(Orbital1)-str(Orbital2)”



* **Returns**

    float describing ICOHP/ICOOP value



#### get_icohp_dict_by_bondlengths(minbondlength=0.0, maxbondlength=8.0)
get a dict of IcohpValues corresponding to certain bond lengths
:param minbondlength: defines the minimum of the bond lengths of the bonds
:param maxbondlength: defines the maximum of the bond lengths of the bonds


* **Returns**

    dict of IcohpValues, the keys correspond to the values from the initial list_labels.



#### get_icohp_dict_of_site(site, minsummedicohp=None, maxsummedicohp=None, minbondlength=0.0, maxbondlength=8.0, only_bonds_to=None)
get a dict of IcohpValue for a certain site (indicated by integer).


* **Parameters**


    * **site** – integer describing the site of interest, order as in Icohplist.lobster/Icooplist.lobster, starts at 0


    * **minsummedicohp** – float, minimal icohp/icoop of the bonds that are considered. It is the summed ICOHP value
    from both spin channels for spin polarized cases


    * **maxsummedicohp** – float, maximal icohp/icoop of the bonds that are considered. It is the summed ICOHP value
    from both spin channels for spin polarized cases


    * **minbondlength** – float, defines the minimum of the bond lengths of the bonds


    * **maxbondlength** – float, defines the maximum of the bond lengths of the bonds


    * **only_bonds_to** – list of strings describing the bonding partners that are allowed, e.g. [‘O’]



* **Returns**

    dict of IcohpValues, the keys correspond to the values from the initial list_labels



#### get_summed_icohp_by_label_list(label_list, divisor=1.0, summed_spin_channels=True, spin=Spin.up)
get the sum of several ICOHP values that are indicated by a list of labels (labels of the bonds are the same as
in ICOHPLIST/ICOOPLIST).


* **Parameters**


    * **label_list** – list of labels of the ICOHPs/ICOOPs that should be summed


    * **divisor** – is used to divide the sum


    * **summed_spin_channels** – Boolean to indicate whether the ICOHPs/ICOOPs of both spin channels should be summed


    * **spin** – if summed_spin_channels is equal to False, this spin indicates which spin channel should be returned



* **Returns**

    float that is a sum of all ICOHPs/ICOOPs as indicated with label_list



#### _property_ is_spin_polarized(_: boo_ )
Whether it is spin polarized.


* **Type**

    return



### _class_ pymatgen.electronic_structure.cohp.IcohpValue(label, atom1, atom2, length, translation, num, icohp, are_coops=False, are_cobis=False, orbitals=None)
Bases: `MSONable`

Class to store information on an ICOHP or ICOOP value.


#### num_bonds()

### number of bonds used for the average cohp (relevant for Lobster versions <3.0) (int)()

#### are_coops()

### Boolean to indicates ICOOPs()

#### are_cobis()

### Boolean to indicates ICOBIs()

#### icohp()

### dict={Spin.up: icohpvalue for spin.up, Spin.down: icohpvalue for spin.down}()

### summed_icohp:()

### sum of icohp/icoop of both spin channels()

* **Parameters**


    * **label** – label for the icohp


    * **atom1** – str of atom that is contributing to the bond


    * **atom2** – str of second atom that is contributing to the bond


    * **length** – float of bond lengths


    * **translation** – translation list, e.g. [0,0,0]


    * **num** – integer describing how often the bond exists


    * **icohp** – dict={Spin.up: icohpvalue for spin.up, Spin.down: icohpvalue for spin.down}


    * **are_coops** – if True, this are COOPs


    * **are_cobis** – if True, this are COBIs


    * **orbitals** – {[str(Orbital1)-str(Orbital2)]: {“icohp”:{Spin.up: icohpvalue for spin.up, Spin.down:
    icohpvalue for spin.down}, “orbitals”:[Orbital1, Orbital2]}}.



#### _property_ are_cobis(_: boo_ )
tells if ICOBIs or not
:returns: Boolean.


#### _property_ are_coops(_: boo_ )
tells if ICOOPs or not
:returns: Boolean.


#### _property_ icohp()
dict with icohps for spinup and spindown
:returns: icohpvalue for spin.up, Spin.down: icohpvalue for spin.down}.
:rtype: dict={Spin.up


#### icohpvalue(spin=Spin.up)

* **Parameters**

    **spin** – Spin.up or Spin.down



* **Returns**

    icohpvalue (float) corresponding to chosen spin.



#### icohpvalue_orbital(orbitals, spin=Spin.up)

* **Parameters**


    * **orbitals** – List of Orbitals or “str(Orbital1)-str(Orbital2)”


    * **spin** – Spin.up or Spin.down



* **Returns**

    icohpvalue (float) corresponding to chosen spin.



#### _property_ is_spin_polarized(_: boo_ )
tells if spin polarized calculation or not
:returns: Boolean.


#### _property_ num_bonds()
tells the number of bonds for which the ICOHP value is an average
:returns: Int.


#### _property_ summed_icohp()
Sums ICOHPs of both spin channels for spin polarized compounds
:returns: icohp value in eV.


#### _property_ summed_orbital_icohp()
Sums orbitals-resolved ICOHPs of both spin channels for spin-plarized compounds
:returns: icohp value in eV}.
:rtype: {“str(Orbital1)-str(Ortibal2)”


### pymatgen.electronic_structure.cohp.get_integrated_cohp_in_energy_range(cohp, label, orbital=None, energy_range=None, relative_E_Fermi=True, summed_spin_channels=True)
Method that can integrate completecohp objects which include data on integrated COHPs
:param cohp: CompleteCOHP object
:param label: label of the COHP data
:param orbital: If not None, a orbital resolved integrated COHP will be returned
:param energy_range: if None, returns icohp value at Fermi level;

> if float, integrates from this float up to the Fermi level;
> if [float,float], will integrate in between


* **Parameters**


    * **relative_E_Fermi** – if True, energy scale with E_Fermi at 0 eV is chosen


    * **summed_spin_channels** – if True, Spin channels will be summed.



* **Returns**

    float indicating the integrated COHP if summed_spin_channels==True, otherwise dict of the following form {
    Spin.up:float, Spin.down:float}


## pymatgen.electronic_structure.core module

This module provides core classes needed by all define electronic structure,
such as the Spin, Orbital, etc.


### _class_ pymatgen.electronic_structure.core.Magmom(moment, saxis=(0, 0, 1))
Bases: `MSONable`

New class in active development. Use with caution, feedback is
appreciated.

Class to handle magnetic moments. Defines the magnetic moment of a
site or species relative to a spin quantization axis. Designed for
use in electronic structure calculations.


* For the general case, Magmom can be specified by a vector,
e.g. m = Magmom([1.0, 1.0, 2.0]), and subscripts will work as
expected, e.g. m[0] gives 1.0


* For collinear calculations, Magmom can assumed to be scalar-like,
e.g. m = Magmom(5.0) will work as expected, e.g. float(m) gives 5.0

Both of these cases should be safe and shouldn’t give any surprises,
but more advanced functionality is available if required.

There also exist useful static methods for lists of magmoms:


* Magmom.are_collinear(magmoms) - if true, a collinear electronic
structure calculation can be safely initialized, with float(Magmom)
giving the expected scalar magnetic moment value


* Magmom.get_consistent_set_and_saxis(magmoms) - for non-collinear
electronic structure calculations, a global, consistent spin axis
has to be used. This method returns a list of Magmoms which all
share a common spin axis, along with the global spin axis.

All methods that take lists of magmoms will accept magmoms either as
Magmom objects or as scalars/lists and will automatically convert to
a Magmom representation internally.

The following methods are also particularly useful in the context of
VASP calculations:


* Magmom.get_xyz_magmom_with_001_saxis()


* Magmom.get_00t_magmom_with_xyz_saxis()

See VASP documentation for more information:

[https://cms.mpi.univie.ac.at/wiki/index.php/SAXIS](https://cms.mpi.univie.ac.at/wiki/index.php/SAXIS)


* **Parameters**


    * **moment** – magnetic moment, supplied as float or list/np.ndarray


    * **saxis** – spin axis, supplied as list/np.ndarray, parameter will
    be converted to unit vector (default is [0, 0, 1])



* **Returns**

    Magmom object



#### _static_ are_collinear(magmoms)
Method checks to see if a set of magnetic moments are collinear
with each other.
:param magmoms: list of magmoms (Magmoms, scalars or vectors)
:return: bool.


#### _classmethod_ from_global_moment_and_saxis(global_moment, saxis)
Convenience method to initialize Magmom from a given global
magnetic moment, i.e. magnetic moment with saxis=(0,0,1), and
provided saxis.

Method is useful if you do not know the components of your
magnetic moment in frame of your desired saxis.


* **Parameters**


    * **global_moment** –


    * **saxis** – desired saxis



* **Returns**




#### _classmethod_ from_moment_relative_to_crystal_axes(moment, lattice)
Obtaining a Magmom object from a magnetic moment provided
relative to crystal axes.

Used for obtaining moments from magCIF file.
:param moment: list of floats specifying vector magmom
:param lattice: Lattice
:return: Magmom


#### get_00t_magmom_with_xyz_saxis()
For internal implementation reasons, in non-collinear calculations VASP prefers the following.

> MAGMOM = 0 0 total_magnetic_moment
> SAXIS = x y z

to an equivalent:

> MAGMOM = x y z
> SAXIS = 0 0 1

This method returns a Magmom object with magnetic moment [0, 0, t],
where t is the total magnetic moment, and saxis rotated as required.

A consistent direction of saxis is applied such that t might be positive
or negative depending on the direction of the initial moment. This is useful
in the case of collinear structures, rather than constraining assuming
t is always positive.


* **Returns**

    Magmom



#### _static_ get_consistent_set_and_saxis(magmoms, saxis=None)
Method to ensure a list of magmoms use the same spin axis.
Returns a tuple of a list of Magmoms and their global spin axis.


* **Parameters**


    * **magmoms** – list of magmoms (Magmoms, scalars or vectors)


    * **saxis** – can provide a specific global spin axis



* **Returns**

    (list of Magmoms, global spin axis) tuple



#### get_moment(saxis=(0, 0, 1))
Get magnetic moment relative to a given spin quantization axis.
If no axis is provided, moment will be given relative to the
Magmom’s internal spin quantization axis, i.e. equivalent to
Magmom.moment.


* **Parameters**

    **saxis** – (list/numpy array) spin quantization axis



* **Returns**

    np.ndarray of length 3



#### get_moment_relative_to_crystal_axes(lattice)
If scalar magmoms, moments will be given arbitrarily along z.
Used for writing moments to magCIF file.


* **Parameters**

    **lattice** – Lattice



* **Returns**

    vector as list of floats



#### _static_ get_suggested_saxis(magmoms)
This method returns a suggested spin axis for a set of magmoms,
taking the largest magnetic moment as the reference. For calculations
with collinear spins, this would give a sensible saxis for a ncl
calculation.


* **Parameters**

    **magmoms** – list of magmoms (Magmoms, scalars or vectors)



* **Returns**

    np.ndarray of length 3



#### get_xyz_magmom_with_001_saxis()
Returns a Magmom in the default setting of saxis = [0, 0, 1] and
the magnetic moment rotated as required.


* **Returns**

    Magmom



#### _property_ global_moment()
Get the magnetic moment defined in an arbitrary global reference frame.


* **Returns**

    np.ndarray of length 3



#### _static_ have_consistent_saxis(magmoms)
This method checks that all Magmom objects in a list have a
consistent spin quantization axis. To write MAGMOM tags to a
VASP INCAR, a global SAXIS value for all magmoms has to be used.
If saxis are inconsistent, can create consistent set with:
Magmom.get_consistent_set(magmoms).


* **Parameters**

    **magmoms** – list of magmoms (Magmoms, scalars or vectors)



* **Returns**

    bool



#### _property_ projection()
Projects moment along spin quantisation axis. Useful for obtaining
collinear approximation for slightly non-collinear magmoms.


* **Returns**

    float



### _class_ pymatgen.electronic_structure.core.Orbital(value)
Bases: `Enum`

Enum type for specific orbitals. The indices are basically the order in
which the orbitals are reported in VASP and has no special meaning.


#### dx2(_ = _ )

#### dxy(_ = _ )

#### dxz(_ = _ )

#### dyz(_ = _ )

#### dz2(_ = _ )

#### f0(_ = 1_ )

#### f1(_ = 1_ )

#### f2(_ = 1_ )

#### f3(_ = 1_ )

#### f_1(_ = 1_ )

#### f_2(_ = 1_ )

#### f_3(_ = _ )

#### _property_ orbital_type()
Returns OrbitalType of an orbital.


#### px(_ = _ )

#### py(_ = _ )

#### pz(_ = _ )

#### s(_ = _ )

### _class_ pymatgen.electronic_structure.core.OrbitalType(value)
Bases: `Enum`

Enum type for orbital type. Indices are basically the azimuthal quantum
number, l.


#### d(_ = _ )

#### f(_ = _ )

#### p(_ = _ )

#### s(_ = _ )

### _class_ pymatgen.electronic_structure.core.Spin(value)
Bases: `Enum`

Enum type for Spin. Only up and down.
Usage: Spin.up, Spin.down.


#### down(_ = -_ )

#### up(_ = _ )
## pymatgen.electronic_structure.dos module

This module defines classes to represent the density of states, etc.


### _class_ pymatgen.electronic_structure.dos.CompleteDos(structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure), total_dos: Dos, pdoss: Mapping[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite), Mapping[Orbital, Mapping[Spin, ArrayLike]]], normalize: bool = False)
Bases: `Dos`

This wrapper class defines a total dos, and also provides a list of PDos.
Mainly used by pymatgen.io.vasp.Vasprun to create a complete Dos from
a vasprun.xml file. You are unlikely to try to generate this object
manually.


#### structure()
Structure associated with the CompleteDos.


#### pdos()
Dict of partial densities of the form {Site:{Orbital:{Spin:Densities}}}


* **Parameters**


    * **structure** – Structure associated with this particular DOS.


    * **total_dos** – total Dos for structure


    * **pdoss** – The pdoss are supplied as an {Site: {Orbital: {Spin:Densities}}}


    * **normalize** – Whether to normalize the densities by the volume of the structure.
    If True, the units of the densities are states/eV/Angstrom^3. Otherwise,
    the units are states/eV.



#### as_dict()
JSON-serializable dict representation of CompleteDos.


#### _static_ fp_to_dict(fp: NamedTuple)
Converts a fingerprint into a dictionary.


* **Parameters**

    **fp** – The DOS fingerprint to be converted into a dictionary



* **Returns**

    A dict of the fingerprint Keys=type, Values=np.ndarray(energies, densities)



* **Return type**

    dict



#### _classmethod_ from_dict(d)
Returns CompleteDos object from dict representation.


#### get_band_center(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None)
Compute the orbital-projected band center, defined as the first moment
relative to the Fermi level

> int_{-inf}^{+inf} rho(E)\*E dE/int_{-inf}^{+inf} rho(E) dE

based on the work of Hammer and Norskov, Surf. Sci., 343 (1995) where the
limits of the integration can be modified by erange and E is the set
of energies taken with respect to the Fermi level. Note that the band center
is often highly sensitive to the selected erange.


* **Parameters**


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.



* **Returns**

    band center in eV, often denoted epsilon_d for the d-band center



#### get_band_filling(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None)
Compute the orbital-projected band filling, defined as the zeroth moment
up to the Fermi level.


* **Parameters**


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.



* **Returns**

    band filling in eV, often denoted f_d for the d-band



#### get_band_kurtosis(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None)
Get the orbital-projected kurtosis, defined as the fourth standardized moment

    int_{-inf}^{+inf} rho(E)\*(E-E_center)^4 dE/int_{-inf}^{+inf} rho(E) dE)
    /
    (int_{-inf}^{+inf} rho(E)\*(E-E_center)^2 dE/int_{-inf}^{+inf} rho(E) dE))^2

where E_center is the orbital-projected band center, the limits of the integration can be
modified by erange, and E is the set of energies taken with respect to the Fermi level.
Note that the skewness is often highly sensitive to the selected erange.


* **Parameters**


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.



* **Returns**

    Orbital-projected kurtosis in eV



#### get_band_skewness(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None)
Get the orbital-projected skewness, defined as the third standardized moment

    int_{-inf}^{+inf} rho(E)\*(E-E_center)^3 dE/int_{-inf}^{+inf} rho(E) dE)
    /
    (int_{-inf}^{+inf} rho(E)\*(E-E_center)^2 dE/int_{-inf}^{+inf} rho(E) dE))^(3/2)

where E_center is the orbital-projected band center, the limits of the integration can be
modified by erange, and E is the set of energies taken with respect to the Fermi level.
Note that the skewness is often highly sensitive to the selected erange.


* **Parameters**


    * **band** – Orbitals to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.



* **Returns**

    Orbital-projected skewness in eV



#### get_band_width(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None)
Get the orbital-projected band width, defined as the square root of the second moment

    sqrt(int_{-inf}^{+inf} rho(E)\*(E-E_center)^2 dE/int_{-inf}^{+inf} rho(E) dE)

where E_center is the orbital-projected band center, the limits of the integration can be
modified by erange, and E is the set of energies taken with respect to the Fermi level.
Note that the band width is often highly sensitive to the selected erange.


* **Parameters**


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.



* **Returns**

    Orbital-projected band width in eV



#### get_dos_fp(type: str = 'summed_pdos', binning: bool = True, min_e: float | None = None, max_e: float | None = None, n_bins: int = 256, normalize: bool = True)
Generates the DOS fingerprint based on work of
F. Knoop, T. A. r Purcell, M. Scheffler, C. Carbogno, J. Open Source Softw. 2020, 5, 2671.
Source - [https://gitlab.com/vibes-developers/vibes/-/tree/master/vibes/materials_fp](https://gitlab.com/vibes-developers/vibes/-/tree/master/vibes/materials_fp)
Copyright (c) 2020 Florian Knoop, Thomas A.R.Purcell, Matthias Scheffler, Christian Carbogno.


* **Parameters**


    * **type** (*str*) – Specify fingerprint type needed can accept ‘{s/p/d/f/}summed_{pdos/tdos}’


    * **summed_pdos****)** (*(**default is*) –


    * **binning** (*bool*) – If true, the DOS fingerprint is binned using np.linspace and n_bins.
    Default is True.


    * **min_e** (*float*) – The minimum mode energy to include in the fingerprint (default is None)


    * **max_e** (*float*) – The maximum mode energy to include in the fingerprint (default is None)


    * **n_bins** (*int*) – Number of bins to be used in the fingerprint (default is 256)


    * **normalize** (*bool*) – If true, normalizes the area under fp to equal to 1. Default is True.



* **Raises**

    **ValueError** – If type is not one of the accepted values {s/p/d/f/}summed_{pdos/tdos}.



* **Returns**

    The electronic density of states fingerprint
    of format (energies, densities, type, n_bins)



* **Return type**

    Fingerprint(namedtuple)



#### _static_ get_dos_fp_similarity(fp1: NamedTuple, fp2: NamedTuple, col: int = 1, pt: int | str = 'All', normalize: bool = False, tanimoto: bool = False)
Calculates the similarity index (dot product) of two fingerprints.


* **Parameters**


    * **fp1** (*NamedTuple*) – The 1st dos fingerprint object


    * **fp2** (*NamedTuple*) – The 2nd dos fingerprint object


    * **col** (*int*) – The item in the fingerprints (0:energies,1: densities) to take the dot product of (default is 1)


    * **pt** (*int** or **str*) – The index of the point that the dot product is to be taken (default is All)


    * **normalize** (*bool*) – If True normalize the scalar product to 1 (default is False)


    * **tanimoto** (*bool*) – If True will compute Tanimoto index (default is False)



* **Raises**

    **ValueError** – If both tanimoto and normalize are set to True.


Returns:
Similarity index (float): The value of dot product


#### get_element_dos()
Get element projected Dos.


* **Returns**

    Dos}



* **Return type**

    dict of {Element



#### get_element_spd_dos(el: SpeciesLike)
Get element and spd projected Dos.


* **Parameters**

    **el** – Element in Structure.composition associated with CompleteDos



* **Returns**

    Dos}, e.g. {OrbitalType.s: Dos object, …}



* **Return type**

    dict of {OrbitalType



#### get_hilbert_transform(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None)
Return the Hilbert transform of the orbital-projected density of states,
often plotted for a Newns-Anderson analysis.


* **Parameters**


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **band** – Orbitals to get the band center of (default is d-band)



* **Returns**

    Hilbert transformation of the projected DOS.



#### get_n_moment(n: int, band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None, center: bool = True)
Get the nth moment of the DOS centered around the orbital-projected band center, defined as

    int_{-inf}^{+inf} rho(E)\*(E-E_center)^n dE/int_{-inf}^{+inf} rho(E) dE

where n is the order, E_center is the orbital-projected band center, the limits of the integration can be
modified by erange, and E is the set of energies taken with respect to the Fermi level. If center is False,
then the E_center reference is not used.


* **Parameters**


    * **n** – The order for the moment


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.


    * **center** – Take moments with respect to the band center



* **Returns**

    Orbital-projected nth moment in eV



#### get_normalized()
Returns a normalized version of the CompleteDos.


#### get_site_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite))
Get the total Dos for a site (all orbitals).


* **Parameters**

    **site** – Site in Structure associated with CompleteDos.



* **Returns**

    Dos containing summed orbital densities for site.



#### get_site_orbital_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite), orbital: Orbital)
Get the Dos for a particular orbital of a particular site.


* **Parameters**


    * **site** – Site in Structure associated with CompleteDos.


    * **orbital** – Orbital in the site.



* **Returns**

    Dos containing densities for orbital of site.



#### get_site_spd_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite))
Get orbital projected Dos of a particular site.


* **Parameters**

    **site** – Site in Structure associated with CompleteDos.



* **Returns**

    Dos}, e.g. {OrbitalType.s: Dos object, …}



* **Return type**

    dict of {OrbitalType



#### get_site_t2g_eg_resolved_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite))
Get the t2g, eg projected DOS for a particular site.


* **Parameters**

    **site** – Site in Structure associated with CompleteDos.



* **Returns**

    A dict {“e_g”: Dos, “t2g”: Dos} containing summed e_g and t2g DOS for the site.



* **Return type**

    dict[str, Dos]



#### get_spd_dos()
Get orbital projected Dos.


* **Returns**

    Dos}, e.g. {OrbitalType.s: Dos object, …}



* **Return type**

    dict of {OrbitalType



#### get_upper_band_edge(band: OrbitalType = OrbitalType.d, elements: list[SpeciesLike] | None = None, sites: list[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)] | None = None, spin: Spin | None = None, erange: list[float] | None = None)
Get the orbital-projected upper band edge. The definition by Xin et al.
Phys. Rev. B, 89, 115114 (2014) is used, which is the highest peak position of the
Hilbert transform of the orbital-projected DOS.


* **Parameters**


    * **band** – Orbital type to get the band center of (default is d-band)


    * **elements** – Elements to get the band center of (cannot be used in conjunction with site)


    * **sites** – Sites to get the band center of (cannot be used in conjunction with el)


    * **spin** – Spin channel to use. By default, the spin channels will be combined.


    * **erange** – [min, max] energy range to consider, with respect to the Fermi level.
    Default is None, which means all energies are considered.



* **Returns**

    Upper band edge in eV, often denoted epsilon_u



#### _property_ spin_polarization(_: float | Non_ )
Calculates spin polarization at Fermi level. If the
calculation is not spin-polarized, None will be
returned.

See Sanvito et al., doi: 10.1126/sciadv.1602241 for
an example usage.


* **Return (float)**

    spin polarization in range [0, 1],


will also return NaN if spin polarization ill-defined
(e.g. for insulator)


### _class_ pymatgen.electronic_structure.dos.DOS(energies: ArrayLike, densities: ArrayLike, efermi: float)
Bases: [`Spectrum`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum)

Replacement basic DOS object. All other DOS objects are extended versions
of this object. Work in progress.

<!-- attribute: energies

The sequence of energies -->
<!-- attribute: densities

A dict of spin densities, e.g., {Spin.up: [...], Spin.down: [...]} -->
<!-- attribute: efermi

Fermi level -->

* **Parameters**


    * **energies** – A sequence of energies


    * **densities** (*ndarray*) – Either a Nx1 or a Nx2 array. If former, it is
    interpreted as a Spin.up only density. Otherwise, the first column
    is interpreted as Spin.up and the other is Spin.down.


    * **efermi** – Fermi level energy.



#### XLABEL(_ = 'Energy_ )

#### YLABEL(_ = 'Density_ )

#### get_cbm_vbm(tol: float = 0.001, abs_tol: bool = False, spin=None)
Expects a DOS object and finds the cbm and vbm.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – An absolute tolerance (True) and a relative one (False)


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    float in eV corresponding to the gap



* **Return type**

    (cbm, vbm)



#### get_gap(tol: float = 0.001, abs_tol: bool = False, spin: Spin | None = None)
Expects a DOS object and finds the gap.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – An absolute tolerance (True) and a relative one (False)


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    gap in eV



#### get_interpolated_gap(tol: float = 0.001, abs_tol: bool = False, spin: Spin | None = None)
Expects a DOS object and finds the gap.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – Set to True for an absolute tolerance and False for a
    relative one.


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    Tuple of floats in eV corresponding to the gap, cbm and vbm.



* **Return type**

    (gap, cbm, vbm)



### _class_ pymatgen.electronic_structure.dos.Dos(efermi: float, energies: ArrayLike, densities: Mapping[Spin, ArrayLike], norm_vol: float | None = None)
Bases: `MSONable`

Basic DOS object. All other DOS objects are extended versions of this
object.

<!-- attribute: energies

The sequence of energies -->
<!-- attribute: densities

A dict of spin densities, e.g., {Spin.up: [...], Spin.down: [...]} -->
<!-- attribute: efermi

Fermi level -->

* **Parameters**


    * **efermi** – Fermi level energy


    * **energies** – A sequences of energies


    * **(****dict****[****Spin** (*densities*) – np.array]): representing the density of states for each Spin.


    * **norm_vol** – The volume used to normalize the densities. Defaults to 1 if None which will not perform any
    normalization. If not None, the resulting density will have units of states/eV/Angstrom^3, otherwise
    the density will be in states/eV.



#### as_dict()
JSON-serializable dict representation of Dos.


#### _classmethod_ from_dict(d)
Returns Dos object from dict representation of Dos.


#### get_cbm_vbm(tol: float = 0.001, abs_tol: bool = False, spin: Spin | None = None)
Expects a DOS object and finds the cbm and vbm.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – An absolute tolerance (True) and a relative one (False)


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    float in eV corresponding to the gap



* **Return type**

    (cbm, vbm)



#### get_densities(spin: Spin | None = None)
Returns the density of states for a particular spin.


* **Parameters**

    **spin** – Spin



* **Returns**

    Returns the density of states for a particular spin. If Spin is
    None, the sum of all spins is returned.



#### get_gap(tol: float = 0.001, abs_tol: bool = False, spin: Spin | None = None)
Expects a DOS object and finds the gap.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – An absolute tolerance (True) and a relative one (False)


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    gap in eV



#### get_interpolated_gap(tol: float = 0.001, abs_tol: bool = False, spin: Spin | None = None)
Expects a DOS object and finds the gap.


* **Parameters**


    * **tol** – tolerance in occupations for determining the gap


    * **abs_tol** – Set to True for an absolute tolerance and False for a
    relative one.


    * **spin** – Possible values are None - finds the gap in the summed
    densities, Up - finds the gap in the up spin channel,
    Down - finds the gap in the down spin channel.



* **Returns**

    Tuple of floats in eV corresponding to the gap, cbm and vbm.



* **Return type**

    (gap, cbm, vbm)



#### get_interpolated_value(energy: float)
Returns interpolated density for a particular energy.


* **Parameters**

    **energy** – Energy to return the density for.



#### get_smeared_densities(sigma: float)
Returns the Dict representation of the densities, {Spin: densities},
but with a Gaussian smearing of std dev sigma.


* **Parameters**

    **sigma** – Std dev of Gaussian smearing function.



* **Returns**

    Dict of Gaussian-smeared densities.



### _class_ pymatgen.electronic_structure.dos.FermiDos(dos: Dos, structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure) | None = None, nelecs: float | None = None, bandgap: float | None = None)
Bases: `Dos`, `MSONable`

This wrapper class helps relate the density of states, doping levels
(i.e. carrier concentrations) and corresponding fermi levels. A negative
doping concentration indicates the majority carriers are electrons
(n-type doping); a positive doping concentration indicates holes are the
majority carriers (p-type doping).


* **Parameters**


    * **dos** – Pymatgen Dos object.


    * **structure** – A structure. If not provided, the structure
    of the dos object will be used. If the dos does not have an
    associated structure object, an error will be thrown.


    * **nelecs** – The number of electrons included in the energy range of
    dos. It is used for normalizing the densities. Default is the total
    number of electrons in the structure.


    * **bandgap** – If set, the energy values are scissored so that the electronic
    band gap matches this value.



#### as_dict()
JSON-serializable dict representation of Dos.


#### _classmethod_ from_dict(d)
Returns Dos object from dict representation of Dos.


#### get_doping(fermi_level: float, temperature: float)
Calculate the doping (majority carrier concentration) at a given
Fermi level  and temperature. A simple Left Riemann sum is used for
integrating the density of states over energy & equilibrium Fermi-Dirac
distribution.


* **Parameters**


    * **fermi_level** – The fermi_level level in eV.


    * **temperature** – The temperature in Kelvin.



* **Returns**

    The doping concentration in units of 1/cm^3. Negative values
    indicate that the majority carriers are electrons (n-type doping)
    whereas positive values indicates the majority carriers are holes
    (p-type doping).



#### get_fermi(concentration: float, temperature: float, rtol: float = 0.01, nstep: int = 50, step: float = 0.1, precision: int = 8)
Finds the Fermi level at which the doping concentration at the given
temperature (T) is equal to concentration. A greedy algorithm is used
where the relative error is minimized by calculating the doping at a
grid which continually becomes finer.


* **Parameters**


    * **concentration** – The doping concentration in 1/cm^3. Negative values
    represent n-type doping and positive values represent p-type
    doping.


    * **temperature** – The temperature in Kelvin.


    * **rtol** – The maximum acceptable relative error.


    * **nstep** – The number of steps checked around a given Fermi level.


    * **step** – Initial step in energy when searching for the Fermi level.


    * **precision** – Essentially the decimal places of calculated Fermi level.



* **Raises**

    **ValueError** – If the Fermi level cannot be found.



* **Returns**

    The Fermi level in eV. Note that this is different from the default
    dos.efermi.



#### get_fermi_interextrapolated(concentration: float, temperature: float, warn: bool = True, c_ref: float = 10000000000.0, \*\*kwargs)
Similar to get_fermi except that when get_fermi fails to converge,
an interpolated or extrapolated fermi is returned with the assumption
that the Fermi level changes linearly with log(abs(concentration)).


* **Parameters**


    * **concentration** – The doping concentration in 1/cm^3. Negative values
    represent n-type doping and positive values represent p-type
    doping.


    * **temperature** – The temperature in Kelvin.


    * **warn** – Whether to give a warning the first time the fermi cannot be
    found.


    * **c_ref** – A doping concentration where get_fermi returns a
    value without error for both c_ref and -c_ref.


    * **\*\*kwargs** – Keyword arguments passed to the get_fermi function.



* **Returns**

    The Fermi level. Note, the value is possibly interpolated or
    extrapolated and must be used with caution.



### _class_ pymatgen.electronic_structure.dos.LobsterCompleteDos(structure: [Structure](pymatgen.core.md#pymatgen.core.structure.Structure), total_dos: Dos, pdoss: Mapping[[PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite), Mapping[Orbital, Mapping[Spin, ArrayLike]]], normalize: bool = False)
Bases: `CompleteDos`

Extended CompleteDOS for Lobster.


* **Parameters**


    * **structure** – Structure associated with this particular DOS.


    * **total_dos** – total Dos for structure


    * **pdoss** – The pdoss are supplied as an {Site: {Orbital: {Spin:Densities}}}


    * **normalize** – Whether to normalize the densities by the volume of the structure.
    If True, the units of the densities are states/eV/Angstrom^3. Otherwise,
    the units are states/eV.



#### _classmethod_ from_dict(d)
Hydrate CompleteDos object from dict representation.


#### get_element_spd_dos(el: SpeciesLike)
Get element and spd projected Dos.


* **Parameters**

    **el** – Element in Structure.composition associated with LobsterCompleteDos



* **Returns**

    densities, OrbitalType.p: densities, OrbitalType.d: densities}



* **Return type**

    dict of {OrbitalType.s



#### get_site_orbital_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite), orbital: str)
Get the Dos for a particular orbital of a particular site.


* **Parameters**


    * **site** – Site in Structure associated with CompleteDos.


    * **orbital** – principal quantum number and orbital in string format, e.g. “4s”.
    possible orbitals are: “s”, “p_y”, “p_z”, “p_x”, “d_xy”, “d_yz”, “d_z^2”,
    “d_xz”, “d_x^2-y^2”, “f_y(3x^2-y^2)”, “f_xyz”,
    “f_yz^2”, “f_z^3”, “f_xz^2”, “f_z(x^2-y^2)”, “f_x(x^2-3y^2)”
    In contrast to the Cohpcar and the Cohplist objects, the strings from the Lobster files are used



* **Returns**

    Dos containing densities of an orbital of a specific site.



#### get_site_t2g_eg_resolved_dos(site: [PeriodicSite](pymatgen.core.md#pymatgen.core.sites.PeriodicSite))
Get the t2g, eg projected DOS for a particular site.


* **Parameters**

    **site** – Site in Structure associated with CompleteDos.



* **Returns**

    Dos, “t2g”: Dos} containing summed e_g and t2g DOS
    for the site.



* **Return type**

    A dict {“e_g”



#### get_spd_dos()
Get orbital projected Dos.
For example, if 3s and 4s are included in the basis of some element, they will be both summed in the orbital
projected DOS.


* **Returns**

    Dos}, e.g. {“s”: Dos object, …}



* **Return type**

    dict of {orbital



### pymatgen.electronic_structure.dos.add_densities(density1: Mapping[Spin, ArrayLike], density2: Mapping[Spin, ArrayLike])
Sum two densities.


* **Parameters**


    * **density1** – First density.


    * **density2** – Second density.



* **Returns**

    dict[Spin, np.ndarray]



### pymatgen.electronic_structure.dos.f0(E, fermi, T)
Return the equilibrium fermi-dirac.


* **Parameters**


    * **E** (*float*) – energy in eV


    * **fermi** (*float*) – the Fermi level in eV


    * **T** (*float*) – the temperature in kelvin



* **Returns**

    float


## pymatgen.electronic_structure.plotter module

This module implements plotter for DOS and band structure.


### _class_ pymatgen.electronic_structure.plotter.BSDOSPlotter(bs_projection: Literal['elements'] | None = 'elements', dos_projection: str = 'elements', vb_energy_range: float = 4, cb_energy_range: float = 4, fixed_cb_energy: bool = False, egrid_interval: float = 1, font: str = 'Times New Roman', axis_fontsize: float = 20, tick_fontsize: float = 15, legend_fontsize: float = 14, bs_legend: str = 'best', dos_legend: str = 'best', rgb_legend: bool = True, fig_size: tuple[float, float] = (11, 8.5))
Bases: `object`

A joint, aligned band structure and density of states plot. Contributions
from Jan Pohls as well as the online example from Germain Salvato-Vallverdu:
[http://gvallver.perso.univ-pau.fr/?p=587](http://gvallver.perso.univ-pau.fr/?p=587).

Instantiate plotter settings.


* **Parameters**


    * **bs_projection** (*'elements'** | **None*) – Whether to project the bands onto elements.


    * **dos_projection** (*str*) – “elements”, “orbitals”, or None


    * **vb_energy_range** (*float*) – energy in eV to show of valence bands


    * **cb_energy_range** (*float*) – energy in eV to show of conduction bands


    * **fixed_cb_energy** (*bool*) – If true, the cb_energy_range will be interpreted
    as constant (i.e., no gap correction for cb energy)


    * **egrid_interval** (*float*) – interval for grid marks


    * **font** (*str*) – font family


    * **axis_fontsize** (*float*) – font size for axis


    * **tick_fontsize** (*float*) – font size for axis tick labels


    * **legend_fontsize** (*float*) – font size for legends


    * **bs_legend** (*str*) – matplotlib string location for legend or None


    * **dos_legend** (*str*) – matplotlib string location for legend or None


    * **rgb_legend** (*bool*) – (T/F) whether to draw RGB triangle/bar for element proj.


    * **fig_size** (*tuple*) – dimensions of figure size (width, height)



#### get_plot(bs: BandStructureSymmLine, dos: Dos | CompleteDos | None = None)
Get a matplotlib plot object.


* **Parameters**


    * **bs** (*BandStructureSymmLine*) – the bandstructure to plot. Projection
    data must exist for projected plots.


    * **dos** (*Dos*) – the Dos to plot. Projection data must exist (i.e.,
    CompleteDos) for projected plots.



* **Returns**

    matplotlib.pyplot object on which you can call commands like show()
    and savefig()



### _class_ pymatgen.electronic_structure.plotter.BSPlotter(bs: BandStructureSymmLine)
Bases: `object`

Class to plot or get data to facilitate the plot of band structure objects.


* **Parameters**

    **bs** – A BandStructureSymmLine object.



#### add_bs(bs: BandStructureSymmLine | list[BandStructureSymmLine])
Method to add bands objects to the BSPlotter.


#### bs_plot_data(zero_to_efermi=True, bs=None, bs_ref=None, split_branches=True)
Get the data nicely formatted for a plot.


* **Parameters**


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **bs** – the bandstructure to get the data from. If not provided, the first
    one in the self._bs list will be used.


    * **bs_ref** – is the bandstructure of reference when a rescale of the distances
    is need to plot multiple bands


    * **split_branches** – if True distances and energies are split according to the
    branches. If False distances and energies are split only where branches
    are discontinuous (reducing the number of lines to plot).



* **Returns**

    A dictionary of the following format:
    ticks: A dict with the ‘distances’ at which there is a kpoint (the
    x axis) and the labels (None if no label).
    energy: A dict storing bands for spin up and spin down data
    {Spin:[np.array(nb_bands,kpoints),…]} as a list of discontinuous kpath
    of energies. The energy of multiple continuous branches are stored together.
    vbm: A list of tuples (distance,energy) marking the vbms. The
    energies are shifted with respect to the Fermi level is the
    option has been selected.
    cbm: A list of tuples (distance,energy) marking the cbms. The
    energies are shifted with respect to the Fermi level is the
    option has been selected.
    lattice: The reciprocal lattice.
    zero_energy: This is the energy used as zero for the plot.
    band_gap:A string indicating the band gap and its nature (empty if
    it’s a metal).
    is_metal: True if the band structure is metallic (i.e., there is at
    least one band crossing the Fermi level).



* **Return type**

    dict



#### get_plot(zero_to_efermi=True, ylim=None, smooth=False, vbm_cbm_marker=False, smooth_tol=0, smooth_k=3, smooth_np=100, bs_labels=None)
Get a matplotlib object for the bandstructures plot.
Multiple bandstructure objs are plotted together if they have the
same high symm path.


* **Parameters**


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **ylim** – Specify the y-axis (energy) limits; by default None let
    the code choose. It is vbm-4 and cbm+4 if insulator
    efermi-10 and efermi+10 if metal


    * **smooth** (*bool** or **list**(**bools**)*) – interpolates the bands by a spline cubic.
    A single bool values means to interpolate all the bandstructure objs.
    A list of bools allows to select the bandstructure obs to interpolate.


    * **vbm_cbm_marker** (*bool*) – if True, a marker is added to the vbm and cbm.


    * **smooth_tol** (*float*) – tolerance for fitting spline to band data.
    Default is None such that no tolerance will be used.


    * **smooth_k** (*int*) – degree of splines 1<k<5


    * **smooth_np** (*int*) – number of interpolated points per each branch.


    * **bs_labels** – labels for each band for the plot legend.



#### get_ticks()
Get all ticks and labels for a band structure plot.


* **Returns**

    A dictionary with ‘distance’: a list of distance at which
    ticks should be set and ‘label’: a list of label for each of those
    ticks.



* **Return type**

    dict



#### get_ticks_old()
Get all ticks and labels for a band structure plot.


* **Returns**

    A dictionary with ‘distance’: a list of distance at which
    ticks should be set and ‘label’: a list of label for each of those
    ticks.



* **Return type**

    dict



#### plot_brillouin()
Plot the Brillouin zone.


#### plot_compare(other_plotter, legend=True)
Plot two band structure for comparison. One is in red the other in blue
(no difference in spins). The two band structures need to be defined
on the same symmetry lines! and the distance between symmetry lines is
the one of the band structure used to build the BSPlotter.


* **Parameters**


    * **other_plotter** – Another band structure object defined along the same symmetry lines


    * **legend** – True to add a legend to the plot



* **Returns**

    a matplotlib object with both band structures



#### save_plot(filename, img_format='eps', ylim=None, zero_to_efermi=True, smooth=False)
Save matplotlib plot to a file.


* **Parameters**


    * **filename** – Filename to write to.


    * **img_format** – Image format to use. Defaults to EPS.


    * **ylim** – Specifies the y-axis limits.


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **smooth** – Cubic spline interpolation of the bands.



#### show(zero_to_efermi=True, ylim=None, smooth=False, smooth_tol=None)
Show the plot using matplotlib.


* **Parameters**


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **ylim** – Specify the y-axis (energy) limits; by default None let
    the code choose. It is vbm-4 and cbm+4 if insulator
    efermi-10 and efermi+10 if metal


    * **smooth** – interpolates the bands by a spline cubic


    * **smooth_tol** (*float*) – tolerance for fitting spline to band data.
    Default is None such that no tolerance will be used.



### _class_ pymatgen.electronic_structure.plotter.BSPlotterProjected(bs)
Bases: `BSPlotter`

Class to plot or get data to facilitate the plot of band structure objects
projected along orbitals, elements or sites.


* **Parameters**

    **bs** – A BandStructureSymmLine object with projections.



#### get_elt_projected_plots(zero_to_efermi=True, ylim=None, vbm_cbm_marker=False)
Method returning a plot composed of subplots along different elements.


* **Returns**

    a pyplot object with different subfigures for each projection
    The blue and red colors are for spin up and spin down
    The bigger the red or blue dot in the band structure the higher
    character for the corresponding element and orbital



#### get_elt_projected_plots_color(zero_to_efermi=True, elt_ordered=None)
Returns a pyplot plot object with one plot where the band structure
line color depends on the character of the band (along different
elements). Each element is associated with red, green or blue
and the corresponding rgb color depending on the character of the band
is used. The method can only deal with binary and ternary compounds.

spin up and spin down are differientiated by a ‘-’ and a ‘–’ line


* **Parameters**


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **elt_ordered** – A list of Element ordered. The first one is red,
    second green, last blue



* **Returns**

    a pyplot object



#### get_projected_plots_dots(dictio, zero_to_efermi=True, ylim=None, vbm_cbm_marker=False)
Method returning a plot composed of subplots along different elements
and orbitals.


* **Parameters**


    * **dictio** – The element and orbitals you want a projection on. The
    format is {Element:[Orbitals]} for instance
    {‘Cu’:[‘d’,’s’],’O’:[‘p’]} will give projections for Cu on
    d and s orbitals and on oxygen p.
    If you use this class to plot LobsterBandStructureSymmLine,
    the orbitals are named as in the FATBAND filename, e.g.
    “2p” or “2p_x”


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **ylim** – Specify the y-axis limits. Defaults to None.


    * **vbm_cbm_marker** – Add markers for the VBM and CBM. Defaults to False.



* **Returns**

    a pyplot object with different subfigures for each projection
    The blue and red colors are for spin up and spin down.
    The bigger the red or blue dot in the band structure the higher
    character for the corresponding element and orbital.



#### get_projected_plots_dots_patom_pmorb(dictio, dictpa, sum_atoms=None, sum_morbs=None, zero_to_efermi=True, ylim=None, vbm_cbm_marker=False, selected_branches=None, w_h_size=(12, 8), num_column=None)
Method returns a plot composed of subplots for different atoms and
orbitals (subshell orbitals such as ‘s’, ‘p’, ‘d’ and ‘f’ defined by
azimuthal quantum numbers l = 0, 1, 2 and 3, respectively or
individual orbitals like ‘px’, ‘py’ and ‘pz’ defined by magnetic
quantum numbers m = -1, 1 and 0, respectively).
This is an extension of “get_projected_plots_dots” method.


* **Parameters**


    * **dictio** – The elements and the orbitals you need to project on. The
    format is {Element:[Orbitals]}, for instance:
    {‘Cu’:[‘dxy’,’s’,’px’],’O’:[‘px’,’py’,’pz’]} will give projections for Cu on
    orbitals dxy, s, px and for O on orbitals px, py, pz. If you want to sum over all
    individual orbitals of subshell orbitals, for example, ‘px’, ‘py’ and ‘pz’ of O,
    just simply set {‘Cu’:[‘dxy’,’s’,’px’],’O’:[‘p’]} and set sum_morbs (see
    explanations below) as {‘O’:[p],…}. Otherwise, you will get an error.


    * **dictpa** – The elements and their sites (defined by site numbers) you
    need to project on. The format is {Element: [Site numbers]}, for instance:
    {‘Cu’:[1,5],’O’:[3,4]} will give projections for Cu on site-1 and on site-5, O on
    site-3 and on site-4 in the cell. The correct site numbers of atoms are consistent
    with themselves in the structure computed. Normally, the structure should be totally
    similar with POSCAR file, however, sometimes VASP can rotate or translate the cell.
    Thus, it would be safe if using Vasprun class to get the final_structure and as a
    result, correct index numbers of atoms.


    * **sum_atoms** – Sum projection of the similar atoms together (e.g.: Cu
    on site-1 and Cu on site-5). The format is {Element: [Site numbers]}, for instance:

    > {‘Cu’: [1,5], ‘O’: [3,4]} means summing projections over Cu on site-1 and Cu on
    > site-5 and O on site-3 and on site-4. If you do not want to use this functional,
    > just turn it off by setting sum_atoms = None.



    * **sum_morbs** – Sum projections of individual orbitals of similar atoms
    together (e.g.: ‘dxy’ and ‘dxz’). The format is {Element: [individual orbitals]},
    for instance: {‘Cu’: [‘dxy’, ‘dxz’], ‘O’: [‘px’, ‘py’]} means summing projections
    over ‘dxy’ and ‘dxz’ of Cu and ‘px’ and ‘py’ of O. If you do not want to use this
    functional, just turn it off by setting sum_morbs = None.


    * **zero_to_efermi** – Automatically set the Fermi level as the plot’s origin (i.e. subtract E - E_f).
    Defaults to True.


    * **ylim** – The y-axis limit. Defaults to None.


    * **vbm_cbm_marker** – Whether to plot points to indicate valence band maxima and conduction
    band minima positions. Defaults to False.


    * **selected_branches** – The index of symmetry lines you chose for
    plotting. This can be useful when the number of symmetry lines (in KPOINTS file) are
    manny while you only want to show for certain ones. The format is [index of line],
    for instance: [1, 3, 4] means you just need to do projection along lines number 1, 3
    and 4 while neglecting lines number 2 and so on. By default, this is None type and
    all symmetry lines will be plotted.


    * **w_h_size** – This variable help you to control the width and height
    of figure. By default, width = 12 and height = 8 (inches). The width/height ratio is
    kept the same for subfigures and the size of each depends on how many number of
    subfigures are plotted.


    * **num_column** – This variable help you to manage how the subfigures are
    arranged in the figure by setting up the number of columns of subfigures. The value
    should be an int number. For example, num_column = 3 means you want to plot
    subfigures in 3 columns. By default, num_column = None and subfigures are aligned in
    2 columns.



* **Returns**

    A pyplot object with different subfigures for different projections.
    The blue and red colors lines are bands
    for spin up and spin down. The green and cyan dots are projections
    for spin up and spin down. The bigger
    the green or cyan dots in the projected band structures, the higher
    character for the corresponding elements
    and orbitals. List of individual orbitals and their numbers (set up
    by VASP and no special meaning):
    s = 0; py = 1 pz = 2 px = 3; dxy = 4 dyz = 5 dz2 = 6 dxz = 7 dx2 = 8;
    f_3 = 9 f_2 = 10 f_1 = 11 f0 = 12 f1 = 13 f2 = 14 f3 = 15



### _class_ pymatgen.electronic_structure.plotter.BoltztrapPlotter(bz)
Bases: `object`

class containing methods to plot the data from Boltztrap.


* **Parameters**

    **bz** – a BoltztrapAnalyzer object.



#### plot_carriers(temp=300)
Plot the carrier concentration in function of Fermi level.


* **Parameters**

    **temp** – the temperature



* **Returns**

    a matplotlib object



#### plot_complexity_factor_mu(temps=(300,), output='average', Lambda=0.5)
Plot respect to the chemical potential of the Fermi surface complexity
factor calculated as explained in Ref.
Gibbs, Z. M. et al., Effective mass and fermi surface complexity factor
from ab initio band structure calculations.
npj Computational Materials 3, 8 (2017).


* **Parameters**


    * **output** – ‘average’ returns the complexity factor calculated using the average
    of the three diagonal components of the seebeck and conductivity tensors.
    ‘tensor’ returns the complexity factor respect to the three
    diagonal components of seebeck and conductivity tensors.


    * **temps** – list of temperatures of calculated seebeck and conductivity.


    * **Lambda** – fitting parameter used to model the scattering (0.5 means constant
    relaxation time).



* **Returns**

    a matplotlib object



#### plot_conductivity_dop(temps='all', output='average', relaxation_time=1e-14)
Plot the conductivity in function of doping levels for different
temperatures.


* **Parameters**


    * **temps** – the default ‘all’ plots all the temperatures in the analyzer.
    Specify a list of temperatures if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_conductivity_mu(temp: float = 600, output: str = 'eig', relaxation_time: float = 1e-14, xlim: Sequence[float] | None = None)
Plot the conductivity in function of Fermi level. Semi-log plot.


* **Parameters**


    * **temp** (*float*) – the temperature


    * **output** (*str*) – “eig” or “average”


    * **relaxation_time** (*float*) – A relaxation time in s. Defaults to 1e-14 and the plot is in
    units of relaxation time


    * **xlim** (*tuple**[**float**, **float**]*) – a 2-tuple of min and max fermi energy. Defaults to (0, band gap)



* **Returns**

    a matplotlib object



#### plot_conductivity_temp(doping='all', output='average', relaxation_time=1e-14)
Plot the conductivity in function of temperature for different doping levels.


* **Parameters**


    * **doping** (*str*) – the default ‘all’ plots all the doping levels in the analyzer.
    Specify a list of doping levels if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_dos(sigma=0.05)
Plot dos.


* **Parameters**

    **sigma** – a smearing



* **Returns**

    a matplotlib object



#### plot_eff_mass_dop(temps='all', output='average')
Plot the average effective mass in function of doping levels
for different temperatures.


* **Parameters**


    * **temps** – the default ‘all’ plots all the temperatures in the analyzer.
    Specify a list of temperatures if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_eff_mass_temp(doping='all', output='average')
Plot the average effective mass in function of temperature
for different doping levels.


* **Parameters**


    * **doping** (*str*) – the default ‘all’ plots all the doping levels in the analyzer.
    Specify a list of doping levels if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.



* **Returns**

    a matplotlib object



#### plot_hall_carriers(temp=300)
Plot the Hall carrier concentration in function of Fermi level.


* **Parameters**

    **temp** – the temperature



* **Returns**

    a matplotlib object



#### plot_power_factor_dop(temps='all', output='average', relaxation_time=1e-14)
Plot the Power Factor in function of doping levels for different temperatures.


* **Parameters**


    * **temps** – the default ‘all’ plots all the temperatures in the analyzer.
    Specify a list of temperatures if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_power_factor_mu(temp: float = 600, output: str = 'eig', relaxation_time: float = 1e-14, xlim: Sequence[float] | None = None)
Plot the power factor in function of Fermi level. Semi-log plot.


* **Parameters**


    * **temp** (*float*) – the temperature


    * **output** (*str*) – “eig” or “average”


    * **relaxation_time** (*float*) – A relaxation time in s. Defaults to 1e-14 and the plot is in
    units of relaxation time


    * **xlim** (*tuple**[**float**, **float**]*) – a 2-tuple of min and max fermi energy. Defaults to (0, band gap)



* **Returns**

    a matplotlib object



#### plot_power_factor_temp(doping='all', output='average', relaxation_time=1e-14)
Plot the Power Factor in function of temperature for different doping levels.


* **Parameters**


    * **doping** (*str*) – the default ‘all’ plots all the doping levels in the analyzer.
    Specify a list of doping levels if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_seebeck_dop(temps='all', output='average')
Plot the Seebeck in function of doping levels for different temperatures.


* **Parameters**


    * **temps** – the default ‘all’ plots all the temperatures in the analyzer.
    Specify a list of temperatures if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.



* **Returns**

    a matplotlib object



#### plot_seebeck_eff_mass_mu(temps=(300,), output='average', Lambda=0.5)
Plot respect to the chemical potential of the Seebeck effective mass
calculated as explained in Ref.
Gibbs, Z. M. et al., Effective mass and fermi surface complexity factor
from ab initio band structure calculations.
npj Computational Materials 3, 8 (2017).


* **Parameters**


    * **output** – ‘average’ returns the seebeck effective mass calculated
    using the average of the three diagonal components of the
    seebeck tensor. ‘tensor’ returns the seebeck effective mass
    respect to the three diagonal components of the seebeck tensor.


    * **temps** – list of temperatures of calculated seebeck.


    * **Lambda** – fitting parameter used to model the scattering (0.5 means
    constant relaxation time).



* **Returns**

    a matplotlib object



#### plot_seebeck_mu(temp: float = 600, output: str = 'eig', xlim: Sequence[float] | None = None)
Plot the seebeck coefficient in function of Fermi level.


* **Parameters**


    * **temp** (*float*) – the temperature


    * **output** (*str*) – “eig” or “average”


    * **xlim** (*tuple**[**float**, **float**]*) – a 2-tuple of min and max fermi energy. Defaults to (0, band gap)



* **Returns**

    a matplotlib object



#### plot_seebeck_temp(doping='all', output='average')
Plot the Seebeck coefficient in function of temperature for different
doping levels.


* **Parameters**


    * **doping** (*str*) – the default ‘all’ plots all the doping levels in the analyzer.
    Specify a list of doping levels if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.



* **Returns**

    a matplotlib object



#### plot_zt_dop(temps='all', output='average', relaxation_time=1e-14)
Plot the figure of merit zT in function of doping levels for different
temperatures.


* **Parameters**


    * **temps** – the default ‘all’ plots all the temperatures in the analyzer.
    Specify a list of temperatures if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Returns**

    a matplotlib object



#### plot_zt_mu(temp: float = 600, output: str = 'eig', relaxation_time: float = 1e-14, xlim: Sequence[float] | None = None)
Plot the ZT in function of Fermi level.


* **Parameters**


    * **temp** (*float*) – the temperature


    * **output** (*str*) – “eig” or “average”


    * **relaxation_time** (*float*) – A relaxation time in s. Defaults to 1e-14 and the plot is in
    units of relaxation time


    * **xlim** (*tuple**[**float**, **float**]*) – a 2-tuple of min and max fermi energy. Defaults to (0, band gap)



* **Returns**

    matplotlib.pyplot module



#### plot_zt_temp(doping='all', output: Literal['average', 'eigs'] = 'average', relaxation_time=1e-14)
Plot the figure of merit zT in function of temperature for different doping levels.


* **Parameters**


    * **doping** (*str*) – the default ‘all’ plots all the doping levels in the analyzer.
    Specify a list of doping levels if you want to plot only some.


    * **output** – with ‘average’ you get an average of the three directions
    with ‘eigs’ you get all the three directions.


    * **relaxation_time** – specify a constant relaxation time value



* **Raises**

    **ValueError** – if output is not ‘average’ or ‘eigs’



* **Returns**

    a matplotlib object



### _class_ pymatgen.electronic_structure.plotter.CohpPlotter(zero_at_efermi=True, are_coops=False, are_cobis=False)
Bases: `object`

Class for plotting crystal orbital Hamilton populations (COHPs) or
crystal orbital overlap populations (COOPs). It is modeled after the
DosPlotter object.


* **Parameters**


    * **zero_at_efermi** – Whether to shift all populations to have zero
    energy at the Fermi level. Defaults to True.


    * **are_coops** – Switch to indicate that these are COOPs, not COHPs.
    Defaults to False for COHPs.


    * **are_cobis** – Switch to indicate that these are COBIs, not COHPs/COOPs.
    Defaults to False for COHPs.



#### add_cohp(label, cohp)
Adds a COHP for plotting.


* **Parameters**


    * **label** – Label for the COHP. Must be unique.


    * **cohp** – COHP object.



#### add_cohp_dict(cohp_dict, key_sort_func=None)
Adds a dictionary of COHPs with an optional sorting function
for the keys.


* **Parameters**


    * **cohp_dict** – dict of the form {label: Cohp}


    * **key_sort_func** – function used to sort the cohp_dict keys.



#### get_cohp_dict()
Returns the added COHPs as a json-serializable dict. Note that if you
have specified smearing for the COHP plot, the populations returned
will be the smeared and not the original populations.


* **Returns**

    Dict of COHP data of the form {label: {“efermi”: efermi,
    “energies”: …, “COHP”: {Spin.up: …}, “ICOHP”: …}}.



* **Return type**

    dict



#### get_plot(xlim=None, ylim=None, plot_negative=None, integrated=False, invert_axes=True)
Get a matplotlib plot showing the COHP.


* **Parameters**


    * **xlim** – Specifies the x-axis limits. Defaults to None for
    automatic determination.


    * **ylim** – Specifies the y-axis limits. Defaults to None for
    automatic determination.


    * **plot_negative** – It is common to plot -COHP(E) so that the
    sign means the same for COOPs and COHPs. Defaults to None
    for automatic determination: If are_coops is True, this
    will be set to False, else it will be set to True.


    * **integrated** – Switch to plot ICOHPs. Defaults to False.


    * **invert_axes** – Put the energies onto the y-axis, which is
    common in chemistry.



* **Returns**

    A matplotlib object.



#### save_plot(filename, img_format='eps', xlim=None, ylim=None)
Save matplotlib plot to a file.


* **Parameters**


    * **filename** – File name to write to.


    * **img_format** – Image format to use. Defaults to EPS.


    * **xlim** – Specifies the x-axis limits. Defaults to None for
    automatic determination.


    * **ylim** – Specifies the y-axis limits. Defaults to None for
    automatic determination.



#### show(xlim=None, ylim=None)
Show the plot using matplotlib.


* **Parameters**


    * **xlim** – Specifies the x-axis limits. Defaults to None for
    automatic determination.


    * **ylim** – Specifies the y-axis limits. Defaults to None for
    automatic determination.



### _class_ pymatgen.electronic_structure.plotter.DosPlotter(zero_at_efermi: bool = True, stack: bool = False, sigma: float | None = None)
Bases: `object`

Class for plotting phonon DOSs. The interface is extremely flexible given there are many
different ways in which people want to view DOS.
Typical usage is:

> # Initializes plotter with some optional args. Defaults are usually fine
> plotter = PhononDosPlotter().

> # Add DOS with a label
> plotter.add_dos(“Total DOS”, dos)

> # Alternatively, you can add a dict of DOSes. This is the typical form
> # returned by CompletePhononDos.get_element_dos().
> plotter.add_dos_dict({“dos1”: dos1, “dos2”: dos2})
> plotter.add_dos_dict(complete_dos.get_spd_dos())


* **Parameters**


    * **zero_at_efermi** (*bool*) – Whether to shift all Dos to have zero energy at the
    fermi energy. Defaults to True.


    * **stack** (*bool*) – Whether to plot the DOS as a stacked area graph


    * **sigma** (*float*) – Specify a standard deviation for Gaussian smearing
    the DOS for nicer looking plots. Defaults to None for no
    smearing.



#### add_dos(label: str, dos: Dos)
Adds a dos for plotting.


* **Parameters**


    * **label** – label for the DOS. Must be unique.


    * **dos** – Dos object



#### add_dos_dict(dos_dict, key_sort_func=None)
Add a dictionary of doses, with an optional sorting function for the
keys.


* **Parameters**


    * **dos_dict** – dict of {label: Dos}


    * **key_sort_func** – function used to sort the dos_dict keys.



#### get_dos_dict()
Returns the added doses as a json-serializable dict. Note that if you
have specified smearing for the DOS plot, the densities returned will
be the smeared densities, not the original densities.


* **Returns**

    Dict of dos data. Generally of the form
    {label: {‘energies’:…, ‘densities’: {‘up’:…}, ‘efermi’:efermi}}



* **Return type**

    dict



#### get_plot(xlim: tuple[float, float] | None = None, ylim: tuple[float, float] | None = None, invert_axes: bool = False, beta_dashed: bool = False)
Get a matplotlib plot showing the DOS.


* **Parameters**


    * **xlim** (*tuple**[**float**, **float**]*) – The energy axis limits. Defaults to None for automatic
    determination.


    * **ylim** (*tuple**[**float**, **float**]*) – The y-axis limits. Defaults to None for automatic determination.


    * **invert_axes** (*bool*) – Whether to invert the x and y axes. Enables chemist style DOS plotting.
    Defaults to False.


    * **beta_dashed** (*bool*) – Plots the beta spin channel with a dashed line. Defaults to False.



#### save_plot(filename, img_format='eps', xlim=None, ylim=None, invert_axes=False, beta_dashed=False)
Save matplotlib plot to a file.


* **Parameters**


    * **filename** – Filename to write to.


    * **img_format** – Image format to use. Defaults to EPS.


    * **xlim** – Specifies the x-axis limits. Set to None for automatic
    determination.


    * **ylim** – Specifies the y-axis limits.


    * **invert_axes** (*bool*) – Whether to invert the x and y axes. Enables chemist style DOS plotting.
    Defaults to False.


    * **beta_dashed** (*bool*) – Plots the beta spin channel with a dashed line. Defaults to False.



#### show(xlim=None, ylim=None, invert_axes=False, beta_dashed=False)
Show the plot using matplotlib.


* **Parameters**


    * **xlim** – Specifies the x-axis limits. Set to None for automatic
    determination.


    * **ylim** – Specifies the y-axis limits.


    * **invert_axes** (*bool*) – Whether to invert the x and y axes. Enables chemist style DOS plotting.
    Defaults to False.


    * **beta_dashed** (*bool*) – Plots the beta spin channel with a dashed line. Defaults to False.



### pymatgen.electronic_structure.plotter.fold_point(p, lattice, coords_are_cartesian=False)
Folds a point with coordinates p inside the first Brillouin zone of the lattice.


* **Parameters**


    * **p** – coordinates of one point


    * **lattice** – Lattice object used to convert from reciprocal to Cartesian coordinates


    * **coords_are_cartesian** – Set to True if you are providing
    coordinates in Cartesian coordinates. Defaults to False.



* **Returns**

    The Cartesian coordinates folded inside the first Brillouin zone



### pymatgen.electronic_structure.plotter.plot_brillouin_zone(bz_lattice, lines=None, labels=None, kpoints=None, fold=False, coords_are_cartesian=False, ax=None, \*\*kwargs)
Plots a 3D representation of the Brillouin zone of the structure.
Can add to the plot paths, labels and kpoints.


* **Parameters**


    * **bz_lattice** – Lattice object of the Brillouin zone


    * **lines** – list of lists of coordinates. Each list represent a different path


    * **labels** – dict containing the label as a key and the coordinates as value.


    * **kpoints** – list of coordinates


    * **fold** – whether the points should be folded inside the first Brillouin Zone.
    Defaults to False. Requires lattice if True.


    * **coords_are_cartesian** – Set to True if you are providing
    coordinates in Cartesian coordinates. Defaults to False.


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – provided by add_fig_kwargs decorator



* **Returns**

    matplotlib figure

    Keyword arguments controlling the display of the figure:

    | kwargs

     | Meaning

     |
    | ------------ | ------------------------------------------------------------------------------------------------- |  |  |  |  |
    | title

            | Title of the plot (Default: None).

                                                                    |
    | show

             | True to show the figure (default: True).

                                                              |
    | savefig

          | ”abc.png” or “abc.eps” to save the figure to a file.

                                                  |
    | size_kwargs

      | Dictionary with options passed to fig.set_size_inches
    e.g. size_kwargs=dict(w=3, h=4)

                 |
    | tight_layout

     | True to call fig.tight_layout (default: False)

                                                        |
    | ax_grid

          | True (False) to add (remove) grid from all axes in fig.
    Default: None i.e. fig is left unchanged.

     |
    | ax_annotate

      | Add labels to  subplots e.g. (a), (b).
    Default: False

                                                 |
    | fig_close

        | Close figure. Default: False.

                                                                         |



### pymatgen.electronic_structure.plotter.plot_brillouin_zone_from_kpath(kpath, ax=None, \*\*kwargs)
Gives the plot (as a matplotlib object) of the symmetry line path in

    the Brillouin Zone.


* **Parameters**


    * **kpath** ([*HighSymmKpath*](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath)) – a HighSymmKPath object


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **\*\*kwargs** – provided by add_fig_kwargs decorator



* **Returns**

    matplotlib figure

    Keyword arguments controlling the display of the figure:

    | kwargs

           | Meaning

                                                                                               |
    | ------------ | ------------------------------------------------------------------------------------------------- |
    | title

            | Title of the plot (Default: None).

                                                                    |
    | show

             | True to show the figure (default: True).

                                                              |
    | savefig

          | ”abc.png” or “abc.eps” to save the figure to a file.

                                                  |
    | size_kwargs

      | Dictionary with options passed to fig.set_size_inches
    e.g. size_kwargs=dict(w=3, h=4)

                 |
    | tight_layout

     | True to call fig.tight_layout (default: False)

                                                        |
    | ax_grid

          | True (False) to add (remove) grid from all axes in fig.
    Default: None i.e. fig is left unchanged.

     |
    | ax_annotate

      | Add labels to  subplots e.g. (a), (b).
    Default: False

                                                 |
    | fig_close

        | Close figure. Default: False.

                                                                         |



### pymatgen.electronic_structure.plotter.plot_ellipsoid(hessian, center, lattice=None, rescale=1.0, ax=None, coords_are_cartesian=False, arrows=False, \*\*kwargs)
Plots a 3D ellipsoid rappresenting the Hessian matrix in input.
Useful to get a graphical visualization of the effective mass
of a band in a single k-point.


* **Parameters**


    * **hessian** – the Hessian matrix


    * **center** – the center of the ellipsoid in reciprocal coords (Default)


    * **lattice** – Lattice object of the Brillouin zone


    * **rescale** – factor for size scaling of the ellipsoid


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **coords_are_cartesian** – Set to True if you are providing a center in
    Cartesian coordinates. Defaults to False.


    * **arrows** – whether to plot arrows for the principal axes of the ellipsoid. Defaults to False.


    * **\*\*kwargs** – passed to the matplotlib function ‘plot_wireframe’.
    Color defaults to blue, rstride and cstride
    default to 4, alpha defaults to 0.2.



* **Returns**

    matplotlib figure and matplotlib ax


Example of use:

    fig,ax=plot_wigner_seitz(struct.reciprocal_lattice)
    plot_ellipsoid(hessian,[0.0,0.0,0.0], struct.reciprocal_lattice,ax=ax)


### pymatgen.electronic_structure.plotter.plot_fermi_surface(data, structure, cbm, energy_levels=None, multiple_figure=True, mlab_figure=None, kpoints_dict=None, colors=None, transparency_factor=None, labels_scale_factor=0.05, points_scale_factor=0.02, interactive=True)
Plot the Fermi surface at specific energy value using Boltztrap 1 FERMI
mode.

The easiest way to use this plotter is:

>
> 1. Run boltztrap in ‘FERMI’ mode using BoltztrapRunner,


> 2. Load BoltztrapAnalyzer using your method of choice (e.g., from_files)


> 3. Pass in your BoltztrapAnalyzer’s fermi_surface_data as this

>     function’s data argument.


* **Parameters**


    * **data** – energy values in a 3D grid from a CUBE file via read_cube_file
    function, or from a BoltztrapAnalyzer.fermi_surface_data


    * **structure** – structure object of the material


    * **energy_levels** (*[**float**]*) – Energy values for plotting the fermi surface(s)
    By default 0 eV correspond to the VBM, as in the plot of band
    structure along symmetry line.
    Default: One surface, with max energy value + 0.01 eV


    * **cbm** (*bool*) – Boolean value to specify if the considered band is a
    conduction band or not


    * **multiple_figure** (*bool*) – If True a figure for each energy level will be
    shown. If False all the surfaces will be shown in the same figure.
    In this last case, tune the transparency factor.


    * **mlab_figure** (*mayavi.mlab.figure*) – A previous figure to plot a new
    surface on.


    * **kpoints_dict** (*dict*) – dictionary of kpoints to label in the plot.
    Example: {“K”:[0.5,0.0,0.5]}, coords are fractional


    * **colors** (*[**tuple**]*) – Iterable of 3-tuples (r,g,b) of integers to define
    the colors of each surface (one per energy level).
    Should be the same length as the number of surfaces being plotted.
    Example (3 surfaces): colors=[(1,0,0), (0,1,0), (0,0,1)]
    Example (2 surfaces): colors=[(0, 0.5, 0.5)]


    * **transparency_factor** (*float*) – Values in the range [0,1] to tune the
    opacity of each surface. Should be one transparency_factor per
    surface.


    * **labels_scale_factor** (*float*) – factor to tune size of the kpoint labels


    * **points_scale_factor** (*float*) – factor to tune size of the kpoint points


    * **interactive** (*bool*) – if True an interactive figure will be shown.
    If False a non interactive figure will be shown, but it is possible
    to plot other surfaces on the same figure. To make it interactive,
    run mlab.show().



* **Returns**

    The mlab plotter and an interactive

        figure to control the plot.




* **Return type**

    ((mayavi.mlab.figure, mayavi.mlab))


Note: Experimental.

    Please, double check the surface shown by using some
    other software and report issues.


### pymatgen.electronic_structure.plotter.plot_labels(labels, lattice=None, coords_are_cartesian=False, ax=None, \*\*kwargs)
Adds labels to a matplotlib Axes.


* **Parameters**


    * **labels** – dict containing the label as a key and the coordinates as value.


    * **lattice** – Lattice object used to convert from reciprocal to Cartesian coordinates


    * **coords_are_cartesian** – Set to True if you are providing.
    coordinates in Cartesian coordinates. Defaults to False.
    Requires lattice if False.


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – kwargs passed to the matplotlib function ‘text’. Color defaults to blue
    and size to 25.



* **Returns**

    matplotlib figure and matplotlib ax



### pymatgen.electronic_structure.plotter.plot_lattice_vectors(lattice, ax=None, \*\*kwargs)
Adds the basis vectors of the lattice provided to a matplotlib Axes.


* **Parameters**


    * **lattice** – Lattice object


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – kwargs passed to the matplotlib function ‘plot’. Color defaults to green
    and linewidth to 3.



* **Returns**

    matplotlib figure and matplotlib ax



### pymatgen.electronic_structure.plotter.plot_path(line, lattice=None, coords_are_cartesian=False, ax=None, \*\*kwargs)
Adds a line passing through the coordinates listed in ‘line’ to a matplotlib Axes.


* **Parameters**


    * **line** – list of coordinates.


    * **lattice** – Lattice object used to convert from reciprocal to Cartesian coordinates


    * **coords_are_cartesian** – Set to True if you are providing
    coordinates in Cartesian coordinates. Defaults to False.
    Requires lattice if False.


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – kwargs passed to the matplotlib function ‘plot’. Color defaults to red
    and linewidth to 3.



* **Returns**

    matplotlib figure and matplotlib ax



### pymatgen.electronic_structure.plotter.plot_points(points, lattice=None, coords_are_cartesian=False, fold=False, ax=None, \*\*kwargs)
Adds Points to a matplotlib Axes.


* **Parameters**


    * **points** – list of coordinates


    * **lattice** – Lattice object used to convert from reciprocal to Cartesian coordinates


    * **coords_are_cartesian** – Set to True if you are providing
    coordinates in Cartesian coordinates. Defaults to False.
    Requires lattice if False.


    * **fold** – whether the points should be folded inside the first Brillouin Zone.
    Defaults to False. Requires lattice if True.


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – kwargs passed to the matplotlib function ‘scatter’. Color defaults to blue



* **Returns**

    matplotlib figure and matplotlib ax



### pymatgen.electronic_structure.plotter.plot_wigner_seitz(lattice, ax=None, \*\*kwargs)
Adds the skeleton of the Wigner-Seitz cell of the lattice to a matplotlib Axes.


* **Parameters**


    * **lattice** – Lattice object


    * **ax** – matplotlib `Axes` or None if a new figure should be created.


    * **kwargs** – kwargs passed to the matplotlib function ‘plot’. Color defaults to black
    and linewidth to 1.



* **Returns**

    matplotlib figure and matplotlib ax