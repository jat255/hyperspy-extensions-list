
This repository contains a list of [HyperSpy](https://hyperspy.org)
extensions. HyperSpy extensions are packages that use the HyperSpy extension
mechanism to add functionality to HyperSpy (such as GUI widgets) and/or
register new subclasses of HyperSpy objects (such as components and signals).

# Adding a HyperSpy extension to the list

Note that the information in this file is automatically generated. To add a
package just [open an
issue](https://github.com/hyperspy/hyperspy-extensions-list/issues) with the
request and we'll get it done for you. Alternatively, [follow these
instructions](https://github.com/hyperspy/hyperspy-extensions-list/blob/master/doc/how_to_add_extension.md)
and send us a pull request.

# (Known) HyperSpy extensions

| Package name                                                                   | Brief description                                                                      |
|--------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [exspy](https://github.com/hyperspy/exspy)                                     | Electron energy loss spectroscopy (EELS) and X-ray energy dispersive spectroscopy (EDS)|
| [holospy](https://github.com/hyperspy/holospy)                                 | Electron holography                                                                    |
| [hyperspy-gui-ipywidgets](https://github.com/hyperspy/hyperspy_gui_ipywidgets) | ipywidgets widgets for HyperSpy                                                        |
| [hyperspy-gui-traitsui](https://github.com/hyperspy/hyperspy_gui_traitsui)     | traitsui widgets for HyperSpy                                                          |
| [kikuchipy](https://github.com/pyxem/kikuchipy)                                | Processing, simulating and indexing of electron backscatter diffraction patterns       |
| [LumiSpy](https://github.com/lumispy/lumispy)                                  | Analysis of luminescence spectroscopy data                                             |
| [pyxem](https://github.com/pyxem/pyxem)                                        | Multi-dimensional diffraction microscopy                                               |
| [rosettasciio](https://github.com/hyperspy/rosettasciio)                       | Reading and writing of scientific data formats                                         |
| [etspy](https://github.com/usnistgov/etspy)                                    | Electron tomogoraphy processing and reconstruction tools                               |

## List of `signal_type` classes provided by the different HyperSpy extensions in alphabetical order


|        signal_type         |                                  aliases                                  |         class name         | package |
| :------------------------: | :-----------------------------------------------------------------------: | :------------------------: | :-----: |
|         beam_shift         |                                                                           |         BeamShift          |  pyxem  |
|           CL_SEM           |                       CLSEM, cathodoluminescence SEM                      |       CLSEMSpectrum        | lumispy |
|          CL_STEM           |                      CLSTEM, cathodoluminescence STEM                     |       CLSTEMSpectrum       | lumispy |
|             CL             |                      CLSpectrum, cathodoluminescence                      |         CLSpectrum         | lumispy |
|        correlation         |                                                                           |       Correlation1D        |  pyxem  |
|        correlation         |                                                                           |       Correlation2D        |  pyxem  |
|            dpc             |                                                                           |       DPCBaseSignal        |  pyxem  |
|            dpc             |                                                                           |        DPCSignal1D         |  pyxem  |
|            dpc             |                                                                           |        DPCSignal2D         |  pyxem  |
|     DielectricFunction     |                            dielectric function                            |     DielectricFunction     |  exspy  |
|        diffraction         |                                                                           |       Diffraction1D        |  pyxem  |
|        diffraction         |                                                                           |       Diffraction2D        |  pyxem  |
|    diffraction_variance    |                                                                           |   DiffractionVariance1D    |  pyxem  |
|    diffraction_variance    |                                                                           |   DiffractionVariance2D    |  pyxem  |
|    diffraction_vectors     |                                                                           |     DiffractionVectors     |  pyxem  |
|    diffraction_vectors     |                                                                           |    DiffractionVectors1D    |  pyxem  |
|    diffraction_vectors     |                                                                           |    DiffractionVectors2D    |  pyxem  |
|        tensor_field        |                                                                           |  DisplacementGradientMap   |  pyxem  |
|          EDS_SEM           |                                                                           |       EDSSEMSpectrum       |  exspy  |
|          EDS_TEM           |                                                                           |       EDSTEMSpectrum       |  exspy  |
|            EELS            |                                  TEM EELS                                 |        EELSSpectrum        |  exspy  |
|             EL             |                      ELSpectrum, electroluminescence                      |         ELSpectrum         | lumispy |
|    electron_diffraction    |                                                                           |   ElectronDiffraction1D    |  pyxem  |
|    electron_diffraction    |                                                                           |   ElectronDiffraction2D    |  pyxem  |
|          hologram          |                                                                           |       HologramImage        | holospy |
|        Luminescence        |                            LuminescenceSpectrum                           |        LumiSpectrum        | lumispy |
|         Transient          |            TRLumi, TR luminescence, time-resolved luminescence            |       LumiTransient        | lumispy |
|       TransientSpec        | TRLumiSpec, TR luminescence spectrum, time-resolved luminescence spectrum |   LumiTransientSpectrum    | lumispy |
|             PL             |                       PLSpectrum, photoluminescence                       |         PLSpectrum         | lumispy |
| pair_distribution_function |                                                                           | PairDistributionFunction1D |  pyxem  |
|     polar_diffraction      |                                                                           |     PolarDiffraction2D     |  pyxem  |
|           power            |                                                                           |          Power2D           |  pyxem  |
|          RecStack          |                            Reconstructed stack                            |          RecStack          |  etspy  |
|     reduced_intensity      |                                                                           |     ReducedIntensity1D     |  pyxem  |
|         TomoStack          |                  Tomography, Tomography stack, TiltStack                  |         TomoStack          |  etspy  |
|      vector_matching       |                                                                           |   VectorMatchingResults    |  pyxem  |
|     virtual_dark_field     |                                                                           |   VirtualDarkFieldImage    |  pyxem  |


