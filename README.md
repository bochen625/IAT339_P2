# IAT339_P2
Website for Lumi

Naming convention
- camelCase (ie: featureModule)
- the name should be descriptive and the individual should be able to understand what it is by reading the name

Structure:
- Section header and description (See below for example)
- Pattern overview container (Encapsulates everything BUT the title/description)
        Example:
            <h4> Title of Module </h4>
            <p class="note">Description: What it's used for, who created it, and who is responsible for maintaining it.</p>
            
            <div class="patternOverview">
                <!-- Code for Feature Module -->
                <!-- Code Snippet for Feature Module -->
            </div>
- Code snippet container (Contains the code)
        Example:
            <div class="codeSnippetContainer">
                <div class="codeSnippetPattern">
                    <p class="codeSnippetTitle">HTML</p>
                    <code>
                        <!--HTML Code-->
                    </code>
                </div>

                <div class="codeSnippetPattern">
                    <p class="codeSnippetTitle">CSS</p>
                    <code>
                        <!--CSS Code-->
                    </code>
                </div>
            </div>

Global CSS variables (These variables allow you to call a colour WITHOUT specifying the hexcode):
<!--Blue-->
--CTAColour

<!--Gray-->
--textColour

<!--Off white-->
--bgColour

<!--gradient-->
--gradientColour

<!--drop Shadow-->
--dropShadow

    - Examples of how these global variables are used in CSS:
        color: var(--textColour); <!--This will make the text gray-->
        background-color: var(--bgColour); <!--This will make the background offwhite-->
        background-color: var(--CTAColour); <!--This will make the background blue-->
        background-image: var(--gradientColour); <!--This will create a gradient background using Lumi's brand colours-->
        box-shadow: var(--dropShadow); <!--This will create a light drop shadow around a box-->

