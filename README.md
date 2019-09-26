# iCapture-Pricing
Pricing page with lead capture form

### Info
Because of the complexity involved with trying to replicate the existing iCapture WP environment and the discomfort of working directly with pages and styles on a live site, I have created a discrete webpage with the html and css clearly laid out for copying to the live iCapture site by a qualified developer.
Email me with any questions!

- The index.html contains the HTML that should be able to drop into the Pricing page, replacing the current pricing panels. Look for a comment called
```<!-- iCapture Pricing Panel with Form -->``` (entire code snippet provided below)
This will provide everything needed including the embedded form provided by Tami.

- All of the CSS used can be found in the CSS folder in the "main.css" file
- The graphics used are in the 'img' folder but because they are duplicates of graphics that are used elsewhere, the original source graphics should be used instead.


```
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
