<link rel="stylesheet" href="table_hide.css"/>
<div>
   <h2>Details</h2>
   <ul>
      <li>
         <a href="metadata">Metadata about Ground Truth</a>
      </li>
      <li>
         <a href="overview">Detailed table view about regions</a>
      </li>
      <li>
         <a href="overview-level">Level Matrix</a>
      </li>
   </ul>
</div>
<div class="metadata">
   <h2>Metadata</h2>
   <dl class="grid">
      <dt>Name:</dt>
      <dd>gt_structure_text_test</dd>
      <dt>Description:</dt>
      <dd>The OCR-D Ground Truth text and structure corpus was created between 2015 -2017. In the years since 2017, this corpus has been further curated and supplemented with metadata where appropriate. The corpus includes page XML files within annotations of the text and structure include. The data is based on transcription data stored in the German Text Archive (DTA) (https://www.deutschestextarchiv.de/).</dd>
      <dt>Language:</dt>
      <dd>eng, fra, deu, heb, lat</dd>
      <dt>Format:</dt>
      <dd>Page-XML</dd>
      <dt>Time:</dt>
      <dd>1500-1900</dd>
      <dt>GT Type:</dt>
      <dd>data_structure_and_text</dd>
   </dl>
   <details>
      <summary>More Information</summary>
      <dl class="more-grid">
         <dt>Transcription Guidelines:</dt>
         <dd>OCR-D Ground Truth Guidelines https://ocr-d.de/en/gt-guidelines/trans/</dd>
         <dt>License:</dt>
         <dd>CC-BY-SA-4.0</dd>
         <dt>Project:</dt>
         <dd>OCR-D</dd>
         <dt>Project-URL:</dt>
         <dd>https://ocr-d.de/</dd>
      </dl>
   </details>
   <h2>Compressed table view</h2>
   <div>
      <table class="noStyle">
         <tr>
            <td>💡 You can show and hide individual columns of the table.<br/>Click the corresponding button.
                                    <details>
                  <summary>Legend</summary>
                  <dl class="grid">
                     <dt>TextLine</dt>
                     <dd>TextLine</dd>
                     <dt>Page</dt>
                     <dd>Page</dd>
                     <dt>TxtRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lytextregion.html"
                           target="_blank">TextRegion</a>
                     </dd>
                     <dt>ImgRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyBildbereiche.html"
                           target="_blank">ImageRegion</a>
                     </dd>
                     <dt>LineDrawRegion</dt>
                     <dd>LineDrawingRegion</dd>
                     <dt>GraphRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyGraphik.html"
                           target="_blank">GraphicRegion</a>
                     </dd>
                     <dt>TabRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyTabellen.html"
                           target="_blank">TableRegion</a>
                     </dd>
                     <dt>ChartRegion</dt>
                     <dd>ChartRegion</dd>
                     <dt>SepRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lySeparatoren.html"
                           target="_blank">SeperatorRegion</a>
                     </dd>
                     <dt>MathRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyMathematische_Zeichen.html"
                           target="_blank">MathsRegion</a>
                     </dd>
                     <dt>ChemRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyChemische_Symbole.html"
                           target="_blank">ChemRegion</a>
                     </dd>
                     <dt>MusicRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyNotenzeichen.html"
                           target="_blank">MusicRegion</a>
                     </dd>
                     <dt>AdRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyWerbung.html"
                           target="_blank">AdvertRegion</a>
                     </dd>
                     <dt>NoiseRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyRauschen.html"
                           target="_blank">NoiseRegion</a>
                     </dd>
                     <dt>UnknownRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lySonstiges.html"
                           target="_blank">UnknownRegion</a>
                     </dd>
                     <dt>CustomRegion</dt>
                     <dd>CustomRegion</dd>
                  </dl>
               </details>
            </td>
            <td>
               <div class="grid-container">
                  <button onclick="document.getElementById('table_id').classList.toggle('hide2')">
                     <i>TextLine</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide3')">
                     <i>Page</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide4')">
                     <i>TxtRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide5')">
                     <i>ImgRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide6')">
                     <i>LineDrawRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide7')">
                     <i>GraphRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide8')">
                     <i>TabRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide9')">
                     <i>ChartRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide10')">
                     <i>SepRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide11')">
                     <i>MathRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide12')">
                     <i>ChemRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide13')">
                     <i>MusicRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide14')">
                     <i>AdRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide15')">
                     <i>NoiseRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide16')">
                     <i>UnknownRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide17')">
                     <i>CustomRegion</i>
                  </button>
               </div>
            </td>
         </tr>
      </table>
      <table id="table_id" class="display">
         <thead>
            <tr>
               <th>document</th>
               <th>TextLine</th>
               <th>Page</th>
               <th>TxtRegion</th>
               <th>ImgRegion</th>
               <th>LineDrawRegion</th>
               <th>GraphRegion</th>
               <th>TabRegion</th>
               <th>ChartRegion</th>
               <th>SepRegion</th>
               <th>MathRegion</th>
               <th>ChemRegion</th>
               <th>MusicRegion</th>
               <th>AdRegion</th>
               <th>NoiseRegion</th>
               <th>UnknownRegion</th>
               <th>CustomRegion</th>
            </tr>
         </thead>
         <tbody>
            <tr>
               <th>aepinus_bekentnis_1548</th>
               <td>101</td>
               <td>4</td>
               <td>20</td>
               <td>0</td>
               <td>0</td>
               <td>3</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
               <td>0</td>
            </tr>
            <tr>
               <td colspan="17" style="text-align:left !important;">
                  <details>
                     <summary>Overview</summary>
                     <table>
                        <thead>
                           <tr>
                              <th>document</th>
                              <th>TextLine</th>
                              <th>Page</th>
                              <th>TxtRegion</th>
                              <th>ImgRegion</th>
                              <th>LineDrawRegion</th>
                              <th>GraphRegion</th>
                              <th>TabRegion</th>
                              <th>ChartRegion</th>
                              <th>SepRegion</th>
                              <th>MathRegion</th>
                              <th>ChemRegion</th>
                              <th>MusicRegion</th>
                              <th>AdRegion</th>
                              <th>NoiseRegion</th>
                              <th>UnknownRegion</th>
                              <th>CustomRegion</th>
                           </tr>
                        </thead>
                        <tr>
                           <td>
                              <a href="https://github.com/tboenig/gt_structure_text_test/blob/v1.0.8/data/aepinus_bekentnis_1548/GT-PAGE/aepinus_bekentnis_1548_0007.xml">aepinus_bekentnis_1548_0007.xml</a>
                           </td>
                           <td>30</td>
                           <td>1</td>
                           <td>4</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                        </tr>
                        <tr>
                           <td>
                              <a href="https://github.com/tboenig/gt_structure_text_test/blob/v1.0.8/data/aepinus_bekentnis_1548/GT-PAGE/aepinus_bekentnis_1548_0020.xml">aepinus_bekentnis_1548_0020.xml</a>
                           </td>
                           <td>21</td>
                           <td>1</td>
                           <td>4</td>
                           <td>0</td>
                           <td>0</td>
                           <td>1</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                        </tr>
                        <tr>
                           <td>
                              <a href="https://github.com/tboenig/gt_structure_text_test/blob/v1.0.8/data/aepinus_bekentnis_1548/GT-PAGE/aepinus_bekentnis_1548_0006.xml">aepinus_bekentnis_1548_0006.xml</a>
                           </td>
                           <td>18</td>
                           <td>1</td>
                           <td>4</td>
                           <td>0</td>
                           <td>0</td>
                           <td>2</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                        </tr>
                        <tr>
                           <td>
                              <a href="https://github.com/tboenig/gt_structure_text_test/blob/v1.0.8/data/aepinus_bekentnis_1548/GT-PAGE/aepinus_bekentnis_1548_0021.xml">aepinus_bekentnis_1548_0021.xml</a>
                           </td>
                           <td>32</td>
                           <td>1</td>
                           <td>8</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                           <td>0</td>
                        </tr>
                     </table>
                  </details>
               </td>
            </tr>
         </tbody>
      </table>
   </div>
</div>
