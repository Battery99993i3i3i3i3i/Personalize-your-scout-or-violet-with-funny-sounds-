# Personalize-your-scout-or-violet-with-funny-sounds-
<!DOCTYPE html><html><head>
        <title>Leapfrog</title>
        <meta http-equiv="x-ua-compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" type="text/css" href="css/leapfrog.css" media="screen">
        <link href="https://fonts.googleapis.com/css?family=Muli" rel="stylesheet" type="text/css">
        
        <script async="" src="js/gtm.js"></script><script src="js/jquery.min.js"></script>
    	<script src="js/jquery.localizemod.js" type="text/javascript" charset="utf-8"></script>
		
	<!-- Google Tag Manager -->
	<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0], j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src='https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);})(window,document,'script','dataLayer','GTM-56

	        <script>
            $(function(){
				$('a[href="#chooseLanguage"]').click(function(){
                        window.location = 'locale.php?';
				});
			})
        </script>
    </head>
    
    <body style="background-image:url(c22.jpg);">
    <div id="body_container">
        
	<!-- Google Tag Manager -->
	<noscript><iframe sandbox src='https://www.googletagmanager.com/ns.html?id=GTM-MGKFQB' height='0' width='0' style='display:none;visibility:hidden'></iframe></noscript>
	<!-- End Google Tag Manager -->
	<script>
		if (typeof dataLayer == 'undefined'){ dataLayer = [];}
		dataLayer.push({'locale': 'en-us', 'colorSelected': 'scout'});
		
		function doAnalytics(event, param1, param2)
		{
			// alert('event=' + event + 'param1=' + param1 + 'param2=' + param2);
			if (event == 'calibrationStep')
			{
				dataLayer.push({'event':event, 'lbl':param1});
			}
			else
			{
				dataLayer.push({'event':event, 'form':param1, 'status':param2});
			}
		}
		
		function checkCharCount(checkFieldName, maxLimit, errorFieldName, errorTextName){ 			
			var checkField = $(checkFieldName);
			var errorField = $('#' + errorFieldName);
			if (errorField)
			{
				if ((checkField.val()).length >= maxLimit) // if too long...trim it!
				{
					errorField.text($('input[name=' + errorTextName + ']').val());
				}
				else
				{
					errorField.text('');
				}
			}
	    };
		
	</script>
	
	<div class="header_container">
	            <a class="link_no_underline" href="index.php">
	            	<img id="logo" src="images/logo.png">
	           	</a>
	            	<img id="headerpng" src="images/header_english.png">
	        </div>
	        <div class="index_title" data-localize="main_title">
            
        </div>
        <div class="home-explanation" data-localize="home_explanation">
            
        </div>
        <div class="bear_container">
            <div class="scout">
                <a href="https://scout.leapfrog.com/mypals2/login.php?chosen=Scout">
                    <img id="scout_bear" src="images/scout_bear_english.png">
                </a>
            </div>
            <div class="violet">
                <a href="https://scout.leapfrog.com/mypals2/login.php?chosen=Violet">
                    <img id="violet_bear" src="images/violet_bear_english.png">
                </a>
            </div>

        </div>


                <div class="bear_container ">
            <div class="home-explanation" data-localize="home_explanation_2">

            </div>
            <div class="scout ">
                <a href="https://smartypaws.leapfrog.com/index.html">
                    <img id="scout_bear" src="images/welcome-scout.png">
                </a>
            </div>
                            <div class="violet">
                    <a href="https://smartypaws.leapfrog.com/index.html">
                        <img id="violet_bear" src="images/welcome-violet.png">
                    </a>
                </div>
                    </div>
            
	 	 
        <div class="body_footer_space"></div>
     </div>
     
	 
    <div id="footer_container">
        <div id="footer">
	        <div id="footer_inside">
	        	<div class="footer_content">
			        <table>
													<tbody><tr height="10" width="320">
								<td width="230px" class="footer_medium_text">
									<span class="footer_medium_text" data-localize="footer_privacy_see_legal">
									</span>
									<a href="https://www.leapfrog.com/en-us/legal/privacy" target="_blank" class="footer_medium_text_link privacy-underline"><span data-localize="footer_privacy_go_legal"></span></a>
									<span class="footer_medium_text" data-localize="footer_privacy_detail_legal">
									</span>
								</td>
							</tr>
										        <tr height="10" width="320">
					        <td width="230px">
								<a href="https://www.leapfrog.com/en-us/legal" target="_blank" class="footer_medium_text_link">
									<span class="footer_medium_text" data-localize="footer_go_legal">
									   
									</span>
								</a>
								<span class="footer_medium_text">
								     |  
								</span>
								<a href="https://www.leapfrog.com/en-us/legal/privacy" target="_blank" class="footer_medium_text_link">
									<span class="footer_medium_text" data-localize="footer_go_privacy">
									   
									</span>
								</a>
								<span id="logoutSpan" class="hide_at_start">
									<span class="footer_medium_text">
									     |  
									</span>
									<a href="logout.php" class="footer_medium_text_link">
										<span class="footer_medium_text" data-localize="footer_go_logout">
										   
										</span>
									</a>
								</span>
					        </td>
					        <td width="90px">
									<span class="footer_large_text" data-localize="footer_location">
									   
									</span>
					        </td>
						</tr>
				        <tr height="10" width="320">
					        <td width="230px" class="copyright_td_line_height">
						        <span class="footer_smalltext" data-localize="copyright_rights_reserved"></span>	
							</td>
								<td width="90px" class="text_top">
									<span class="footer_medium_text" data-localize="footer_location_en-us">
									   
									</span>
									<a href="locale.php" class="footer_medium_text_link_change_location">
										<span class="footer_large_text" data-localize="footer_change_location">
										   
										</span>
									</a>
								</td>
				        </tr>
			        </tbody></table>
	        	</div>
	        </div>	
        </div>	
    </div>	
	
	<script type="text/javascript" charset="utf-8">
      $(function(){
        // var opts = { language: "es", pathPrefix: "lang" };
        // var opts = { pathPrefix: "lang" };
        var opts = { language: "en-us", pathPrefix: "lang" };
        $("[data-localize]").localize("main", opts);
      })
    </script>
	<script>
		var resizeTimeoutId;
		function finishResize() {
		  	window.clearTimeout(resizeTimeoutId);
			$(document.body).removeClass('resetBackgroundSize');
		}
	    $( window ).resize(function() {
	    	// var cacheBreaker = (new Date()).getTime();
	    	// var imageUrl = '../images/bg_leapfrog.jpg' + '?cb=' + cacheBreaker;
	    	// var imageUrl = '../images/bg_leapfrog.jpg';
			// $(document.body).css('background-image', 'url(' + imageUrl + ')');
			$(document.body).addClass('resetBackgroundSize');
			resizeTimeoutId = window.setTimeout(finishResize, 500);
		});
	</script>
     

</body></html>
