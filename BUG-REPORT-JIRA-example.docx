<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=unicode">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 12">
<meta name=Originator content="Microsoft Word 12">
<link rel=File-List href="BUG-REPORT-JIRA-TEMPLATE_files/filelist.xml">
<title>[#BUG-1] Login for a user is not working with valid username and
password with 500 error in login API</title>
<!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>HP</o:Author>
  <o:LastAuthor>HP</o:LastAuthor>
  <o:Revision>2</o:Revision>
  <o:TotalTime>10</o:TotalTime>
  <o:Created>2023-03-06T08:01:00Z</o:Created>
  <o:LastSaved>2023-03-06T08:11:00Z</o:LastSaved>
  <o:Pages>1</o:Pages>
  <o:Words>132</o:Words>
  <o:Characters>754</o:Characters>
  <o:Company>by adguard</o:Company>
  <o:Lines>6</o:Lines>
  <o:Paragraphs>1</o:Paragraphs>
  <o:CharactersWithSpaces>885</o:CharactersWithSpaces>
  <o:Version>12.00</o:Version>
 </o:DocumentProperties>
</xml><![endif]-->
<link rel=themeData href="BUG-REPORT-JIRA-TEMPLATE_files/themedata.thmx">
<link rel=colorSchemeMapping
href="BUG-REPORT-JIRA-TEMPLATE_files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:Zoom>130</w:Zoom>
  <w:SpellingState>Clean</w:SpellingState>
  <w:GrammarState>Clean</w:GrammarState>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EN-US</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:DontVertAlignCellWithSp/>
   <w:DontBreakConstrainedForcedTables/>
   <w:DontVertAlignInTxbx/>
   <w:Word11KerningPairs/>
   <w:CachedColBalance/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="--"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="true"
  DefSemiHidden="true" DefQFormat="false" DefPriority="99"
  LatentStyleCount="267">
  <w:LsdException Locked="false" Priority="0" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 9"/>
  <w:LsdException Locked="false" Priority="35" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" Priority="10" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" Priority="1" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" Priority="11" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" Priority="22" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" Priority="59" SemiHidden="false"
   UnhideWhenUsed="false" Name="Table Grid"/>
  <w:LsdException Locked="false" UnhideWhenUsed="false" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" UnhideWhenUsed="false" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" QFormat="true" Name="TOC Heading"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--hr.FULLCONTENT
	{background-attachment:scroll;
	background-position-x:50%;
	background-position-y:50%;}

 /* Font Definitions */
 @font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-format:other;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Tahoma;
	panose-1:2 11 6 4 3 5 4 4 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-520081665 -1073717157 41 0 66047 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
h3
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 3 Char";
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	mso-outline-level:3;
	font-size:13.5pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	font-weight:bold;}
p
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.MsoAcetate, li.MsoAcetate, div.MsoAcetate
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"Balloon Text Char";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:8.0pt;
	font-family:"Tahoma","sans-serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.tableborder, li.tableborder, div.tableborder
	{mso-style-name:tableborder;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	background:white;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.grid, li.grid, div.grid
	{mso-style-name:grid;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	background:white;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.tablabel, li.tablabel, div.tablabel
	{mso-style-name:tablabel;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	border:none;
	mso-border-top-alt:solid #CCCCCC .75pt;
	mso-border-left-alt:solid #CCCCCC .75pt;
	mso-border-right-alt:solid #CCCCCC .75pt;
	padding:0in;
	mso-padding-alt:2.0pt 2.0pt 0in 2.0pt;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	font-weight:bold;}
p.subtext, li.subtext, div.subtext
	{mso-style-name:subtext;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.nopadding, li.nopadding, div.nopadding
	{mso-style-name:nopadding;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
p.subtext1, li.subtext1, div.subtext1
	{mso-style-name:subtext1;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0in;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	font-size:7.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
span.Heading3Char
	{mso-style-name:"Heading 3 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Heading 3";
	mso-ansi-font-size:12.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Cambria","serif";
	mso-ascii-font-family:Cambria;
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:Cambria;
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#4F81BD;
	mso-themecolor:accent1;
	font-weight:bold;}
span.BalloonTextChar
	{mso-style-name:"Balloon Text Char";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Balloon Text";
	mso-ansi-font-size:8.0pt;
	mso-bidi-font-size:8.0pt;
	font-family:"Tahoma","sans-serif";
	mso-ascii-font-family:Tahoma;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Tahoma;
	mso-bidi-font-family:Tahoma;}
span.SpellE
	{mso-style-name:"";
	mso-spl-e:yes;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-size:10.0pt;
	mso-ansi-font-size:10.0pt;
	mso-bidi-font-size:10.0pt;}
@page Section1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;
	mso-header-margin:.5in;
	mso-footer-margin:.5in;
	mso-paper-source:0;}
div.Section1
	{page:Section1;}
 /* List Definitions */
 @list l0
	{mso-list-id:1235242843;
	mso-list-template-ids:1993380362;}
ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-qformat:yes;
	mso-style-parent:"";
	mso-padding-alt:0in 5.4pt 0in 5.4pt;
	mso-para-margin:0in;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman","serif";}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="2050"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=EN-US link=blue vlink=purple style='tab-interval:.5in'>

<div class=Section1>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width="100%"
 style='width:100.0%;background:white;border-collapse:collapse;mso-yfti-tbllook:
 1184;mso-padding-alt:0in 0in 0in 0in'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width="100%" colspan=2 valign=top style='width:100.0%;border:solid #CCCCCC 1.0pt;
  mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <h3><span style='mso-fareast-font-family:"Times New Roman"'>[BUG-1]&nbsp;<a
  href="https://bugz.atlassian.net/browse/BUG-1">Login for a user is not
  working with valid username and password with 500 error in login API</a> <o:p></o:p></span></h3>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Status:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td width="80%" valign=top style='width:80.0%;border-top:none;border-left:
  none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>To
  Do<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Project:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td width="80%" valign=top style='width:80.0%;border-top:none;border-left:
  none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Defect<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td valign=top style='border:solid #CCCCCC 1.0pt;border-top:none;mso-border-top-alt:
  solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Components:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;
  border-right:solid #CCCCCC 1.0pt;mso-border-top-alt:solid #CCCCCC .75pt;
  mso-border-left-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Login
  <o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4'>
  <td valign=top style='border:solid #CCCCCC 1.0pt;border-top:none;mso-border-top-alt:
  solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Affects
  versions:</span></b><span style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;
  border-right:solid #CCCCCC 1.0pt;mso-border-top-alt:solid #CCCCCC .75pt;
  mso-border-left-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>None
  <o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5;mso-yfti-lastrow:yes'>
  <td valign=top style='border:solid #CCCCCC 1.0pt;border-top:none;mso-border-top-alt:
  solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Fix
  versions:</span></b><span style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;
  border-right:solid #CCCCCC 1.0pt;mso-border-top-alt:solid #CCCCCC .75pt;
  mso-border-left-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>RELEASE
  2<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width="100%"
 style='width:100.0%;background:white;border-collapse:collapse;mso-yfti-tbllook:
 1184;mso-padding-alt:0in 0in 0in 0in'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Type:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td width="30%" valign=top style='width:30.0%;border:solid #CCCCCC 1.0pt;
  border-left:none;mso-border-left-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Task
  <o:p></o:p></span></p>
  </td>
  <td valign=top style='border:solid #CCCCCC 1.0pt;border-left:none;mso-border-left-alt:
  solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Priority:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td nowrap valign=top style='border:solid #CCCCCC 1.0pt;border-left:none;
  mso-border-left-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Medium
  <o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Reporter:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td width="30%" valign=top style='width:30.0%;border-top:none;border-left:
  none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span class=SpellE><span style='mso-fareast-font-family:
  "Times New Roman"'>Garima</span></span><span style='mso-fareast-font-family:
  "Times New Roman"'> Verma<o:p></o:p></span></p>
  </td>
  <td width="20%" valign=top style='width:20.0%;border-top:none;border-left:
  none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Assignee:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td width="30%" nowrap valign=top style='width:30.0%;border-top:none;
  border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>ABC
  DEVELOPER<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Resolution:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td width="30%" nowrap valign=top style='width:30.0%;border-top:none;
  border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Unresolved
  <o:p></o:p></span></p>
  </td>
  <td width="20%" valign=top style='width:20.0%;border-top:none;border-left:
  none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Votes:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td width="30%" nowrap valign=top style='width:30.0%;border-top:none;
  border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>0 <o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Labels:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td nowrap colspan=3 valign=top style='border-top:none;border-left:none;
  border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'
  id=labels-10007-value>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>Team
  1 <o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Remaining
  Estimate:</span></b><span style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td width="80%" nowrap colspan=3 valign=top style='width:80.0%;border-top:
  none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>3d<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Time
  Spent:</span></b><span style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td width="80%" nowrap colspan=3 valign=top style='width:80.0%;border-top:
  none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>0d<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:6;mso-yfti-lastrow:yes'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  border-top:none;mso-border-top-alt:solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;
  background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Original
  estimate:</span></b><span style='mso-fareast-font-family:"Times New Roman"'><o:p></o:p></span></p>
  </td>
  <td width="80%" nowrap colspan=3 valign=top style='width:80.0%;border-top:
  none;border-left:none;border-bottom:solid #CCCCCC 1.0pt;border-right:solid #CCCCCC 1.0pt;
  mso-border-top-alt:solid #CCCCCC .75pt;mso-border-left-alt:solid #CCCCCC .75pt;
  mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>3d<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width="100%"
 style='width:100.0%;background:white;border-collapse:collapse;mso-yfti-tbllook:
 1184;mso-padding-alt:0in 0in 0in 0in'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width="20%" valign=top style='width:20.0%;border:solid #CCCCCC 1.0pt;
  mso-border-alt:solid #CCCCCC .75pt;background:#F0F0F0;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><b><span style='mso-fareast-font-family:"Times New Roman"'>Attachments:</span></b><span
  style='mso-fareast-font-family:"Times New Roman"'> <o:p></o:p></span></p>
  </td>
  <td valign=top style='border:solid #CCCCCC 1.0pt;border-left:none;mso-border-left-alt:
  solid #CCCCCC .75pt;mso-border-alt:solid #CCCCCC .75pt;padding:1.5pt 1.5pt 1.5pt 1.5pt'></td>
 </tr>
</table>

<p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<div align=center>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width="100%"
 style='width:100.0%;mso-cellspacing:0in;mso-yfti-tbllook:1184;mso-padding-alt:
 1.5pt 1.5pt 1.5pt 1.5pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width="1%" nowrap style='width:1.0%;background:#BBBBBB;padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='mso-fareast-font-family:"Times New Roman"'>&nbsp;<b><span
  style='color:white'>Description</span></b>&nbsp; <o:p></o:p></span></p>
  </td>
  <td style='padding:1.5pt 1.5pt 1.5pt 1.5pt'>
  <p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'>&nbsp;<o:p></o:p></span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman";
display:none;mso-hide:all'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width="100%"
 style='width:100.0%;mso-cellspacing:0in;mso-yfti-tbllook:1184;mso-padding-alt:
 0in 0in 0in 0in'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td style='border:solid #CCCCCC 1.0pt;mso-border-alt:solid #CCCCCC .75pt;
  padding:1.5pt 1.5pt 1.5pt 1.5pt' id=descriptionArea>
  <p><b>Steps to Reproduce</b></p>
  <ol start=1 type=1>
   <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
       auto;mso-list:l0 level1 lfo1;tab-stops:list .5in'><span
       style='mso-fareast-font-family:"Times New Roman"'>Navigate to opencart.com/login<o:p></o:p></span></li>
   <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
       auto;mso-list:l0 level1 lfo1;tab-stops:list .5in'><span
       style='mso-fareast-font-family:"Times New Roman"'>Use username <span
       class=SpellE>abc</span> with password 123 <o:p></o:p></span></li>
   <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
       auto;mso-list:l0 level1 lfo1;tab-stops:list .5in'><span
       style='mso-fareast-font-family:"Times New Roman"'>Notice that After
       clicking Login button, login it not working<o:p></o:p></span></li>
  </ol>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
  style='mso-fareast-font-family:"Times New Roman"'>Note – Login API is giving
  500 in response<o:p></o:p></span></p>
  <p>Actual Result – After Login user should redirect to homepage</p>
  <p>Expected Result – user is not redirect to homepage</p>
  <p>URL</p>
  <p><span class=SpellE>Stg</span> Environment - stage.opencart.com</p>
  <p>Logs - Error with 500 /login with JSON</p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span style='mso-fareast-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
