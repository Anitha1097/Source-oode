<messageML>
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <meta name="csrf-token" content="{{ csrf_token() }}">
        <title>Signup - Customer Information</title>
          </head>
    
<body class="bg-color-gradiant">
    <div class="lds-css ng-scope" style="display:none;">
        <div style="width:100%;height:100%" class="lds-eclipse"><div></div></div>
    </div>
<div class="container-scroller">
    <div class="container-fluid page-body-wrapper full-page-wrapper">
        <div class="d-flex align-items-center auth">
            <div class="col-lg-9 mx-auto r_main_container">
                <div class="brand-logo"><a href=""> <img src="{{ asset('images/favicon.png') }}" alt="logo" width="1000" height="300"></a> </div>
                <div class="auth-form-light text-left p-5 register_container">
                    <form action="" method="post" class="form-sample login_form_panel register_form_panel signup_form" id="">

                        <h2>Customer Information</h2>

                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Email <span class="require">*</span></label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter your email" name="email" id="email" value="" />

                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Username <span class="require">*</span></label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter username" name="username" id="username" value=""/>
                                      
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-12">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Password <span class="require">*</span></label>
                                    <div class="col-sm-12">
                                        <input type="password" class="form-control" placeholder="Enter username" name="password" id="password" value=""/>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">First Name</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control"  placeholder="Enter first name" name="first_name" id="first_name" value=""/>
                                        
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Last Name</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control"  placeholder="Enter last name" name="last_name" id="last_name" value=""/>
                                        
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-12">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Address 1</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter address" name="address1" id="address1" value=""/>
                                       
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-12">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Address 2</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter address" name="address2" id="address2" value=""/>
                                     
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">City</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter city" name="city" id="city"  value="" />
                                     
                                    </div>
                                </div>
                            </div>

                        </div> 
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group row">
                                    <label class="col-sm-12 col-form-label">Postal Code</label>
                                    <div class="col-sm-12">
                                        <input type="text" class="form-control" placeholder="Enter postal code" name="postal_code" id="postal_code" onpaste="return false" value="" />
                                      
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="mt-3 login_button_custom signup_btn"> 
                            <button type="submit">Singup</button> 
                        </div>
                    </form>
                </div>
            </div>
        </div>
        <!-- content-wrapper ends -->
    </div>
    <!-- page-body-wrapper ends -->
</div>
<!-- container-scroller -->
</body>
</messageML>


