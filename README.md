# iCapture-Pricing
Pricing page with lead capture form

### Info
Because of the complexity involved with trying to replicate the existing iCapture WP environment and the discomfort of working directly with pages and styles on a live site, I have created a discrete webpage with the html and css clearly laid out for copying to the live iCapture site by a qualified developer.
Email me with any questions!

- The index.html contains the HTML that should be able to drop into the Pricing page, replacing the current pricing panels. Look for a comment called
```<!-- iCapture Pricing Panel with Form -->``` (entire code snippet provided below)
This will provide everything needed including the embedded form provided by Tami.

- All of the CSS used can be found in the CSS folder in the "main.css" file.  The minified version can be copied below.
- The graphics used are in the 'img' folder but because they are duplicates of graphics that are used elsewhere, the original source graphics should be used instead.

### HTML
```html
<!-- iCapture Pricing Panel with Form -->
        <div class="row">
            <div class="pricingPanel col-md-6">
                <h2 class="pricingPanel_h2">The #1 Lead Capture and Prioritization Platform</h2>
                <p class="pricingPanel_body">
                    We’d love to prepare a customized proposal for you!<br><br>
                    iCapture’s pricing model depends on a few factors specific to your team, so we’ll need to get in touch to give you accurate pricing info. <br><br>
                    Simply fill out this form to get your personalized iCapture price today!</p>
                    <p class="pricingPanel_body" style="padding: 10px 0px 0px 20px;">
                        Trusted by companies around the world!
                    </p>
                    <div class="row pricingForm_proof_container">
                        <div class="col-md-3" id="pricingForm_proof_staples"></div>
                        <div class="col-md-3" id="pricingForm_proof_ge"></div>
                        <div class="col-md-3" id="pricingForm_proof_trendMicro"></div>
                        <div class="col-md-3" id="pricingForm_proof_3m"></div>
                    </div>
            </div>
            <div class="col-md-6">
                <h2 class=pricingForm_h2>Request Pricing</h2>
                <p>
                    <form class="pricingForm" role="form">
                        <!--[if lte IE 8]>
                        <script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/v2-legacy.js"></script>
                        <![endif]-->
                        <script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/v2.js"></script>
                        <script>
                          hbspt.forms.create({
                        portalId: "6333205",
                        formId: "04f2b36f-b88e-4937-a43a-930339610c3f"
                        });
                        </script>
                        <!-- <div class="form-group">
                            <label for="firstName">First Name</label>
                            <input type="text" placeholder="Enter your first name" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="lastName">Last Name</label>
                            <input type="password" placeholder="Enter your last name" class="form-control">
                        </div> -->
                    </form>
                </p>
            </div>
        </div>
<!-- END iCapture Pricing Panel -->
```

### CSS (Minified)
```CSS
.pricingPanel{background:#f3f6fb 0 0 no-repeat padding-box;-webkit-box-shadow:0 3px 6px #00000029;box-shadow:0 3px 6px #00000029;border-radius:5px;opacity:1}.pricingPanel_h2{font-size:40px;text-align:center;letter-spacing:0;color:#1c3664;opacity:1}.pricingPanel_body{padding:30px 20px 50px 20px;text-align:left;font-size:18px!important;letter-spacing:0;color:#1c3664AC;opacity:1}.pricingForm_proof_container{padding:0;margin:0;width:100%;height:100px}#pricingForm_proof_staples{background:transparent url(https://www.icapture.com/wp-content/uploads/easy_logo_slider/284802honeywell_logo-113.png) 0 0 no-repeat padding-box;opacity:1;width:130px;height:60px;background-position:center;background-size:contain;display:inline-block}#pricingForm_proof_ge{background:transparent url(https://www.icapture.com/wp-content/uploads/easy_logo_slider/663050GECriticalPowerLogo-113.png) 0 0 no-repeat padding-box;opacity:1;width:130px;height:60px;background-position:center;background-size:contain;display:inline-block}#pricingForm_proof_trendMicro{background:transparent url(https://www.icapture.com/wp-content/uploads/easy_logo_slider/657374TrendMicroLogo-113.png) 0 0 no-repeat padding-box;opacity:1;width:130px;height:60px;background-position:center;background-size:contain;display:inline-block}#pricingForm_proof_3m{background:transparent url(https://www.icapture.com/wp-content/uploads/easy_logo_slider/8895803M_logo-113.png) 0 0 no-repeat padding-box;opacity:1;width:130px;height:60px;background-position:center;background-size:contain;display:inline-block}.pricingForm{padding:0 30px 20px 30px}.pricingForm label{padding-left:3px;font-size:11px;letter-spacing:0;color:#1c3664;text-transform:uppercase;opacity:1}.pricingForm_h2{padding-top:0;margin-top:0;font-size:40px;text-align:center;letter-spacing:0;color:#1c3664;opacity:1}@media screen and (max-width:600px){.pricingForm_proof_container{display:none}}
```
