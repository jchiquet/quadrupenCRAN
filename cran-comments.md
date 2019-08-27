This submission corrects the following request from CRAN maintainers 

CRAN packages using deprecated entry points in external software

Result: WARN 
    Found the following significant warnings:
     bounded_reg.cpp:33:3: warning: 'set_stream_err2' is deprecated [-Wdeprecated-declarations]
     elastic_net.cpp:35:3: warning: 'set_stream_err2' is deprecated [-Wdeprecated-declarations]
     first_order.cpp:71:10: warning: 'sort<arma::mtOp<unsigned int, arma::mtOp<unsigned int, arma::eGlue<arma::eOp<arma::Col<double>, arma::eop_abs>, arma::eOp<arma::eOp<arma::Col<double>, arma::eop_abs>, arma::eop_scalar_minus_post>, arma::eglue_plus>, arma::op_rel_lt_post>, arma::op_find_simple> >' is deprecated [-Wdeprecated-declarations]
     first_order.cpp:147:9: warning: 'sort<arma::eOp<arma::Col<double>, arma::eop_abs> >' is deprecated [-Wdeprecated-declarations]
     first_order.cpp:153:17: warning: 'sort<arma::mtOp<unsigned int, arma::mtOp<unsigned int, arma::eGlue<arma::Col<double>, arma::Col<double>, arma::eglue_minus>, arma::op_rel_gt_post>, arma::op_find_simple> >' is deprecated [-Wdeprecated-declarations]
     first_order.cpp:206:10: warning: 'sort<arma::mtOp<unsigned int, arma::mtOp<unsigned int, arma::eGlue<arma::eOp<arma::Col<double>, arma::eop_abs>, arma::eOp<arma::eOp<arma::eGlue<arma::eOp<arma::Col<double>, arma::eop_neg>, arma::Col<double>, arma::eglue_plus>, arma::eop_abs>, arma::eop_scalar_minus_post>, arma::eglue_plus>, arma::op_rel_lt_post>, arma::op_find_simple> >' is deprecated [-Wdeprecated-declarations] 
Flavors: r-devel-linux-x86_64-debian-clang, r-devel-linux-x86_64-fedora-clang

thanks