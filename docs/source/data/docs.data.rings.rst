Rings
-----

Broad rings 
~~~~~~~~~~~

Detection and quantification of grey level differences of ca. 1% in the electrode particles – local
tomography and broad ring artifacts are making this challenging task even more difficult. Standard
solutions used at the TOMCAT beamline (e.g. constant padding) are not sufficient in the phase
retrieved case :cite:`paganin:02`, if small grey level differences need to be reliably detected. 
A more sophisticated flat-field correction might help for the ring artefact problem.

+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00071                      |  
+=========================================+============================+
|             Image preview               | |00071|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00071_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | SLS TOMCAT                 |  
+-----------------------------------------+----------------------------+
|             Sample name                 | SLS_01                     |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | 24.999 keV                 |  
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 15 mm                      |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 1201                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 200 (100 before 100 after) | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | 10                         |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 0.65 µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1302.50                    |
+-----------------------------------------+----------------------------+


To load the data sets and perform a basic reconstruction using `tomopy <https://tomopy.readthedocs.io>`_ ::

    tomopy recon --file-name tomo_00071.h5 --rotation-axis 1302.50

To enable phase retrieval un-comment the appropriate setting in :download:`tomopy_rec.py <../../demo/tomopy_rec.py>` 

.. _tomo_00071: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00071%2F

.. |00071| image:: ../img/tomo_00071.png
    :width: 20pt
    :height: 20pt


Soft Tissue
~~~~~~~~~~~

To limit radiation damage of soft tissue, the energy is set in the hard x-ray regime. Samples are weakly absorbing and generate severe ring artefact. Below are two soft tissue sample measurements collected as follows:


+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00072                      |  
+=========================================+============================+
|             Image preview               | |00072|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00072_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | APS 2-BM                   |  
+-----------------------------------------+----------------------------+
|             Sample name                 | soft tissue                |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | 20 keV                     |  
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 15 mm                      |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 1500                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 10                         | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | 10                         |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 1.43 µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1403                       |
+-----------------------------------------+----------------------------+


.. _tomo_00072: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00072%2F

.. |00072| image:: ../img/tomo_00072.png
    :width: 20pt
    :height: 20pt


+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00076                      |  
+=========================================+============================+
|             Image preview               | |00076|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00076_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | APS 2-BM                   |  
+-----------------------------------------+----------------------------+
|             Detector                    | PCO edge                   |
+-----------------------------------------+----------------------------+
|             Sample name                 | soft tissue                |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | braod 60-70 keV            |  
+-----------------------------------------+----------------------------+
|             Exposure Time               | 100 ms                     |         
+-----------------------------------------+----------------------------+
|             Scan Type                   | Fly Scan                   |
+-----------------------------------------+----------------------------+
|             Scan Speed                  | 0.75 deg/s                 |
+-----------------------------------------+----------------------------+
|             Shutter Mode                | Rolling                    |
+-----------------------------------------+----------------------------+
|             Scintillator                | 10um LuAG                  |
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 90 mm                      |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 2000                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 10 pre scan                | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | 10                         |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 2.2  µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1275                       |
+-----------------------------------------+----------------------------+


.. _tomo_00076: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00076%2F

.. |00076| image:: ../img/tomo_00076.png
    :width: 20pt
    :height: 20pt

To load the data sets and perform a basic reconstruction using `tomopy <https://tomopy.readthedocs.io>`_ ::

    tomopy recon --file-name tomo_00072.h5 --rotation-axis 1403 
    tomopy recon --file-name tomo_00076.h5 --rotation-axis 1275  

To enable phase retrieval un-comment the appropriate setting in :download:`tomopy_rec.py <../../demo/tomopy_rec.py>` 

Al Samples
~~~~~~~~~~

Here we present two measuremend done on the same Al sample presenting mild ring artefacts.
Mesurements have a different white field data collection strategy.

+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00073                      |  
+=========================================+============================+
|             Image preview               | |00073|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00073_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | APS 2-BM                   |  
+-----------------------------------------+----------------------------+
|             Sample name                 | AlO2_01                    |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | 25 keV                     |  
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 10 mm                      |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 1500                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 100 at the end             | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | 1                          |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 0.74 µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1001.2                     |
+-----------------------------------------+----------------------------+


.. _tomo_00073: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00073%2F

.. |00073| image:: ../img/tomo_00073.png
    :width: 20pt
    :height: 20pt


+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00074                      |  
+=========================================+============================+
|             Image preview               | |00074|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00074_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | APS 2-BM                   |  
+-----------------------------------------+----------------------------+
|             Sample name                 | AlO2_02                    |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | 25 keV                     |  
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 10 mm                      |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 1500                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 200 (100 pre 100 post)     | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | 1                          |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 0.74 µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1001.6                     |
+-----------------------------------------+----------------------------+


.. _tomo_00074: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00074%2F

.. |00074| image:: ../img/tomo_00074.png
    :width: 20pt
    :height: 20pt


White beam
~~~~~~~~~~

To increase data collection speed on a BM source, the beamline is set in white beam mode. This data set contains mild ring artefacts and was collected with the following experimental conditions:


+-----------------------------------------+----------------------------+
|             tomo_ID                     | 00075                      |  
+=========================================+============================+
|             Image preview               | |00075|                    |  
+-----------------------------------------+----------------------------+
|             Download                    | tomo_00075_                |  
+-----------------------------------------+----------------------------+
|             Instrument                  | APS 2-BM                   |  
+-----------------------------------------+----------------------------+
|             Detector                    | PCO DIMAX                  |
+-----------------------------------------+----------------------------+
|             Exposure Time               | 5 ms                       |         
+-----------------------------------------+----------------------------+
|             Scan Type                   | Fly Scan                   |
+-----------------------------------------+----------------------------+
|             Scan Speed                  | 9 deg/s                    |
+-----------------------------------------+----------------------------+
|             Shutter Mode                | Rolling                    |
+-----------------------------------------+----------------------------+
|             Scintillator                | 100um LuAG 28mm Glass      |
+-----------------------------------------+----------------------------+
|             Sample name                 | Ceramic Rod + Clay + Wire  |  
+-----------------------------------------+----------------------------+
|             X-ray energy                | white beam                 |  
+-----------------------------------------+----------------------------+
|             Sample-to-detector distance | 110 mm                     |  
+-----------------------------------------+----------------------------+
|             Scan Range                  | 180 degree                 |
+-----------------------------------------+----------------------------+
|             Number of Projections       | 3000                       |
+-----------------------------------------+----------------------------+
|             White Fields                | 200 (100 pre 100 post)     | 
+-----------------------------------------+----------------------------+
|             Dark Fields                 | none                       |  
+-----------------------------------------+----------------------------+
|             Pixel size                  | 1.43 µm                    |  
+-----------------------------------------+----------------------------+
|             Rotation axis location      | 1010                       |
+-----------------------------------------+----------------------------+


.. _tomo_00075: https://app.globus.org/file-manager?origin_id=e133a81a-6d04-11e5-ba46-22000b92c6ec&origin_path=%2Ftomobank%2Ftomo_00075%2F

.. |00075| image:: ../img/tomo_00075.png
    :width: 20pt
    :height: 20pt

To load the data sets and perform a basic reconstruction using `tomopy <https://tomopy.readthedocs.io>`_ ::

    tomopy recon --file-name tomo_00073.h5 --rotation-axis 1001.2 
    tomopy recon --file-name tomo_00074.h5 --rotation-axis 1001.6 
    tomopy recon --file-name tomo_00075.h5 --rotation-axis 1010  

To enable phase retrieval un-comment the appropriate setting in :download:`tomopy_rec.py <../../demo/tomopy_rec.py>` 


add datasets APS05 
~~~~~~~~~~~~~~~~~~

from https://drive.google.com/drive/folders/0B78bW1AwveI_WVdXQlBRMVBKQk0

