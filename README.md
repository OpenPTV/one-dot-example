# one-dot-example
Jimmy has created a single-point demo to for the test of an epipolar crossing

3D-PTV Group


- A bug reported by Jimmy Kim from UIUC.
- Issue: A calibrated 3D-PTV reconstructs more 3D points than detected 2D Points at large total band.

To test the performance, go to `Run -> Main Parameters -> Observation volume -> Epipolar distance`, change it in the range of 0.05 to 0.5 and see the changes in the `working_folder/res/det_ls`q file. 
