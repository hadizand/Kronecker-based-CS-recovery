# Kronecker-based-CS-recovery
Kronecker technique for improving quality of the signal in compressive sensing recovery

 This code shows the effect of Kronecker technique on compressive sensing recovery; this technique has been used for different signals and measurement matrices, 
  and it has been published in multiple journals and conference papers:

% [1] H. Zanddizari, S. Rajan, and H. Zarrabi, “Increasing the quality of reconstructed  signal  in  compressive  sensing  utilizing  Kronecker  technique,”
     % Biomedical Engineering Letters, vol. 8, no. 2, pp. 239–247, May 2018.

% [2] D. Mitra, H. Zanddizari, and S. Rajan, "Investigation of Kronecker-based recovery of compressed ECG signal," 
     % IEEE Transactions on Instrumentation and Measurement, pp. 1-1, 2019.

% [3] D. Mitra, H. Zanddizari, and S. Rajan, “Improvement of signal quality during recovery of compressively sensed ECG signals,” 
     % in 2018 IEEE International Symposium on Medical Measurements and Applications (MeMeA), June 2018, pp. 1–5.

% [4] D. Mitra, H. Zanddizari, and S. Rajan, “Improvement of recovery in segmentation-based parallel compressive sensing,” 
     % in 2018 IEEE International Symposium on Signal Processing and Information Technology (ISSPIT), Dec 2018, pp. 501–506.

%Author Hadi Zanddizari, 
% hadiz@mail.usf.edu
% hadizand@alumni.iust.ac.ir


%-----------The main objective of this approach
% For fast and efficient compression, sensing phase in compressive sensing can be done in very small size, because in this case: 
    %it requires very small measurement matrix, 
    %less number of multiplication and addition operations, and
    %less delay for generating compressed samples
    % which can be used for sensors with low computational resources.
 But sensing in small size degrades quality of recovery. Kronecker
 technique can be used in order to improve the quality of recovered signal.

%---------------------------------------CS Recovery algorithm
 Any recovery algorithm can be used. In this code, Sl0 which is very fast CS recovery algorithm is used.
 [sl0-reference]: http://ee.sharif.edu/~SLzero/

%----------------------------------Database
 In this code, an ECG signal from MIT-BIH Arrhythmia database which is public dataset is used.
 [Database Reference]:MIT-BIH Arrhythmia Database. [Online]. Available: http://www.physionet.org/physiobank/database/mitdb/
 
