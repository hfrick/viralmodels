# viraltab() works

    Code
      print(viraltab(traindata, semilla, target, viralvars, logbase, pliegues,
        repeticiones, rejilla, rank_output = TRUE))
    Message
      i Creating pre-processing data to finalize unknown parameter: mtry
    Output
                          wflow_id              .config .metric   mean std_err n
      1             normalized_KNN Preprocessor1_Model1    rmse 121.25    8.50 2
      2             normalized_KNN Preprocessor1_Model1     rsq   0.75    0.01 2
      3                  simple_rf Preprocessor1_Model1    rmse 124.04   14.10 2
      4                  simple_rf Preprocessor1_Model1     rsq   0.73    0.01 2
      5         simple_CART_bagged Preprocessor1_Model1    rmse 125.74   16.87 2
      6         simple_CART_bagged Preprocessor1_Model1     rsq   0.71    0.04 2
      7              full_quad_KNN Preprocessor1_Model1    rmse 137.43   14.47 2
      8              full_quad_KNN Preprocessor1_Model1     rsq   0.69    0.03 2
      9        normalized_SVM_poly Preprocessor1_Model1    rmse 145.34    4.92 2
      10       normalized_SVM_poly Preprocessor1_Model1     rsq   0.67    0.08 2
      11 normalized_neural_network Preprocessor1_Model1    rmse 167.69   30.36 2
      12 normalized_neural_network Preprocessor1_Model1     rsq   0.57    0.06 2
      13             simple_Cubist Preprocessor1_Model1    rmse 182.88    0.67 2
      14             simple_Cubist Preprocessor1_Model1     rsq   0.44    0.07 2
      15      full_quad_linear_reg Preprocessor1_Model1    rmse 218.04    3.15 2
      16      full_quad_linear_reg Preprocessor1_Model1     rsq   0.36    0.00 2
      17     normalized_SVM_radial Preprocessor1_Model1    rmse 233.06   15.80 2
      18     normalized_SVM_radial Preprocessor1_Model1     rsq   0.70    0.08 2
               preprocessor            model rank
      1              recipe nearest_neighbor    1
      2              recipe nearest_neighbor    1
      3  workflow_variables      rand_forest    2
      4  workflow_variables      rand_forest    2
      5  workflow_variables         bag_tree    3
      6  workflow_variables         bag_tree    3
      7              recipe nearest_neighbor    4
      8              recipe nearest_neighbor    4
      9              recipe         svm_poly    5
      10             recipe         svm_poly    5
      11             recipe              mlp    6
      12             recipe              mlp    6
      13 workflow_variables     cubist_rules    7
      14 workflow_variables     cubist_rules    7
      15             recipe       linear_reg    8
      16             recipe       linear_reg    8
      17             recipe          svm_rbf    9
      18             recipe          svm_rbf    9

