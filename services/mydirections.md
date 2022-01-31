# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=Houston&destination=Austin&units=metric&departure_time=now&traffic_model=optimistic&avoid=tolls&waypoints=via%3A28.815644%2C-96.925831%7Cvia%3A29.438893%2C-98.477889%7Cvia%3A29.869429%2C-97.939114&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJAYWNSLS4QIYROwVl894CDco",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJLXrf4StmQoYRcAYNnfXEoAI",
         "types" : [ "route" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJiWIZq_D1XIYRPs_HnLBEnc0",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJK3tba4uoXIYR6ncQDnzPVn8",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJLwPMoJm1RIYRetVp1EtGm10",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 30.2678636,
               "lng" : -95.3698084
            },
            "southwest" : {
               "lat" : 28.8154055,
               "lng" : -98.4934284
            }
         },
         "copyrights" : "Map data ©2022 Google, INEGI",
         "legs" : [
            {
               "distance" : {
                  "text" : "527 km",
                  "value" : 526971
               },
               "duration" : {
                  "text" : "5 hours 25 mins",
                  "value" : 19489
               },
               "duration_in_traffic" : {
                  "text" : "5 hours 0 mins",
                  "value" : 17996
               },
               "end_address" : "Austin, TX, USA",
               "end_location" : {
                  "lat" : 30.2671716,
                  "lng" : -97.74313869999999
               },
               "start_address" : "Houston, TX, USA",
               "start_location" : {
                  "lat" : 29.76043,
                  "lng" : -95.3698084
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "49 m",
                        "value" : 49
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 29.7600631,
                        "lng" : -95.3700879
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e on \u003cb\u003eBagby St\u003c/b\u003e toward \u003cb\u003eMcKinney St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "uqstDh|aeQhAv@"
                     },
                     "start_location" : {
                        "lat" : 29.76043,
                        "lng" : -95.3698084
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 200
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 29.7590492,
                        "lng" : -95.36837199999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMcKinney St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kostD`~aeQf@cAv@wADKn@wAf@cAJS"
                     },
                     "start_location" : {
                        "lat" : 29.7600631,
                        "lng" : -95.3700879
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2311
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 318
                     },
                     "end_location" : {
                        "lat" : 29.7419157,
                        "lng" : -95.38192119999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSmith St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Wells Fargo Bank (on the right in 1.7&nbsp;km)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "aistDhsaeQhBtATPXThAx@fAv@tA~@`@V|AjAzAfA^Z`BhARNHHf@^jA|@dDbCx@l@DBVRBBl@^FHnCnBHFFDXRx@n@DB@@@@JHB@FFB@PN|AdALJj@`@^Xb@ZNL~@r@NLpA`Al@d@fBpA`@XZT`Ap@JFZTPNPNb@Z\\TdAx@hAx@\\VrA~@v@l@h@^DDLJz@n@x@l@XRPLVRbAt@xB~At@j@`@Xv@j@nBvAx@n@D@HFHDBB@@D@FD"
                     },
                     "start_location" : {
                        "lat" : 29.7590492,
                        "lng" : -95.36837199999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1339
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 29.7321858,
                        "lng" : -95.38868859999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSpur 527 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_~otD~gdeQb@@R@R?b@AhA?`@?J?V?^A`@@P?T@b@Bf@Fl@H^Hb@Jt@Rf@Ph@Tn@^ZRXRb@\\d@\\r@f@`@V\\TPRb@X`Ar@HD|CzBLJ@?NLr@`@\\Vx@j@VPBBNJDDFDx@l@j@`@|@p@FDrAdALNJNVZV^NVJVN\\Tn@Ll@Jp@Dl@Jf@FR"
                     },
                     "start_location" : {
                        "lat" : 29.7419157,
                        "lng" : -95.38192119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 3979
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 148
                     },
                     "end_location" : {
                        "lat" : 29.7298118,
                        "lng" : -95.42974439999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-69\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "eantDhreeQFpBFfBBb@Bv@?T@TFdBBh@?@?XF|A@\\@JN|D?F?D@DFhADzAPvE@`@B`@d@tN@X?T@\\@V@hA@d@?^@V?VJ`FBrBBfADjAPxJF`DPjI?zB?h@?h@@f@?`A@`D@pA@hA@p@?hA@|A?L?D?F?J?F?\\?pBDdA@dA?dBB`A?D?@DtA?BDjBD~@DjA@RDhA?@?ZBnD?j@?\\?pA?f@?`B?|@@z@?v@?B?b@@Z?nBB|C?b@?L?b@?vABbG@rC@zADhB@JJbCJ~ABXJrAFr@J`A@JV~CRvBH~@@PB`@BVBR@TFf@Df@Dh@LnA"
                     },
                     "start_location" : {
                        "lat" : 29.7321858,
                        "lng" : -95.38868859999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1829
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 29.730092,
                        "lng" : -95.4485045
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-69\u003c/b\u003e",
                     "polyline" : {
                        "points" : "irmtDzrmeQPbB@@BZD^LxAP`CNfDDlAFtC?V@V?LBhAJ~FFdEH|DD`C@j@?BFhC@V@f@?L?DBdBB`B@jA?F?d@?B?~@An@EnB?J?DC`AAHCp@GdA?B?DEp@A@IfAGv@MpAGf@CVG`@K~@CPOfAIp@GRSzAEZK`AGf@It@M|AAJ?BE^?L"
                     },
                     "start_location" : {
                        "lat" : 29.7298118,
                        "lng" : -95.42974439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.4 km",
                        "value" : 3408
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 128
                     },
                     "end_location" : {
                        "lat" : 29.7259639,
                        "lng" : -95.4829522
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-69\u003c/b\u003e",
                     "polyline" : {
                        "points" : "atmtDbhqeQGr@C\\InBAPAp@A^Cn@A`@?@?f@AR?~@?l@?`@?@?h@@j@BxK@h@?R@fCH^@RBp@HlCFdAJpARzBTjBNv@V~ALd@Ld@BJ?@HVZjA@B?B@@Pp@@@Ld@@@@D?@Nd@Pn@@B?@@@h@jBHV@BHX?@FP^lAl@vB`@vAl@jBJ\\Ld@HVn@zBJh@H^@FHp@D\\X`AVfAFZLr@TtANhAD\\RtBXjEHzDBpA@v@@ZLjI@^?FBdD?D@`@?h@DdDBzB?H?^?pA?h@?pA?@?f@?v@?r@@z@?`A?zB?\\@dA?V?\\?hG?dD@dD@xA"
                     },
                     "start_location" : {
                        "lat" : 29.730092,
                        "lng" : -95.4485045
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "44.3 km",
                        "value" : 44340
                     },
                     "duration" : {
                        "text" : "25 mins",
                        "value" : 1484
                     },
                     "end_location" : {
                        "lat" : 29.53454529999999,
                        "lng" : -95.85663489999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-69\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gzltDl_xeQ?nB@h@?pA@pA?j@?bD?L?x@@zA?l@Bh@@d@Bb@Fx@B^Db@Jl@DXF\\DRPr@`@rATl@@@?@Vp@JR?@?@NZl@dARb@hAxAFHj@n@\\b@FFBBFHFF@@NRBBBBNPt@z@l@x@VZ`@`@\\`@r@x@v@z@LJhAvALPHJdBpB?@r@x@`AjAd@j@p@t@p@x@XZ~@hAh@l@@@jApA?@XZZ\\TZZ^h@n@FDp@x@@@@@TV@@?@p@t@j@p@?@@?RVNPDD@@HHb@h@B@?@@@VZXZhCvCp@x@jAvAxClDpFnG~CtDhBtBzDrEp@x@hBxBtBbClEfFn@x@FFdG|Gb@h@FLBL@?TVjEfFfApAx@~@DDX\\@?JLLPHFNRr@x@p@x@xClDz@bAh@n@PRtA~AxEtFJHFF\\`@JLHJFFFHPTDBPTf@j@DH`AhAHJ|@dAFJBBt@v@bAhAlAtAxAbBn@v@~E|FpAxAtChD`ExEb@h@|AfB`@h@dBtBj@r@\\b@p@v@@@@BZ\\?@RTBBBBNR?@@?DFz@`A`@b@t@t@d@b@d@b@?@NL`BtAj@d@fAx@@@dAv@`CbBfAv@@?RNXR?@\\TFDz@n@jCjBtBtArBzA@@\\VfGnEj@`@lDhCr@h@\\VZVVR@@p@j@^\\b@b@TTB@TXB@VV@BpAtAFHJJLNLLj@p@nBvBXZbClCnAtApEbFHL|CbDt@x@z@~@b@f@ZZBBNPBBXZ@@DDVZHFJLZZzAbBlArAX\\XZX\\XZXZfBrB`GpGdAjAb@f@vAzA?@BB@@FHdAhAFFlEzElJfK\\Xh@n@v@z@hEtE`ChCLNxCdDXZdF|F@@`@d@@@@@@@b@d@@@p@v@r@x@r@v@RRr@r@b@f@DDFFBDDD@@@@NN`@d@DBLNVV@BPPFHRRBBVV?@DDNPdAhADFlArAn@p@x@~@NNVZDDx@~@pD~DrE~EdAjA`@d@bBhBHJJHZZfAnANNLNBBHJjAlAjAtADF?@@?~AfBfHbI~@bAZ\\LLHJ@@@@JJBDDBJJFH@@@BNNDDb@d@hBpBf@j@pCzC^XbAfArAzAnArAZZj@n@rEbFh@l@r@v@XZhBpBJLZZfBnBXZhBpBJJ@BNL?@TVDDBBJJBDd@f@hBpBFFhEvEFH`BfBnAtAXZTT|BfCnBvBl@p@j@l@JL@@XZBBFFFH@?BFJL|@`AVZ`ClCxDdElApAlHbIXZVX`ChCjBtBjFzFh@j@|BhC~BhCnD|DPRpAvAv@z@v@z@Z^\\^vA|AtAzAVVVXfEtEtAxAxC`Dp@x@X\\X\\b@h@hAbBLRn@~@HN^n@Tb@h@`A~@bBtAdCR^T`@nB`Dj@v@PVPTLN^f@dApA`BdBXX`BzAt@l@jA`An@`@pBlA|C`BLFpAn@hCrAj@XfB`ArBhAvCpBpCtBZVtB`BfFxDfBvAnA~@RPLJjDvCBBb@`@?@XZNPpAnAzExEhBlBTVBBHHFHHFJJTVl@l@l@n@p@p@`AbAx@x@dBfBDDdBfBbAbA~HhIdBfBVVh@l@TTTThCnCdAdAJJhBlBpApAdChCf@f@VVd@d@FDPRFFZXTVz@x@r@v@t@t@d@d@d@d@zBfCDFxBjCpAdBj@t@JLdAzA|AbCj@|@T^zA~BjBbD~AxCdBbD`@v@|ArCd@z@f@bAbAlBt@vAjAvB?@DFHPT^BD@BJR@BjBbD|BhEtAbCrAdCVf@nCbFtAdC@DP\\~@`BBDx@vADHT`@pA~BVf@`D~FFLT^rAdCdCrEt@rA^p@T`@R`@fBlDf@~@PZT`@PZBD@BJPzAnCrAdCbAdBhAtBNZl@fAT`@Vf@pA~B^r@rBtDdEvHj@dArBvDfLzSR`@~@bBd@z@NXzAnClBlDnA~BbCpErAdCl@hAtAdCLVh@`AtAdC@@@B@Bv@xAdAlBDHNVfBfDT`@bAnBv@vA`@t@`AhBFNbAtBt@fBr@fB\\`AZ`Aj@hBRp@Rp@V~@ZtAF^Nx@R`AV|A?@Jr@J~@d@tDFf@Hf@v@xGFh@@F~@xH`BbNn@nFX~BD^NrAz@`IL`AP`BBV@@Df@?@?@Fb@PvABPLfAJv@BND\\Fl@r@zFLdAVxBL|@NrAFd@Fd@D\\Jv@j@`EJ~@ZpCh@dEHj@l@pFj@dERvA@Hl@bFJdAx@jGTzBRnA`@fDhB`Od@~D`AhInApKx@zG~@`IDd@@@Dd@X~BPvAPvAlBrOp@pF|@nHpAbKp@pFj@jEf@~D^`Dd@hD`@~BN~@\\rBTjALp@BJDPJd@d@rBPz@pCbKNd@J`@j@hBpAbE`@rAt@dCr@zBv@bCNb@jBdGBHBFBF@FDFBLFLpBdGb@xABDHXDPFR\\`ADPFPFNFPTr@DNp@pB|CdJFTFN@BL`@\\~@`@pAtBpG|AvEh@nAt@zBl@hB@@Nb@?@^dA?@xBjHtAbFhA`E`@nAj@~Al@~A@D?@@@DLdDrKj@fB`DnJl@fBRh@p@jBv@zBPb@x@hCnHbVNb@j@lB^bAxEnORn@t@hCBFPl@FRRt@@BJ`@BDXlAHZv@xCBL\\~AXrAPx@@FLl@@B@JFZ?@BJLr@VxAFVRvAHf@BNHt@Jv@RxAPzAD\\Hv@BXDf@Fb@Fn@BZNfBF`AJrAJ|@Fx@J~CDhADdAFzBDxBFhDBzC@bA@h@?R@hABhBB~BBbCB`CB|BDlDDvDr@bo@@rA?LLhIDlC@~B@l@BzBHvF?h@@T@~@@tBBrA@b@?@BnBFdDNhIH`FFhD@|CH`MHjN?X?V@|BBhFBvCCzBAp@GjBCpAAd@ARARKpBEr@CXALAVYnEIpA?DC`@Gt@MzBEr@AV?DIpA?BCb@UbDARAREh@O`CC`@Ef@w@`M?@?D]tFKvAKjBSvCUrD?BQ|Cs@dLMrBGpAa@vGw@tL]fFAVEn@IpASjDMjBCh@ADQ|CAXe@jHEjBC`A?nAA|@BzA?z@JxCVvCTrBf@|Cp@pD"
                     },
                     "start_location" : {
                        "lat" : 29.7259639,
                        "lng" : -95.4829522
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "133 km",
                        "value" : 133278
                     },
                     "duration" : {
                        "text" : "1 hour 10 mins",
                        "value" : 4178
                     },
                     "end_location" : {
                        "lat" : 28.8425798,
                        "lng" : -96.90198269999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eUS-59 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}mgsD|~`hQ|@~Cf@~Ad@hAXn@^|@\\r@d@`AT`@@DNV@BNXLRBFDFVj@FLJPNXr@tAnBxDDFv@|AjBpDpDvGnEvIfAjBN\\h@`AxHzN|CzFnGpLh@bAlAvBP\\fBlDlD`HbC`FpLlUhEdIzBfEnC`FdAtBzF|KzArCrDbH\\r@f@~@n@nA|@dB`BzChC`FvAdCnBrDR`@T^T`@R`@~AxC\\n@HNd@z@Xh@~@fBxAzC^r@x@~Aj@dAPZJRT`@R^LPLRLPLRNRNTHLNR\\b@\\d@NNNPNP^b@NNNNPNHHj@h@^ZPNFFHFNLHFNJ\\VPLNJTNVPVNVNj@ZPJZPj@XbF~B\\Pb@R`@RZLb@TDBHBXNp@Z@@PHJDRJLDvAr@pB`AdAf@bBz@l@\\r@`@JFj@\\jAv@`BjAh@b@TPB@f@`@NNXVZVTRf@d@RTFF\\\\j@l@VXb@d@X\\PTNRDFPRFHd@p@r@~@Zf@`@l@R^V`@T`@PZR\\JTR`@Xh@Tf@\\v@Tf@BHLXJXN^Vr@Pd@Nb@Rj@Vx@DNNd@FT`@|AjAhEl@~Bh@lB|@fDrAfFnArEp@jC^tAz@bD\\jAj@xBj@tBp@bC`AtDd@dBXbARx@L`@HZf@hBNl@`@xAn@`C^vAV`ATv@f@jB\\pAb@~Ad@hBd@bB\\nAFXh@nBDL`@xAHZd@fBl@zBJ`@DRRt@V|@n@bCJ\\J\\n@bCTx@Ld@J\\V|@X~@dAnCb@fAr@hBRd@FPZt@f@jAtApCvApCXj@z@dB|@dBR`@hGxLf@bAfC`FtC|F|A`DfFtJJR`DlGtFvKp@tAdCzEr`@rv@NXNX~O`[hC`FTd@R^Vh@Zp@\\p@rAzBbAjB`AjBt@`B|A~B|AhClBxChAhBvAtBfFrH|BdDrH|Kb@l@FHfHdKbBdCd@v@dGvJtBpDbBtCbCtEXj@bBfD@Br@|Ab@~@n@rAn@pAh@hABHd@`ANZj@rAr@bBVj@^|@v@jBvApDfAnCNb@hBtE\\z@DLRh@N^~AdEPb@xB|FvArDNb@|DdK|@zBhH`R~@`ChAxCP`@`@~@b@bAj@nAh@jA`@x@`@v@jBnDRb@dBfDzGjMpAdCzBlEnClFVb@d@`ApCjFpAfCvBfEdBdDzDrHh@fAnG|LnClFT`@|Sla@p@rAjQb]^r@jVje@hCbF|@fBLTJRf@|@hDtGN\\r@rAb@z@dBfDHNlBpD^v@t@pApArB~@nAx@jAn@bA`@r@`BbD`AhBhDvGtB`EnChFb@x@lChF`AhB^l@h@x@\\d@`@h@h@n@z@|@\\Zf@b@d@^b@Z`@Xd@ZNHb@V~@f@rAr@bWvMrHzDlGdDlDlBlCxA~BfAdFlCd@R|@d@zDtBxBhA^Pp@^tFvCt@\\d@Vn@ZpDnBfAl@r@^p@\\jDhBxDlBtAr@jFpC`DfBdAn@zAr@rAr@vAp@|C~Av@`@j@Xz@b@vAf@t@Xl@R~@ZfA`@~Bt@tGhBvBn@pDfAvDlA~C~@vAd@z@TzBp@bD~@~@Xf@Rj@RLHf@RTLd@Td@XdAv@f@\\b@\\p@j@b@b@r@n@\\`@NPLN^f@Xb@LN@BJPjAjBvA~Bv@pAh@z@^p@lAnBvBjDFJ~@~A|@tAlB`D`A`Bj@hApBvCxA~Bd@v@bAbBt@jAvBpDlB|CpB`DjAlBbAbBpEnHvBjDlAnBrDdGxNzU~AjCf@z@zBrDh@x@j@x@\\b@\\d@NP^`@NNHHDD?@`@^PNTRFFTPPLb@ZRNPLPJPLd@Vf@Vd@VRHRHz@^|@XtCz@jTjGrLfDpDdAtd@rMlLfDh@N|Bn@~@Xv@RxCz@hD~@xDhApCv@XH`Bd@lBl@~@V^LpA^~C~@vAb@l@RvBn@pA^pA^pBj@LBdAXbBd@pGdBTFtCv@`@J~Bn@jCt@tCx@hAXpBb@l@Hj@J~@NVDd@FVB~@JvALjBL|ALnAJnJv@dFZlDVvE^rOhAxALhBL`DVlAJlBRlAPvB^nAVrAZnAZvFvApLvCjBd@VFvGbBv]zIrD|@xGbBbOtDn@RbG|A`@JnBd@jItBr@LlFrAfBd@tA\\f@PTFd@PTHRHRHd@TPJTJ\\PXRPLPLRLNLPNJHDDZXZXTV^`@X^RVNRLRn@bAfCvEpAbC@@bFrJn@pApCnFfBzCfCzE`JzPR`@nDzGrB|DxXjh@zCvFdDlGbDhGdJ|PhAtBpFjKdAjB|@dBxM|VlRd^hDlGjBnDbIfOnHhNxCxFTd@l@jAjBhDR`@tCnFpBxDx@`Bl@zAl@`Br@xBXhAPt@VnAVxALx@ZhCNpBHnA@TBz@F`D@bABbBBnAD~@F`AFz@LpATzANv@Pz@TdATz@Tr@Tp@BDb@lA^|@^r@l@fAb@n@h@x@zC`ExBvCZb@f@l@j@n@f@f@v@p@r@h@x@h@j@Zz@`@~@`@dCz@`Bh@|CdAxAh@|@`@r@\\l@\\r@f@`At@r@n@~@dA`@h@b@n@^h@Xf@t@tA|EdJlBrDpElIpFbKvB`EjIrOf@bAT^bCrEtB`EvI`Pb@|@d@|@`ArBp@bB^~@^dA`AxC~BrHDLdFhPdAfDnBjGr@xBh@vAz@jB`@t@j@|@|@jAj@n@DDRTJHp@l@r@l@~@j@`@VXNNHh@T^PnAd@~@\\hC|@@@dC|@`@N^NXJPFVJRHl@T`@NLFn@T@@FBfA`@b@PXJRHxBx@n@VFBFB~DzAxCfAdUrIbBn@dBn@|@\\|@ZHDzAj@xChAj@Rl@Rf@Ph@Pf@NVFRDTFTDh@Jh@Hj@HTDTBTBTBj@Fh@Bl@Dv@Bl@@Z?l@AnBA`CClIG`@?zCCdAAtAC~@A~@A|@Ah@?h@?h@@T@R@VBP@TBR@TDR@TD^FZF|@PVHhAZ~@Xf@Rf@Rf@Rf@Vd@Vd@Vd@Zb@XPNPLPL`@^b@^TRHJpArAf@j@VXn@p@~@bA`AdAlCrCPThAjAj@n@~DhElBtB~@bAn@p@hDpDPRn@p@~@bAZ\\fAjA^b@X\\BBRXJJ\\d@Zd@Xd@Zf@Xh@BFXj@d@fARf@Xx@BHLd@@?FTJ\\Jb@Ld@Nt@Lv@BJN|@BJNfAd@tCJv@BJDZHd@n@fEHd@v@~Ed@|Cn@dE^|BLx@RxAp@dE|@vFTzAVbBTlBJ~@JfAH`AHhAF~@HxB@VDbB@fA@z@?RF|I?ZBpD@bB?hABbD@bD?J?f@?Z?X@pC@h@BtF@pBBzB@pA@dD@`AB|D?X@|BBzD@vEB~C@xA@fD@xB@f@?d@BfD@~ABzBB`A@n@F`CDbBNfFBnABr@H|CBnADrAL~EB`ADbBBnA@f@?@HpDHbCDvABfAJlDB|@DdAFrADv@Fr@Jp@D^Lv@Nr@H^Lh@Nf@L`@Pd@Nb@Rd@Tf@R`@Xh@Vb@\\j@X`@PT\\b@TVb@b@TTVVTRb@\\j@d@t@h@tAhAv@l@B@v@p@ZXf@d@r@v@d@f@VZ\\f@\\b@`@n@Vb@j@`ADFdClEtBzDx@zAlBpDtPj[DFj@fAjAvBt@tA^p@R^Vh@vFhK`AdBdBbD`ChEtFhJdAdBx@tAb@v@tAhCfArBhArBhAtBrLtThAvBvAtCTf@l@zAZ~@ZdAPl@Jj@Jf@H^DXFXBTDXDVDVBVFr@D`@Bh@BV@V@V@VBn@FhABbADv@Dr@Dr@Fp@Ft@BVDZBPD^Jp@Pz@BPT`APn@Nj@Pl@FNDLFPFJN`@DLFNRd@DHDJVh@Vd@P\\`AhBxBbE`AfBf@|@l@fALRNRVb@JPLNPVNPVZTXNPPRJJJHJLFFPNf@d@j@b@XTRLPLd@XNJPLh@Xd@Tf@TZNj@TvAn@x@\\`Bx@x@f@t@f@j@`@l@f@b@^n@n@^`@NP\\b@\\b@Zd@\\f@l@bAz@tAr@pAbBbDpIvOh@nA|BfER`@xJvQhCzE\\n@lBnDPZXh@fCxEfArBvB~D^p@hAvBr@pAp@nAr@nAxAnCpBtD|DnHpDzG~DpHTb@~@fB~BjEfHvMl@fAl@hAZj@j@bAx@zAp@pAn@lA^x@LZXr@\\~@X|@Pn@T~@Np@DTF\\Jj@NdAD^Db@Dj@H~@Bd@@X@h@@j@@b@?d@?n@An@A`@AZ?JAL?JAVCr@Cz@MzDg@vOKhDIbBE~ACv@Ap@AdA@lA@p@@r@Dl@Bp@Dr@Fl@DXDb@Fd@DVDVBPFZFXH`@H`@FVNp@Vz@J\\L^Nb@Rd@FPFLJVR`@JTb@|@d@|@Xh@Vf@Xf@jA|B`@z@V`@T`@xB|DzCtFjE~HjBhDbL`TbCtExB~DT`@Xf@T^Xd@d@p@\\d@^`@TXPRNNPPxArAtAbATNx@h@b@TZN^RNFTJ^N`@Nh@R`A\\j@P~FpBxDpAtItCn@TfJ~Cz@XfA^fBl@fCz@dA`@r@Vv@\\t@^^RZTp@d@b@\\z@v@^`@VV^b@f@r@FHT^V`@R\\JPxAjCjAvBlBrDj@dANVxAnCpA`C|BhE~EdJl@fA`CnET`@h@bApElIj@fAhDnGjGhLP\\dB~ChM|Uf@~@rGzLdAnBDH`G|KpBtDR`@pF`KxApCtLxTnItO`B|CjC~E~BjEdAnBnGrLnCdFz@zAp@lAn@jAhDlGbB~CT`@n@lAxLzTv@vA`@t@vFhKjC`FbB~CrU~b@lAzBPZhRx]n@lAdB~CnLnTXh@~@fB`AdBx@~Av@dBd@fAL`@Pb@BHJZRl@Pl@Rr@^dBPx@DNTjAXdBPpANnALpAJbANnBF`A@f@B^?FDvADrA?\\@pA?dA?N?h@Ap@A`B?NAz@?|@C`CA~@BtABt@BbADx@FhAH`ADp@Hl@Hl@Hn@PlArBhLp@xDRdARfAv@fETdADNX`AVx@Lb@\\z@j@rA`@t@LTBDb@v@Zd@Zb@`ArAnA`BnBfCpDzEzAnBnA`BdCdDjChDnA~AdCbDd@l@jDrEV\\Z`@hCfDhB|BRXlClDv@`Av@dA|@hAvCzDFFzCdE|@jAV\\jDpEjA~ATZrCrD|IjLjA|A\\d@t@bApApBx@xALRb@z@f@`A^z@j@pAp@`BL^Pb@Pj@`@nA~@pCv@dCp@rB|AzEn@pBlCjIl@nB^hAjE~MNd@tC|IdC|Hn@lB`@hARh@n@dB\\`AbAbCz@rBjArC|@xBnHnQhBpEzAlDxChH`D|HPd@Nb@Pb@\\bAdB~ElAjDdBnExBnF~BtFLZdAdCRd@xBjFb@fAf@lALXpB|E`A|B|HhRpFrMhBlEr@jBh@vA@@n@lBZ|@\\dAtBpGnAtDn@lBr@nBl@vA`@bAjAtCv@jBTh@Vn@d@fApBzErA`D|@xBPb@zAnD^~@`@|@fAlCPb@b@dA~BxFxChHv@jB?@jApCv@jBl@pAz@hB`BdDdB`D^r@T`@FLr@rAz@dBb@|@Vj@JR`@|@`@`Ab@`A^|@Tj@Zt@DJv@jBTh@FNLZzDjJjBpEPb@\\v@lBtE^~@v@lBh@rATl@\\~@d@xAHVRl@FRHVFTHVPl@Pp@FTT~@Rz@BHFZJf@@BH`@BJFZJd@@FFVJn@DVHf@FZDZNdAPfADVP~AHr@H|@J|@HdAL~ADt@@T@VFlAF~ADjABbB@J?`@@p@?r@@n@?r@AhAAhAAp@Ap@Ar@KrCIdBo@rMOlDEn@EhACjAClAAfA?r@?l@?X@bB@r@@R@Z?D@d@B^Bj@@\\FdAJbBH~@@JJfAHr@Hl@LhANbADVFZJl@Jl@Lp@TdAVbAVfAPn@FTHTFTFTHVPj@Pf@L`@~B`H~@pC`FbO`@hALb@Pd@nAvDh@zAf@zAxKf\\Xx@Vt@Rl@Z|@f@xAf@xA^`AJTRf@p@tARb@\\n@f@x@f@x@j@v@^h@X^NPh@n@RT`@`@PRNLNNRPn@j@p@j@f@\\JHTNd@ZtA|@rBrAbJtFvFhDrD|BdAl@nBjAzBtAxBrALHfDrB|BvA@@nBlAf@Zr@b@@@v@f@zA|@fAp@f@ZnBnAz@l@XR|@r@TRl@f@hAdAx@x@~@`AnAvApA`BnAdBHLl@~@p@fAV`@dAjBPZRd@Zp@^v@`@~@j@tAVj@\\|@HLPb@Pb@v@jBf@lAd@hATn@^jAVdAFVFRDRDTFZDXDVF^@JBVDXBXB\\D`@Dx@DdAHbCL`DD`AL|D@f@f@bN?FJ|BDx@@RD`@JjAFj@F^NdAXzATbAPp@Tt@Rn@BH^bAlAtCbA`CvAhD@BPb@z@nBvAhDpCvGx@fBd@|@r@lAd@v@`@j@h@v@fAtAnAzAjAxA`EbF`AjAfC|CnDlEfDbEn@v@|@dAjB~BX\\nDlEX\\hAvAfAxAb@n@h@x@f@z@Zf@p@nA@Bb@z@d@~@j@rAvFvMbB~Dd@hAhBhEpBxEbB~DZv@pA|CnBtEpA|Cv@hBb@bARd@Tl@Zz@b@nARp@d@|Ar@fCp@zBj@dB\\~@jAvCh@pAb@`AxBhFd@jAtDzIPb@P`@v@hBv@hBPb@lBrEj@rAl@tAfAjCd@fAP`@rCzGP`@dC`GhAhCrKdW^~@~BtFxE~KhAlCn@zAb@|@P\\j@fAd@|@NTR`@zA|Br@dAt@hA\\h@f@x@Zf@d@x@d@~@Vh@`@z@b@~@`@`Aj@rA`A~B|IzS^|@R`@Pb@dC~F~Sfg@h@pA`BzDnAxCrCxGpDrIf@lAx@hB`AxB~AxDjApCrAbD^z@d@fApA~CbA`CFLtAfD\\x@@B^bA^dANh@Rj@XdAPl@`@|ATbA`@|ANn@Pl@TbAPp@VbANn@Rr@R~@|D|O\\rAH\\f@nB?@ZjADNTz@J`@X~@\\dAh@xA^`A@D\\x@^|@\\x@^z@^|@tA`DdD|HPb@v@fB`CvFvD~Iz@vBPb@Tn@\\~@h@xAp@lBb@xAbAbDpCnJp@|BbJxZb@vArHdWr@~BjA|DnBtGv@lCn@rBl@lBVv@@@f@pAN\\Tb@h@dAZj@f@t@x@fAn@x@HH^h@~AnBl@v@hY|]fDbEzBpC|BtCfBxBtAbB`AlA^d@b@n@b@p@Vd@Zj@j@jAd@fA\\x@LVd@jAlApCpCtGhChGf@lAlApClArCtAdD|DjJ|@rBtAbDxHvQrGnOnH~P~AzDrA|Cf@jAbFrLt@hBjAlCtC~GHRxBfFrEpKn@|AfAfClG`On@xAfAhCRf@^|@jEbKv@jB|@tBzG~O`AzBl@rAVj@l@jAf@~@|@bBn@nAPZl@lA\\p@\\t@l@tAj@tA`@`Al@tAj@tAl@rAt@hBl@tAbA`CbA`Ch@pAz@pBf@jArJbUNZ?BlBnEf@vAr@jBl@lBVx@Rr@ZdAl@rBd@bBNd@XbAn@tBf@bB^tADLRr@Vz@Vr@Vr@Vp@Tj@Td@@BP\\DJb@v@@BZf@d@r@X`@VZl@t@VXTV`@`@^\\r@j@^XVRv@j@FD\\VLHhAx@PLh@`@b@ZFDfAv@`Ap@vAdAx@j@\\V^Vx@l@z@l@nE`D~@x@pAdAdAx@"
                     },
                     "start_location" : {
                        "lat" : 29.53454529999999,
                        "lng" : -95.85663489999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2813
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 159
                     },
                     "end_location" : {
                        "lat" : 28.8229526,
                        "lng" : -96.92016459999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "ci`oDjdmnQ~@fAp@b@`LlIpE`Dl@h@hAdAbIjHhEdEpBrB`BxAjC`CNLnE~DlG~FRRtDfDhFzErJdJrFpFr@p@jG|FrBpB|CzCl@h@"
                     },
                     "start_location" : {
                        "lat" : 28.8425798,
                        "lng" : -96.90198269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 167
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 28.8216635,
                        "lng" : -96.9210489
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue toward \u003cb\u003eUS-59 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "mn|nD~upnQ`BdA`BfA|@b@"
                     },
                     "start_location" : {
                        "lat" : 28.8229526,
                        "lng" : -96.92016459999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 337
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 28.8193375,
                        "lng" : -96.9232605
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eUS-59 S\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "kf|nDp{pnQRPdGvFtDnD"
                     },
                     "start_location" : {
                        "lat" : 28.8216635,
                        "lng" : -96.9210489
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 495
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 28.8163603,
                        "lng" : -96.9269264
                     },
                     "html_instructions" : "Take the exit toward \u003cb\u003eTX-463Loop\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBurroughsville Rd\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{w{nDjiqnQJR@BBDBBDHJL|@`AhApAn@p@BDX\\v@`AFHFJDJBFBDFPFPFXDXHh@v@p@lC`CPP"
                     },
                     "start_location" : {
                        "lat" : 28.8193375,
                        "lng" : -96.9232605
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "67 m",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 28.8158924,
                        "lng" : -96.9273549
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ge{nDh`rnQ|ArA"
                     },
                     "start_location" : {
                        "lat" : 28.8163603,
                        "lng" : -96.9269264
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 28.8149839,
                        "lng" : -96.92625369999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eZac Lentz Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ib{nD|brnQl@w@V[Xa@@ATY|@iA"
                     },
                     "start_location" : {
                        "lat" : 28.8158924,
                        "lng" : -96.9273549
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 262
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 28.8167833,
                        "lng" : -96.92451079999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eFrontage Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s|znD`|qnQuAoAqGkG"
                     },
                     "start_location" : {
                        "lat" : 28.8149839,
                        "lng" : -96.92625369999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2645
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 107
                     },
                     "end_location" : {
                        "lat" : 28.8352837,
                        "lng" : -96.90747520000001
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "{g{nDdqqnQkB_B]a@eA}@k@]]U{BuAiCaBgAy@MKeA_Aa@]{@u@u@s@}CuCe@c@oLyKg@e@sByBoLmKoDeDwEoEmFcFIGmHaH{BuBeBcBiAeA{EgEmDeD"
                     },
                     "start_location" : {
                        "lat" : 28.8167833,
                        "lng" : -96.92451079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "68 m",
                        "value" : 68
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 77
                     },
                     "end_location" : {
                        "lat" : 28.8356372,
                        "lng" : -96.9080496
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eCounty Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o{~nDvfnnQ[h@Wd@S`@"
                     },
                     "start_location" : {
                        "lat" : 28.8352837,
                        "lng" : -96.90747520000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1839
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 94
                     },
                     "end_location" : {
                        "lat" : 28.8229526,
                        "lng" : -96.92016459999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w}~nDhjnnQpBrB`BxAjC`CNLnE~DlG~FRRtDfDhFzErJdJrFpFr@p@jG|FrBpB|CzCl@h@"
                     },
                     "start_location" : {
                        "lat" : 28.8356372,
                        "lng" : -96.9080496
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 167
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 28.8216635,
                        "lng" : -96.9210489
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue toward \u003cb\u003eUS-59 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "mn|nD~upnQ`BdA`BfA|@b@"
                     },
                     "start_location" : {
                        "lat" : 28.8229526,
                        "lng" : -96.92016459999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 337
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 28.8193375,
                        "lng" : -96.9232605
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eUS-59 S\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "kf|nDp{pnQRPdGvFtDnD"
                     },
                     "start_location" : {
                        "lat" : 28.8216635,
                        "lng" : -96.9210489
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 495
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 28.8163603,
                        "lng" : -96.9269264
                     },
                     "html_instructions" : "Take the exit toward \u003cb\u003eTX-463Loop\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBurroughsville Rd\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{w{nDjiqnQJR@BBDBBDHJL|@`AhApAn@p@BDX\\v@`AFHFJDJBFBDFPFPFXDXHh@v@p@lC`CPP"
                     },
                     "start_location" : {
                        "lat" : 28.8193375,
                        "lng" : -96.9232605
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.6 km",
                        "value" : 10565
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 375
                     },
                     "end_location" : {
                        "lat" : 28.8625698,
                        "lng" : -97.0132141
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTX-463 Loop\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eZac Lentz Pkwy\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Zac Lentz Pkwy\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ge{nDh`rnQJ`@DLBL@L@L?H?JCLGp@cArA}BxCiDjEW\\q@z@i@r@s@|@u@bAk@r@m@t@GFy@bAs@x@s@z@c@h@m@r@w@|@YZoAtAEFUV{BfCA@CBeBjBaCjCA?uA~AeAhAYZCBcBlBmArAw@z@YZSTYXWXqBzBo@p@o@r@eDrDIHSTKJiDvD}BfC{ChDOHKHSTk@j@e@h@STKJaAbAw@x@o@r@g@j@k@n@OPUV]`@o@r@]^ST{@`Aq@r@m@p@q@v@qAtA_BfB}@bAw@z@UVo@r@q@t@}@bAQPGHgAlA_@`@Y\\e@f@}AdBs@t@m@p@y@~@e@f@aAdAu@|@UTu@x@k@n@q@t@mArA_AbAONq@t@[\\a@d@k@n@aAfAm@t@[\\aAjA{@dAc@h@k@r@OPyAlBiB`C{@hAkA|AmA`Bg@n@sD~E}ArB}C`EsD~EiAzA]b@]d@GHW\\W\\QT]d@m@v@i@t@ILc@n@a@j@ILW\\_@h@gA|Ai@r@c@j@W\\MPIJq@`Ao@v@k@v@i@p@OTo@z@Y\\A@UZe@l@ILmA|AeAtACBSXY\\W\\UXABY\\W\\a@j@MNo@z@A?gAxAo@|@Y\\ORiB`Ci@t@m@x@[`@]d@i@r@QR_@f@o@z@W\\c@j@MPo@z@qCrDW\\aBxBg@p@i@l@k@t@[b@]d@W`@CF[f@c@x@Yj@Wl@Uh@Uj@Sl@GPIX[bAQr@Mj@On@Kj@Kr@EXG`@Gf@CNC^Gn@?@En@Ep@ATAXA`@Ad@?^An@@X?T@lAD~A?J@f@@h@?DHfDDxBBhADnABzABfA@ZDzBB|A@\\@T?P@\\@b@HbDDvBRxI?R@h@@J?P@n@@FN~G@f@NrG?JF|C?DDpABtA@b@@h@HnCDzBH|D@f@@h@BlA@j@@T?PB~@Bz@?N@\\?B@^?PHzCBpAF|CF~BHlE@f@@X?NBb@Br@Bx@F`AB^@PBVDj@Df@Db@"
                     },
                     "start_location" : {
                        "lat" : 28.8163603,
                        "lng" : -96.9269264
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 432
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 28.8615878,
                        "lng" : -97.01747669999999
                     },
                     "html_instructions" : "Take the \u003cb\u003eBriggs Blvd\u003c/b\u003e exit toward \u003cb\u003eNursery Dr\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "afdoDp{boQAl@Bd@Df@@NFv@Hn@B\\TfBDXBPf@rC\\dBTbA^nAF`@"
                     },
                     "start_location" : {
                        "lat" : 28.8625698,
                        "lng" : -97.0132141
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 957
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 28.8576731,
                        "lng" : -97.0262176
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eU.S. 77 Frontage Rd\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "}_doDfvcoQ\\`Ax@`C|@jCx@vB`@|AzA~EnDbLLb@n@hBb@lAFPj@pAj@tA\\t@Th@Zr@"
                     },
                     "start_location" : {
                        "lat" : 28.8615878,
                        "lng" : -97.01747669999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "38.1 km",
                        "value" : 38128
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1342
                     },
                     "end_location" : {
                        "lat" : 29.0938184,
                        "lng" : -97.29000449999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eUS-87 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mgcoDzleoQk@n@gAlAgApAWj@k@n@gAnAuEhF_@b@oD~DaEtEQR}DlE}CjDq@t@mAtA_CjCwHtIyBdCuA~AiCvCmE`F}BhCkGfHiBrBsHpImCzCyAbBaBjBeCpCYZSV_@`@YZqDbEiBtBsC`DeCpCwBdCsB~Bs@x@cBjB{DlE}FtGY\\eG~GoD`EkE`FmKtL}AdBqBzBY\\m@p@yBbCaAjA_BdBwBdC{AdBcAhA{AdBqBzB_BhBsFjGY\\}CjDaFvFgCtCwA~AoB|BwBbCoJrKcBlBaDlDwAzAsArA}@|@UTuBzBgEzEaAhAkGdHeIfJqC`DyJ|KgEzEuA|AWXA@aFzFqD`Ec@f@sDdEm@r@o@t@i@n@UZY^MRORSXU\\MRQV]l@[h@s@lAGLQ\\OZCBw@lBWPSb@KT}AbDqAzBqArBKLw@fAs@z@qAvAmAnAeA`Ay@r@URURg@h@AB_@ZCBq@l@s@p@q@l@ON}@z@oAjAcD~CA@[X{BtBiC`CeC|BaGpFqAlAwDjDGFmG|FeDzCsAlAiAfAeC|B]XmBhBsNtMiAbAuSnRwApAqBjB[XaEvDiC`CcKlJmD`DiAdAyFjF[XgEzDsJ~IqAlAaBzAgExDwBrBgB~AaA|@_@\\yAtAs@n@s@p@o@j@ED]Z_@\\MLuAnAw@r@q@n@_@ZQPmCdCoCfCA@yArAaA|@gB`Bk@h@[XYXgB`B_Az@GFSPk@h@s@n@URa@\\QNeA|@k@d@EDUP]XA?u@l@cAv@[V{@n@[VsB~A]Vy@p@sB~AoDnC[VqCxBkA|@kA|@yAjAiA|@eAv@wAhAGD[Vw@l@sCzBcBpA[V_@XeAv@wAhAMJy@l@QNsB~Ag@`@o@d@WTC@sAbACDyBbBeAx@KH]VKHOLs@j@iA|@cAt@mCvBMH[V[V[TYROJOJUNMHKH_@RYNa@RUJSJ_@PSHSHYJi@N}@Xi@LC@YH]FKBIBQBUDq@Lg@F[D_CXkBT{C^qBVkBTk@J}@Pk@NSFg@NWHa@N]NIBWJi@Tw@`@MF{@h@SLq@f@u@f@gAv@]VsA|@QLULOHk@X}@`@{@Zi@PUFi@L_@J]Hq@Lg@Hi@HkBZeC^uATmBXqAReANu@LiBTuBVeCXwBTM@UB}@JwAL_AHyALOBmAHk@DwCRYBaG`@[B_CPm@Dk@Do@Dg@DoBLoBL}@HC?cAFa@Ba@BSBWBC?{@JgANaBXSDODk@N]H]Ja@LIBWHC@a@Lk@TQFa@PGBc@R{@`@_Af@iAr@a@XEBKHu@j@_@Xi@b@q@n@u@r@aA`AQP_A~@gBdBsArA_A|@s@t@o@l@u@t@q@p@a@^[XGFa@\\MJSPa@Zc@\\c@\\c@\\]TGD}A`A_B~@oAp@MD_@R_@Pk@V_A^_Bl@{@ZWJGBcC|@kBp@iBp@{LnEeC|@cC|@aA^kBp@mCdAiAd@aAb@{@`@w@`@CBQJi@Xc@Ve@Xi@\\c@X]TgBjAeFhDwAbA_@Ts@h@}AfA{B|AKFsDfCUN]VEBu@h@QJe@\\CB]TCB_@ZSPQLONQNCDKJONKJOPUTON_@b@_@b@_@f@STOT[f@W\\MRe@x@MROVWd@Ud@Q\\Uf@g@hAmDpIUf@cAdC{@rBoArCa@~@?@mAtCcDxHw@hBaGlNo@zAQ`@k@tAyBhFMXUj@o@vAm@nAOZWd@c@t@Q\\_@l@SXiAfBuBvCsC`EgBdCqAjBq@~@yDlFiJtMaAtAc@l@wBtCk@t@gBxBgC`D{HvJiB|Ba@f@yBpCkAvAuCpDUXs@|@qAbBuCpDc@f@y@dAcN|PoDpEIJu@~@e@h@cI~JaAlAeC~C{D`F{ApBcAtAk@~@g@x@c@t@Wb@Yd@EJ[j@a@v@o@rAq@xAKPm@xAu@jBM^[z@Wr@Ob@_CfH_E|Lq@rBqEbN_CdH}@nCc@pA}@rC_ArCe@|AGP_A|CUt@u@bCwBdHK\\c@tAOd@Qh@Ob@Wr@Sd@Q\\MXa@v@e@x@m@|@q@~@w@bA_@h@EFc@h@UZ]b@sAdBaG~HsAfBgDnEwAjBcAtAeCbDeBbCo@`AINq@jAQ\\Ud@Sb@Yn@c@hAGPg@tAUr@W~@Qn@Qn@ERI^GV?@?@?@DLS|@g@bCKf@CHm@nCCLEXKd@If@Kl@Mt@Kn@AHGb@Kv@Gp@Gl@Iv@Ed@ALCXGx@G~@?HGdAAj@Ch@Cv@?VAb@?DAf@AVA~@A|AClBCnAAhACbCK|JCnA?HQdPClAGhGAdAA~@Cz@GfAIfAKpAG\\CVG^I`@EXGZI`@K^U|@CLkAdEcCvIMf@e@~Ac@`Ba@rAg@lBq@zB{ApFmBzGqBjHeAtDsAvEeA|DqArE_@fA"
                     },
                     "start_location" : {
                        "lat" : 28.8576731,
                        "lng" : -97.0262176
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1180
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 29.08417249999999,
                        "lng" : -97.29499059999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Esplanade St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kkqpDn}xpQdAb@PHxAj@|ClA`A`@NFnAf@dDrA^NLDNPh@Th@b@f@^h@Xl@V\\NdA`@x@Z|ChAJAb@P~@^pCfA`Bp@lBt@fAb@t@\\XJx@\\"
                     },
                     "start_location" : {
                        "lat" : 29.0938184,
                        "lng" : -97.29000449999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.2 km",
                        "value" : 6218
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 276
                     },
                     "end_location" : {
                        "lat" : 29.0831916,
                        "lng" : -97.3543706
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTX-72 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eW Heaton St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow TX-72 W\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "aoopDt|ypQa@tAm@rBkAjESr@kAdEMh@iA`Ee@dBg@hBCD_AjDmAlE_AlDG\\I^E\\EZALAJAL?JARAR?b@?h@@V@ZDv@Dz@H`BBj@@X@\\A`@?ZAN?HALGr@I`AYlCy@pIeGno@eAvK_AtJ_@`EE|@Et@AV?XA^A\\?@?j@@b@?l@@h@Bj@@d@B~@Dp@Bt@@f@Bz@@ZBd@@\\?P?P?V?R?PAV?B?PARARAREh@I|@Gp@YxBIp@Iv@M~@MhASbBQzAC\\CXAFCZATAXATA\\?V?V?T?XBrB@T@f@Bt@BdA@f@JpD@ZHnDDnB@`@F`CB`AHfDHzCDfBDvA@b@FhCDlBDxA@^@z@DvADnA?PB~@Bn@@j@@ZBT?HB\\Bb@D^DZDZDTLt@J^H\\H\\JZL\\Vt@`@|@t@|AZn@N\\h@hAR`@z@dBR`@f@dAzDbIDHDF\\j@Z`@d@j@VVPL^Zb@ZXPd@V^Nj@Rf@PfBh@ZJRFJDTHBBLDNHPLLHTPRPVVPP"
                     },
                     "start_location" : {
                        "lat" : 29.08417249999999,
                        "lng" : -97.29499059999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "54.5 km",
                        "value" : 54475
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2031
                     },
                     "end_location" : {
                        "lat" : 29.2545428,
                        "lng" : -97.820729
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eUS-87 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}hopDxoeqQ@T?F?F?FAHI\\cB|@}@f@s@b@UNQLKHw@n@URMJKJEJ[ZYX]^YZY^k@v@EHa@n@sBhDEFuA`CU^g@x@KPw@rA}AjCKPu@lAaA`BwA`Cm@bAQX{@vAcBtCiBxC[f@c@v@cAbB[f@_A~AaAbBKPo@dAgAfBABmApBwAbCGHsA|BeAfBU^MRmBdD]h@Wb@_A|AEHs@lAGHu@nAuA~BaA~AeBtCS\\{DvGw@pA_@n@iAlB}AdCU`@gAhB_A|AqAvBcAbBmBbDk@`AeDtF_@n@c@t@aC~Dk@|@{BtDU`@}@zAMRU`@wA`Cc@t@gAhBgBxCgDvFcBtCyBrDwA~BmApB?@U^qAxBsBhDU`@CDQXU^g@z@o@dAU`@U^e@v@eAfBcAbBgAfB{@vA[f@a@p@aHdLoCnEU`@EHOTaExG}AfC{AfCu@nAiCjEo@hAsCzEGJqDhG_C`EoEvHgIhNkBbDc@v@iB~CCDS^cCdE_C~DABcBpCk@`ASZi@x@OPQVy@bA[`@UTABIHOR{AbBe@h@u@z@kArAmArAsA|AsCbDs@v@mAtAcBlByFpG{A`B_FjF{D`EQRiFnFkFtF_BbBeDlD_EhEi@j@[ZiBlBMN}BbCmDzDwA~AeAjAqAzAcBjB{EpF{HrIeDvDqIpJk@p@mApA{@v@URQNQNe@\\a@X]T_@R[R[P]NEBc@Pe@Re@Pc@Nc@L{HvBqGdBqGdByCx@{Bn@_Cn@{A^aAXKBcEhAy@RqGfBoBh@kD~@iD|@qGfBa@JwDbAkD~@iD~@iCr@yCx@cDz@oFvAgCp@aEfAqGbBgCr@]HkD|@{Cx@i@NmAZsA^kAZg@Na@LC@[Ja@No@V}@`@w@b@e@X]RoEtCyBtAoBnAkDxBoBpAIDoBpAcBfAQJyA`AyBtA{A`AyBtAwEvC]TyBtA[RuA|@QJuAz@{@h@q@b@u@f@YP[TWTWVQRORKNMPINCDKRKRGRGNIVGTGVI^Kr@E`@AZAb@A^DzB@|@?RBpADzBBdADjCHpEHfFFnEDfC@n@@b@BvAB|AFjD@x@DnBFdE@x@?t@Al@Ad@APA\\Gx@Ir@Mz@G^I\\Qt@Sx@_@bAWn@[r@Q\\QZ_@j@c@n@yAnBKNoBlCg@v@a@l@i@|@a@r@Yl@c@|@c@`A]z@Ob@M^_@hA[bAUz@S~@WhAUrAMv@Kx@Iv@WrCw@jLYxDk@dIaAdNo@dJc@jGAVAH]fFq@pJCf@IdAM~AEd@En@Kz@Ip@Kj@Ox@Or@YhAOl@EJIXOd@[x@[x@e@dAOX[l@c@r@GJm@~@g@p@OPi@n@m@n@i@f@e@b@A@q@h@e@\\uA`A}F|Ds@d@e@\\UNuCpB]T]TsDfCqFrD]VC@g@\\e@\\a@\\]X_@\\UVYX[\\SREFe@j@_@h@CBW^AB_@h@Yd@_@p@[n@[l@?@Sb@EJSf@Qf@Un@Qd@Ur@[|@Ob@mArDmBxFi@zAYx@Un@Uj@GJS`@Wd@[d@e@n@e@l@c@d@_@\\A?[XGF[VaAx@c@^a@\\YX[\\q@t@k@t@WZYd@SXU\\iC`ESZiCbEGLwAxBg@v@S\\Y`@[d@]d@UXY\\{AhBmAtAkAvAsA~AoAzA{DtEkAvAo@t@Y\\YZaBpB[^eBtBs@x@c@h@KJ[`@o@t@Y\\A@kAvAYZo@v@g@l@g@j@STu@|@A@o@v@CBsDlESVYZkAvAEDwClDm@r@EF{BlC[^STw@`Am@p@EFq@x@s@x@q@x@gAnAq@x@s@x@KLwIhK_CpCW\\IHaAjA}DvEy@`AqCfDwClDmDbEsEtFoDfE{ChDyFbHAByClDcBrBqDjEY\\_CpCWZeBrB_CpCY\\y@~@wBjCWXa@f@]d@[`@U\\Yd@[f@AB]n@Wj@Q`@Qb@Yr@Wv@Sn@Oh@IXGZMj@Or@G\\CNEVCRs@xEo@fEm@dEg@bDu@hFe@bDk@pDKv@eCtP_AlGU~Ac@lCYpBuAjJa@lCSnAMv@Gf@o@fESxAQjAo@dE[vBQnAIf@EVm@`Eq@tE_@`CqA~Iu@~E_@hCYrBSxAOhAMlAW|B]~CALc@zDMnAoAfLkBfQ}@bIs@xGcBtO_@hDUvBOvAy@zHUjBUxBK|@cB|OQ`BEVYrCYdCe@hEU|BGf@UvBSfB]`DKv@UvBqBzQs@vG?@Gh@Gh@KbAIp@In@G^ERGd@O|@WfAOp@Ol@[hAMd@m@tBYbAEJ{@rCSp@yAdEcBjEcBlEQb@IZQn@I`@EPKn@Ij@Ed@?@Cd@C^AV?FAP?ZAT?V@b@B`BBbB@TBlAB|A@`@?B?NBfAB`B?rA?L?BAf@AjA?FAd@Af@AV?RA^ADEjAEx@WjFGhAAHKvBAPSvDOhDABSlEGjAYbG[~GUzFQdECh@Af@E|@]nHEdAEx@w@rOCh@QbDCf@KzBw@rOQvDARUjEUrEE~@a@hIGnAWhFO|C[dGc@zI}@nQIhBc@xIQ`Dc@nIGfAK`Ca@`IS`ESjEIzAcAnSg@zJOvCSlEkA~Uc@lIq@dN_@bIMxBUzECZUvEGdA_@fISzDSrD?NOrCKhBEx@[hGi@lLYnFCt@AVCh@?b@?p@?`@?n@@l@Bf@@^Bd@Dp@Db@B\\Fh@T`BF`@Ff@F^n@nEBRBR~@vGdAjHz@`G@JDZb@|C^fCp@xE\\zBrAdJ|@lG~@vGhA~HRxAn@vEt@lFf@tDt@fF^pCT~Aj@`EDZ@B`@zCXpBj@dERrA@L\\hCj@lEHp@TlB?@\\xCf@`Ej@tEv@zF\\`Cd@~CRzAb@zCHd@Jr@Jz@Hh@BL@DP~@Nn@L`@J^FTXjAHd@RhABXPlA^~BD\\NbARpA`@rCNnA@FBR@BXtBt@bFn@tELv@T`BFf@`@jCVlBHr@PnAPrAHt@D^@JXxBDZBRRtABTZvBj@~DPjAJv@@Hb@|C`CnPHp@|@jGv@nFtBbOHh@f@jDPlAv@tFHh@VbBBTXlBXjBb@|CXrB@DDXx@|FXnBRtARvAp@tE`@rCBRz@`GDTt@lFBNr@~Eb@|CRnAlB|MVfB?BXjBHp@b@tCNdAZ~BN~@b@|CXtBXxB`@pCrBtNF^DXN|@f@tDVfB\\xBh@tDr@`F^`CHh@Ff@d@~C~@tGDZTzAFd@b@zCDT"
                     },
                     "start_location" : {
                        "lat" : 29.0831916,
                        "lng" : -97.3543706
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "21.1 km",
                        "value" : 21108
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 752
                     },
                     "end_location" : {
                        "lat" : 29.2464351,
                        "lng" : -98.02749709999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-87 N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "{wpqDpr`tQFb@BRd@`DJr@h@zDPfAZzB?@dAjH@DXpBXnBx@zFBN^lC~@lGHj@l@fEF^h@pDHj@Nv@VtA?@z@nELl@^lB@FPv@DTP~@Nx@hBxLv@jF`AzGh@|D\\zBJ|@Hp@Jv@RfBVlCTfC\\hDLlAPzAHp@D^d@`DZzBHf@pA`JHf@L`AbCzPDVbC|PL|@bBjLVfBZxB~@vGHf@PnAnB|MlDrVfA|H@D`BfLbEnY?DXlB\\|B|@tGfBxLz@hGLv@PrARnAr@`FZzB@Fz@~Fz@dGdAjHd@lDPlAn@fE`@vChAzHLbA`@lCFf@BPdAnHdBzL`@pCx@|Ft@bFBVxA`KjAlIJr@rApJHf@@HNdAZvBHf@XvBHf@ZtBb@~CRtARvA`@pC@JVhBLt@D\\n@pEf@lDBLt@jFBL`@vCnAvIl@fELz@x@`GLv@t@jFh@|DNx@nAfJf@fD|@pGh@lDp@zEb@zCfAxHBT\\~BBPb@vCRzAVhBHl@NbA\\dCLp@PpADZFf@D\\NjAL|AFx@JzADv@B`@Br@@b@Bd@?B@h@DjEBdD?P@fB@h@@bD@rA@f@BdD@xB@h@@bDBlB@~A@z@FlL@XBdD@zBDlE?D@jA?DB`D@vB?N?`A@|@@lB@z@@vA?r@?Z?\\?^AH?NCh@AXARCT?FEb@E^Ef@If@EZG^Kf@EPELMj@Of@Yz@M^Yj@e@`A_A~AU\\EFm@v@YZIHo@n@a@^a@ZeAx@MH{@n@kAz@}CzBWRc@ZUPa@Za@\\WVKJa@`@]`@KLq@~@ORa@r@MRWf@c@~@Uh@KZQh@Sl@WdAGZOr@Mp@Kx@WrBUtBc@nDUfBQ~AKv@Kj@ABId@G^A\\Md@]hAELeA~Co@lBy@bCSj@Un@yBtGAHSh@c@pAK\\K\\ADGPIXOh@IVa@xAA@W`AQj@Md@GVELOd@Uz@St@Md@Ob@K`@ABYdAm@vBAB{@~Co@tBk@rB_AbD?@y@vCk@pBMb@}@`Di@fBI\\Qj@Oj@_@pAi@nBe@bBk@tBCHADUt@W|@w@pCi@lBGVo@|BK\\W|@oArE[dA]nAi@nBi@jBw@tCQn@YdAOf@GTK`@CLENG`@Kd@Ih@Gf@CPEZCZGj@KlAKpAKfAYjDKnAUfCIbAWvCw@hJWtCIbAC^Y`DAF[xDANQxBKdAMpAIbAO`B?DQnB?HQhBWxCUzCKfAU`DOh@Ep@Eh@Cf@AJGr@OjBCZ?FCZA^CfA?P@b@?`@B^@`@BX@P@B@RDTDZDZDVJd@FVHXNh@nAhEZ~@Z~@X|@HZPj@Ln@F^@DF`@Hx@BXBX?H@R@Z?D?T?ZCv@Cx@Il@CXA@In@GT"
                     },
                     "start_location" : {
                        "lat" : 29.2545428,
                        "lng" : -97.820729
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "42.3 km",
                        "value" : 42285
                     },
                     "duration" : {
                        "text" : "30 mins",
                        "value" : 1820
                     },
                     "end_location" : {
                        "lat" : 29.3983218,
                        "lng" : -98.3881837
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eUS-87 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Jack in the Box (on the right in 42.2&nbsp;km)\u003c/div\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "geoqDz~huQGXCJQp@GRGTKVUj@Uf@GJWh@o@|@w@~@OXw@v@{@|@yBvB{DzDw@v@m@l@oDpD_B~AmGnGcA`AiAhA{@|@URiFjF}C|CgAbAwCxCqBnB}D~DyCxCwAvAcDbDgBfBWV}C|CwDvDo@l@gDhD_B`BIHUTeNhNSR]Z}@v@_@\\UTSNUPSNSNYPoAx@KD_@To@^MH]Rk@\\i@Zc@V[PWPSLQL_@VWR[T_@Zg@`@[XONa@`@a@b@SRQRUXSTSVUVMPOTYb@Yb@QX[f@u@fAi@x@_@j@a@l@kAnBINWb@_@p@Q\\g@dAg@bAg@bAQ^}@jBc@~@{@dBuBnES`@a@v@GJOZCBOXW`@[h@QXw@lAi@t@Y\\k@t@CDk@r@_@b@c@d@k@l@u@t@KJ]\\a@^KJ_@Zw@r@}@t@CBgA|@eA~@wDdDoFvEsAlAiDvCuBhBSPGF]XQPy@r@[VGFSPuAlAo@j@a@^cDrCWRoC`C]Zo@h@u@n@GFy@r@WRGDMLKFKJWR_@X[TSNULi@\\IHs@b@s@`@[RIDA?qAr@kAj@}@d@WJKF{@b@WLGDUJs@\\kAl@ID_D|AsDjB}Av@iDdBm@Zw@^gAj@}@b@aAf@gAf@wCvAID]PcAd@QHc@RqCrAE@[No@ZC?}BfAmCnAqAl@m@Xw@^iFbC_@PaF~B{@`@[NcGpCsCrAeAf@sGzC{Ap@{@`@uBbAo@ZuAn@}Ar@MFy@^GDC@[No@X[NKFcAd@cAd@s@\\EBcDzAaBv@m@VcAf@kAh@QHKDeBx@]NQHiCnAUJ[N}@`@{@b@oB|@{Ar@QH_@P_@PA@}@b@a@PwAp@WLg@Ta@R}CvAoAl@YLc@Te@Ri@V]Pw@^q@Xy@`@WLeCjA[NMDmAl@g@Tm@Xy@`@s@Z]PiClAeAf@i@Vy@^o@ZgCjAMH{Ap@OHm@XoEtB_Ad@e@R_@PoCpAcD|AyAp@s@\\qCpA_CfAiErBuAp@I?IB{@`@{An@qDfBcAd@c@REBcBx@]Nw@^mB~@KF_@PQNqB~@c@RcCjAq@ZQJsAl@aAd@wBdAiCnAgLnFwEzBgAh@w@^mAl@]Rc@VcAr@s@l@]Z[XIFIJYVUVQRWZMN[b@_@f@W^[h@OVQZS^Yl@MVITKTKZGNCJEFM`@ENGNK^K^ABIXADK^Kj@Kb@Qr@c@pB[tAo@fCi@nCERI`@EPEPMj@I`@Op@A?GX[xAo@tCc@rBUdA[rAY~AEZKp@CTCVGh@AHAPCZCd@AN?@Al@ARAn@AF?^CnAAVCzACtA?NCpACjAAPA\\?JAn@Al@EzBA`@CbACbBG~DItEA`@?TAx@Ap@Ab@Ad@CnBARGf@?FCl@Af@CfAGnBAvAGpD?RCvBEfDI`FElCEdCIrFAp@?n@?`@AbADPEvDAl@APA|@ShOAz@Al@ExB?ZALCbCCrBAf@Af@AbAAn@CzAAXAnA?PA\\?\\A`@A\\?`@?JC|ACvA?b@AXAf@?RCzBElEElC?XAf@A`AAbAAfAAP?TCbBGzEA|@E|DArAAj@?RCjAAdA?f@?F@r@?X?Z?Z@pA?l@?f@@h@?r@?N?HBxE@vC@dA?lA@zC@xCBbD@bD@lD@pA@bB@tC@vD@fC@|B@`B?N?H@~A?z@@xC?J?R?F@dA@lC@tB?bA?r@@n@?D?X?~@@`@?pB@jB@tD@l@@zA@rE@xB@xD@|@@bC?P@rB@`CBbE?h@?d@?J?PGh@?l@?Z@j@?ZD~LB`D?j@@pD@z@?nA@^?N?N@\\@TDn@@hB?Z@j@?Z?@?pA@`A?N@bA?v@?b@?B@~@@`B?V?N?h@@bA@~A?p@?R@|@?l@?V?P@jA?f@?J@T?~@?p@?P?V?V?TAX?TAF?`@CVAf@C^Gr@Ef@Ml@Gn@Ip@Iv@EVM|@OlAa@tCG`@MfAGb@SrA]nCS|AIh@c@|Ck@dEOfAOlACTETCPE^CNOhAMz@QrAAFGj@ADa@zCe@hDKt@CNEVOhAOlAKt@_@nCYzBKr@Ip@OfAe@tDCLALGZCPQxACTU~A?@c@hDkAbJu@tFg@xDS|Aa@~CUfBS~AIt@{@pGCRKv@Y`CIj@AHo@tEIn@WbBWlBU`BYvBm@lEe@bDM~@q@`FM~@M|@CR?BG\\?Da@rCIh@Gj@StAU~AIl@Kx@Kx@?BIz@KvAABC`@GjBC|A@`BF~B?J@d@@b@Dr@DhAFbBD|A@hBAfAAjAC`@EbAG`AC^KdAK|@EXu@vFWjBg@zDs@nFq@dFe@lDKv@i@hEqA|JKr@a@~C_@~Ce@jDUxAGb@Sz@Ov@Ql@K\\ABUr@Sl@Ul@Qd@EJYl@Yl@ABsAtCMV_BfD_@hAYz@GRM^St@U~@IZERa@`CMz@QnAKx@o@pE]lCa@xCOx@APKv@E\\E~@AvADxA?HDjAHpBV`EBj@@LB\\@^Bd@@TFhAFnABj@@PJxB?D@L?FL~BF|ARvD?H@^TrEXfGNhD@NLnC@RJhC@V@^@lB@XAxBC\\GjBAJShBWhBa@rBm@xCI^}@hEYrA[zAk@hC{@`EaB|Hg@`CMl@GX]dBI^k@jCS~@UbAe@xBAF]`BOp@I`@uB~Ju@lDiDdPaAzEENi@jCc@rB{@`EaBvH_@dBOr@g@~BUjAWrAUhAI^c@|Bc@|BoAnGs@nDEP_@hBcBtIi@lCsBrKWpA[~AEPa@vBSnAMv@WlBGf@gA~HYvBYvBg@nDqBrNi@xDOpAe@lDGZs@nFAHw@xHe@tE?@]~BEVi@~Di@tDk@lEGd@OpAABGb@?@CTCR]nCUdBO`AMv@Kh@EXI\\AFUbACHER[fAIZM`@]`AOd@w@rBKXSl@]~@MZu@rBGP}@hCIZUv@Sx@YlAa@vBSdAGb@OhAMz@_@jCKz@WfBGd@CPWbBWjBEZObAM~@QtAMx@QnAKv@EZKr@GZSvAYvB}@bHId@O`AQfAEX]fBKh@m@jCK^g@hBq@tB_BlEKX]~@Ob@ITGLOd@{@`CiA`Da@dAKVeAtCIVi@xAK\\o@dBc@lAADOb@M\\KXYt@Yx@[z@q@pByAjEWr@_@bAWx@Uv@GTUfAShAUdBM~ASvF?D?f@@x@?X@~@@P?\\@`B?T@|@?tA?`AC`D?VA\\At@?l@?`@?\\?tBAbF?xB?r@E~CAT?x@At@AR?pB?RA|B?^AT?Z?L@d@?h@"
                     },
                     "start_location" : {
                        "lat" : 29.2464351,
                        "lng" : -98.02749709999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "60 m",
                        "value" : 60
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 29.3986188,
                        "lng" : -98.38866779999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eS East Loop 410\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eI- 410 Access Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ozlrDbmowQCFA@?BCHCNCJAFCFEFEDEDQH"
                     },
                     "start_location" : {
                        "lat" : 29.3983218,
                        "lng" : -98.3881837
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 29.3993666,
                        "lng" : -98.388684
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eS East Loop 410\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eI- 410 Access Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "k|lrDdpowQuA@A?}@?"
                     },
                     "start_location" : {
                        "lat" : 29.3986188,
                        "lng" : -98.38866779999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.2 km",
                        "value" : 6166
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 227
                     },
                     "end_location" : {
                        "lat" : 29.4500953,
                        "lng" : -98.4032842
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to merge onto \u003cb\u003eI-410 N\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "aamrDfpowQAD?@A??@C@G@gBXu@NK@G@YDc@B_BJS@gABI@YBUBuA?}A?W?{C?S?mDAcE?yB?[?eA?sB?}A?kB@[?{B?U?gAAO?S?aD?O?mB?uC?yA?{@AgC@yAAuA@_C?eF?g@AiE@iE?uC?oA?{@?qB?G?U?C?G?W?i@?qA?}@?iB?_@?C?A?U?cAAo@@Y?O?A?E?C?m@?E?C?G?YA_B?O?_@?}B?oD@C?u@?q@@aA@qAC}B@g@EoB@sA@eA?{@?I?U?C?I?wE?sA?kBBeA@A@G?E?qAFG?c@BA?O@A?_@DY@[Ba@DG@K@_BPs@H[FUD[DQDqATC?QDa@JI@E@KDSDA?C@ODYHC?EBKBQFoA^A?WH_@LA@oAd@k@T[LKFGBYJo@XOHa@PC@A@WNq@^QHYPq@`@IBmAx@q@f@IDq@f@OJsAdAMJwAnAkEhEc@b@_AbAkApAy@~@}@fAmA~AOPOR_@d@KP[`@ORMRY`@OVw@nAg@`As@xA[p@S^o@tAOZa@|@mAfCWh@i@dA_@p@OTEHKJSXMPy@v@YVWPgAr@m@Z{@Za@Lu@RYHq@L"
                     },
                     "start_location" : {
                        "lat" : 29.3993666,
                        "lng" : -98.388684
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 532
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 29.4526396,
                        "lng" : -98.4078074
                     },
                     "html_instructions" : "Take the exit on the \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eI-35 S\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "c~vrDnkrwQGLCB_@NSJC@URWTIJEDGFIJABILEJINUb@Q`@Q`@Yn@Qd@Qj@GNELk@fB[dAq@xBQf@a@hAWx@"
                     },
                     "start_location" : {
                        "lat" : 29.4500953,
                        "lng" : -98.4032842
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.1 km",
                        "value" : 8070
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 298
                     },
                     "end_location" : {
                        "lat" : 29.4404804,
                        "lng" : -98.4841934
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e and merge onto \u003cb\u003eI-35 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "_nwrDxgswQWx@i@`BGPIROb@W|@Up@A?CHKZO`@CFMZO\\EJWl@MTYh@g@v@UXA@UZGNGNOTGJKRKNABGLA@S^EHCDc@l@?@GJABKPYj@CFELKVAFCLCTEd@?DA@?JAT?@?@?L?@?@@X?@@H?JBP@HFXDL@DFRDHFLHN@BDFHJVXZVLJZT\\V\\Vx@n@~@r@JHVRBBXT\\\\FFNPZ^BFV\\DJLNTN`@`Ax@rBJXJ^n@nBt@~BHRdE~LRp@DJDN?@L`@HZXx@n@lBJ\\L\\^nA`@hAd@lAb@dALTP^d@fA|FpM`@z@bCpFbDnHnAlCjAfCv@`Bf@`AvAzCP\\\\r@Rd@\\t@b@~@dArBBFjCpFJTTd@Zn@x@bB@@Tb@BHFJFNh@lAp@dBXv@Tj@Tn@FNNb@Ld@BHX`ALf@j@~BJ`@FV@Df@vCFT^lCFd@L~@@DLzABNLfBLfBJ~B@XBtBBdDCh@CpF?h@@f@?h@?N?V?b@?b@?r@?d@?lE@dD?LFrB@j@BlAHtABh@H`AD`@`@pFHbALhBB\\LzBBVBf@?@Bl@?XDpB@hC@fB?`@?lC?h@@pA?B?nA?f@?X?N?lA@`@CfC?dE?jA?fB?xB?PApC@~C?X@xD?|DBrEDtC?h@@hC@bA?Z@T?DA`AA^?v@Ch@Az@A^AXAJAZAb@E~@?@G|@AL?JALQtBAPABCTAL?@EX?B?@In@CXALCPGj@?@Ih@Kz@ABALCVAHIp@CRA@CZG^Kz@AHAHIf@G\\Ih@Ib@GZQv@ERCFCJENIT?@Md@Ob@Oj@Oj@I^ELWvAMx@It@E|@"
                     },
                     "start_location" : {
                        "lat" : 29.4526396,
                        "lng" : -98.4078074
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 529
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 29.4386241,
                        "lng" : -98.48908770000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to stay on \u003cb\u003eI-35 S\u003c/b\u003e, follow signs for \u003cb\u003eLaredo\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "_burDdebxQDT@J?D?p@@p@@p@Dr@?BDf@@@?DHj@DV@@Jf@@DNn@Pj@FNr@~Af@bAp@nALVb@z@nAdC"
                     },
                     "start_location" : {
                        "lat" : 29.4404804,
                        "lng" : -98.4841934
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 376
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 29.4369743,
                        "lng" : -98.4924527
                     },
                     "html_instructions" : "Take exit \u003cb\u003e157A\u003c/b\u003e toward \u003cb\u003eLexington Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMain Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSan Pedro Ave\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "kvtrDxccxQ?L@@?BP\\DJDHR`@?@P`@LXDFDJ`@x@`@x@Xj@h@bB@BN^@BL`@@@N`@Nb@@@Tl@BL?L@@"
                     },
                     "start_location" : {
                        "lat" : 29.4386241,
                        "lng" : -98.48908770000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 190
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 29.4361078,
                        "lng" : -98.4941381
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eE Elmira St\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "altrDxxcxQf@bAh@fAn@bBPb@V|@"
                     },
                     "start_location" : {
                        "lat" : 29.4369743,
                        "lng" : -98.4924527
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 124
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 29.4349966,
                        "lng" : -98.4941295
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Main Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uftrDjcdxQR?VA@?D?B?L?T?`@?b@@z@A"
                     },
                     "start_location" : {
                        "lat" : 29.4361078,
                        "lng" : -98.4941381
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "71 m",
                        "value" : 71
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 29.435113,
                        "lng" : -98.4934284
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eE Quincy St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w_trDhcdxQ?}@ASAKCMEOGO"
                     },
                     "start_location" : {
                        "lat" : 29.4349966,
                        "lng" : -98.4941295
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "77.8 km",
                        "value" : 77806
                     },
                     "duration" : {
                        "text" : "43 mins",
                        "value" : 2603
                     },
                     "end_location" : {
                        "lat" : 29.8779498,
                        "lng" : -97.92745269999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to merge onto \u003cb\u003eI-35 N\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "m`trD|~cxQ_@OC?G?C@KDEBKHQJIBI@E?E?IAEAAAQMEEMK[SYy@Y}@IQA??AqAeCs@wAQa@Ue@w@_BIOKUSc@{@eBA?g@cASa@aAuBUe@KO_BaDm@qAk@mAGSGUGSIYGUEWI_@CYGa@CSQgCAiBB]Fe@Dk@D]DUFa@Ny@TcATaAVaAZsAJc@HWDUH_@He@ReA?EFa@@E@KBSHi@?ENiA@E@KD[Ho@?ABS?ABQD]D[Hq@Hk@D]?IFg@@M?ABU@CDa@?A?CB[@KHgAHmA?C@K?CFeADeA?Q@k@@G@o@@s@@qA?U@]@sB@_B?]@]C{@?I@aA@i@Bo@AoA?G?kA?k@?g@?C@y@?U?cB?qG?q@?g@?iA?GAsB?q@?iA?}GAeD?c@?O?{@AeCAwBAmEAmEAw@GeBASAYCw@GaAGgAIkAMoBAOK}ACk@IiAACKkBEg@Gw@M}BAi@Ci@GyBCuC?M?ACuC?uG@s@?C?e@?C?{B?{B?i@?c@?C?Y?OAsACg@Ai@AS?OEgAAMCy@MiBSiBOmBK_AYoB]wBO}@Mk@_@cBy@cDCIe@_BGOUq@y@aCk@{Am@wAO]AACIYk@e@_AQ_@IOa@y@Ug@a@u@w@_Bi@kAOWKS_AoBMWSa@w@aBqF_LSa@Sa@ACIQkAiCmAoCeCqFi@oAcCuFIOIQQa@e@eAu@}Ae@gAGOgAcCu@kB_@_AAEa@oAQi@Qg@K]K_@EMQk@CE_@iAAAM_@M]Ma@c@qAK]q@sBWu@GWu@{BoCoIOc@a@eAk@yAy@gB_AeBw@mAS[cC}C]c@KMOSKI]]IISQSQOOCCQOKKu@i@OMGEEEECMKSMa@UMIm@]k@[UMQMu@_@u@[AAuCiAm@Yy@]c@QaAa@}Ak@AAw@[GCWIsCiAOGuAk@GCIC[MAAICGCECu@[GCOGEAwAk@o@Y{@]UKKE{D{AqAi@s@Y[MECyCmAICa@OcCcA_@O_@OA?_Bq@eCaAeEcB}@_@WK}@]_CaAiBu@w@[w@[SIc@Qa@QSIMCqAe@qAg@m@Sg@MeAUa@IKCk@Mw@Ie@EaAGs@E_ACaB?wC@o@@i@Ak@E_BAU?w@Cs@CcBMi@CmAIcEc@sAOCAc@EgAOaD_@sDe@o@K[ACAUAGAC?QCE?A?KCOAWEOEg@E_@G]CgAOoAO_@Gi@IcBSqAQs@I_BQaBU_AMa@EqAQEAiQyBw@IcD_@aBUQCy@KyCa@aAKmAQA?k@I{@IA?_BSIAA?a@ECAu@Ko@K}@KA?YEm@EyB[s@IiAOmDa@_I_Aa@G{@IwGy@_AM]EyC_@sEk@qAOw@K_D_@OAa@GmAMYCSC[EUEq@IIAmBUiBUA?{@KAAG?QCMCG?WE[Ec@Go@Iq@I_AMs@IUCsASmFq@_BQ[Ew@KgGy@_BWk@MoAY}@W_AY]Mq@Wg@O_@MeBk@mA_@OCgBa@cCe@eCg@kB]CAk@KCAw@OcB]kAUkAUSEQCgDq@iEy@A?y@Q[Ge@I_B[mAUg@Ok@MqA[g@MsA_@_A[eBm@_A_@kAg@cAe@QKMGkAm@ECMIu@a@i@]_@U_Ao@aAu@A?eA{@y@q@USa@]AAYYECOOa@a@u@y@GEIK[]i@o@_@c@OSMOOUMOMQGIGI[c@MSS[AAc@q@Yc@CGU_@Ua@EGOWEKMUg@_AUg@_@w@Ue@CGiB{DKSCGSa@CEq@{ACEO[CG[q@mAiCg@eAy@gBg@cAe@eASa@sAsCIQQa@Sc@GK?AKSm@qAc@aAS_@CGO[Sa@e@eAIOa@}@OYm@qA]u@EI?ASa@O][q@_@w@Ue@GOS_@qCcGmBaEGMKUUi@Wi@o@sAGKs@_BEGe@eAOYWk@Sa@GOKSQa@g@eAKSYo@Sc@Yk@a@{@Qa@KS[q@Sa@e@eAg@cA?AsAsCqBiEaAuBCG_@u@qAqCMYs@{A{AcDWi@?AEGi@kA{@mBWi@AEWo@Yw@O_@_@iAm@oBCI]qAIUI[UeAQw@WmAQ_AEOk@{Ca@uBG_@Kg@AGIe@a@uBWqAUkAU}@CK]qAS{@s@yBY_ACEi@yAEKa@gAe@oAQc@c@gAYs@AGc@}@ISWk@CESa@Uc@Ua@y@uA_@m@OWcBeCQUKOk@u@QSi@q@gC}CsCkD}@gA_AiAwCoDs@{@g@m@q@y@W]]_@UYW]IIOQY]ACMOIIW]y@aAQSsAaB}BqCu@{@[a@SW}AmBsDoEUY_AgAcAoAkAwAIKaAkAY]IKyBkCUYy@aAa@i@o@w@wAcBk@q@ACwAeBGGcCyCm@s@W[qEsFMOe@i@cBuBcBwBaAkA?Ae@k@GGkAwAY[QUOSOQGIOQIK]a@mA{AMMIKmA{A_@e@Y[KMu@cAGIa@k@[e@OS]k@MQ_@m@GKa@u@i@aAAAo@qAo@uAg@iAUm@Ys@_@cAc@qAWy@GSUu@]sAMe@a@cBQo@ESOk@wCsLa@_BUy@Ke@g@oBi@sBKe@]uAaAuDCMy@gDYeA[_AUw@GOOc@Oa@]}@Wq@CEOa@a@{@]w@S_@Yi@S]Q[OWc@u@Yc@a@q@_@o@aA}Aa@o@AC]k@EE{@uA{BqDw@sA}AiCe@{@g@u@e@w@uC}E_@m@IQe@{@e@aAUe@MYSe@]}@mAyCa@eA}@uBcEeKkBwEq@cBw@iB{@yBc@gAQc@Qa@Wo@]{@y@sBu@gBQe@Qc@KSGQEM[w@Sc@?A_@_Ag@kAiAuCYm@MYGOSg@M[Si@M[GMCIEKa@_ASi@EGi@uAYo@kByEO_@CGkAuCaBeEo@}AIQOa@ISCECG_@}@KYm@{AIUQa@EKCE_A{BcAiCg@kAq@}AQ]EK[q@a@s@a@s@gAgB?AOWSYo@aA_AqAy@cAwA_Bq@w@KMCCUUMMu@w@Y[[[UUk@m@CCMOaAcAk@m@c@c@Y[WWY[SUIIu@w@Y[WUY[y@{@YYqAqAWYgBoB_@]UWy@y@CC{CaD[]WWo@s@MMKK_AcAaBcBw@y@q@s@CCUWIImA{A]c@i@q@UWY_@sBiCA?wAiB}@iAGGEGEEQUoCkDmAyA[c@MMEG?AcBsBs@}@i@y@CESWg@u@y@qAu@uAO[GKMSwA{Cg@kAEMGOISQc@g@kAO_@AC?ACEQa@KWWo@Qc@{AqDcD_IEIgBkEiEmK{@qBc@cAo@aBWm@Um@e@mA[w@Sc@q@iBAAe@kAa@aAEI{@yBEK?AIOw@kBgAqC}@wBSi@a@}@KUi@sAuAaD{A{DmBwEYs@Wm@[u@{@{BmCqGwAmDQc@cAcCc@gAQc@Wk@m@}A]y@Qc@Qc@AAu@gBSe@kAwCuAgDCGeAgCYu@_B{Ds@cBqAaDg@kAw@oBg@kAu@iBc@cAmByEQc@y@uBMYUg@cAgCAAa@aAiAsCa@_ACGQa@EKKWSa@Sa@c@eAsAcDGS_@{@Qe@gAkC_A{BCGi@oAKUM[u@iBAESc@GQ}@cCCIy@mBeAgCGOISk@yA[u@g@kAISWm@_@}@s@iBSc@GOIQSe@c@iAGQ[u@}@yBIS{AqDAGUg@ISo@sA?A{@cBMWOWo@kAgAsBKWeCuE}@cBSa@Ua@Sa@OWIQMWKQCGS_@Uc@Ua@ACCEMUUa@g@cAUa@Sa@q@oAMSSa@sAgCEI_AeB_@s@GKiCaF_AgBAC[m@e@{@AAQ_@EEO[eCuEEIEKyCyFq@oASa@Ua@Sa@Sa@MSy@_B_AgB]q@Ua@[g@c@{@oCkFSa@A?_EyHa@u@]o@y@_Bc@{@w@yAq@mAs@kAyA}Bu@kAKQ}C_Fq@eAi@{@Q]OS_@o@Ym@MYKSO[k@yAYu@a@oAAAOe@Mc@m@qBmAyD{D_MOc@Me@Sm@YaAOe@IUUs@wAqE[cAo@uBUo@Y_AOe@Oc@Qk@c@uAGO?Ak@gBUw@K[[aA_@kACEe@mAISEIQ_@O[Sa@CG?Ac@y@MUGKEGu@mAc@q@S[k@{@k@{@GKg@u@W_@m@}@W_@CEQYiBkCIUOSo@_AYc@ACq@aAqByCs@eA{@sAq@aA_@k@kBqCQYEEU_@W]c@o@oAmB}A{BcA{As@eAiAeB_AuAIKuAyBoAoBqAwBm@_AS[w@mAu@mAg@w@]m@CCIMKQGKS[i@w@cA_BcBgCg@u@]k@KOyA_C}@wA_AyAaA_BGIqAwBcA_BoB_DKQU_@W_@yAaCKQEIkAiBQYS[y@qAw@oAg@y@eAaBq@gAAAg@{@MQIMACAC[i@KSMUWk@IQo@sASi@Si@KWSo@[aAGUI[Mg@I[GUMm@[_BKo@Km@CWE[CMOqASyB_@gDU{Bc@yEYuCc@oEMqAaAsJk@uFO}ACQMoAC[[cDMkAQ_BAMC[i@mFMkAMiAKu@OiAGc@[qB_@sBa@cB{AkGWy@k@mBWy@Su@g@aBm@qB[cAsAoEs@cCo@yBCI_@oAGQW}@c@wASs@i@gBOe@k@iBoB{GK[[eAIWAACIg@eBm@uBsBaHkA{Du@_CMe@Y_ACGYaAy@mCiA}Da@uAUc@i@wB_A}C?Aq@yBk@kBW_ACGOg@[eA]gAe@aB_@mAg@yAUq@u@kBMYQc@ISo@sAIOIQAAc@}@We@A?IQi@}@e@u@a@q@IKo@}@GKY_@EGy@oAQS}@cACCCCCCEGMMg@i@w@w@SSQQiA_AgAaA{@q@aAq@YSu@e@_@WQKKG_@UKGa@Ug@YECcAg@uAo@SIWK_Bo@sAg@eBi@iA[}A_@cAUiAUWEg@I}AS}BWa@GkBS_CWa@Ec@GmCY_@EmFm@_CWMAeAKeAMkAMIAUCi@Gm@GmAOgAO]Ea@Ek@GeAOiBUKCSEe@KKGiCq@a@M{GiBGC[MA?_A_@]OiAe@{Au@cB}@uBoAiAw@wA_AeAu@kB{A}@w@e@c@c@_@SSyB{BkAqAkAuAeBwBg@q@mB_CUYAAkAwAAAW]a@g@a@i@GG}@iAcC}CKMIK_@e@KMa@g@c@g@gCaD{BqCUYEEm@u@UYEGaAmAIKMQwBkCkA{AuA_BMQoF{GoCgD_I}J_AiAq@y@cEcFCEq@{@iAyACE_BqByBqC}EcGeC{Cq@{@CCiCaD{@eAW]a@g@wAeB{@aAu@}@y@{@IIq@s@iCaC_@YAAiAy@w@k@y@i@{CoB]UYQoGaE{@i@i@_@e@Yg@[sA}@m@a@u@e@y@g@II]Uq@c@qBoASMu@g@ECuA}@yAaAECYQECyAaAYQkBmAk@_@_BeA[U_@Uw@i@{@i@yByAWQaBeACC[QCCsCiBwA_Aa@Wk@_@gAs@EC}AcAk@_@iBeAkAu@q@a@]SYQaAm@_@UQMiAq@}BuAyBsA}A_AyBsAWOqEoCKG_BeAYOa@YwBoAYQa@U}@k@_@Sy@g@CAe@[]UwCkB}CsBoBoAu@e@]U_C_BUO{@k@_@We@Y{AcAUOkD_CeHuEuCmBs@g@ECeAs@kAw@EC_@UcAu@q@e@WOAAu@e@i@_@YQm@_@q@e@YQc@WuCmBmGgECA_BeAiD{B{AaAgEsCm@a@sA_Ac@Y{AaAeAy@KGEEUSEEi@c@OMSUEE[Y[YCCqCwCgCkCqAuAEESUEECCY[OO_@c@}@_Ao@o@IIWUs@s@}@y@c@a@i@e@[YEEMKi@g@w@s@[Y[Y{@u@AAw@q@?AUS_Aw@OK_@Wi@_@UOuB{Aw@i@MKWQs@i@qA_As@m@q@k@w@u@OQKKkBuBQUe@g@}AiBY[W[EESUCEWYm@s@SS_AeAKOQSGGcAkAIIIKCEKKY[Y]wAaBmAuAgBqBgBsBmAuA{@_Ak@q@s@y@Y[kAuAA?EGSUgBqBsCeDy@_AEGyEoF}DsE]a@mGiH_AeAgBsBEESUY]eBqBmAuA{CmD_@c@{@_AoCaD}DqEe@e@m@u@o@s@e@k@MMW[WYUYEEoEeFoB{BKMSUs@w@o@q@CCOSUUg@o@c@g@WWGIuDkE[_@m@q@_@c@g@k@sCcDq@w@}CoDUYAAIGACEEGI[]wAaBMOIIOSaCoCGGUWo@s@sBcCq@u@o@w@i@i@kAwAsBaCQQEGA?UY]a@mBuBSUsA}A{@_A{@aA}AeBCEQScCuCu@}@q@y@e@i@[]MMKOMMAAKMY]KIEGc@g@GIGGKKMQ_BiB}CmDmEeFoEeF{BiCKMi@m@u@}@i@m@}AgB_CoCw@{@]a@mBwBaBkBs@y@]_@}BkCq@y@KMMOY[UWq@w@Y]Y[WYACs@y@Y[UW]a@q@w@[]kAuAmAuAQSGIMOu@y@eAmAiBuBi@m@wBgCs@y@i@i@s@y@mAuAACkAqAq@y@OOc@i@EEgAoAs@y@MOAAyCiDwAcBg@i@W[{AeBs@y@aCoCgE}E_@c@qA{AoAyA_@c@]a@s@y@i@k@mAwA_DoDq@w@GGMQqAyAGGaAiAaCoCEGa@e@wAaB_@c@OQCCSWEEW[m@s@W]Y]KKMOEESWkAuAQSa@e@UW]a@kAwAWYoAyA?A]_@eAmACAW]KKi@o@_AiA[]GIa@c@QUY]UWMOKMu@}@oB_Ci@o@a@e@_AiAUWu@{@iHsI_@a@mAyAcBqBY]Y_@sBaCaGaH{BiC]a@QUY]UWOSY]Y]MOEGm@u@W[o@y@CCk@w@[c@GKc@o@i@w@GIACACU[qAoBc@q@k@{@oAoBY_@W_@]g@]g@Wc@KQy@mAeCuDs@gAkA_BCEa@k@Ya@Ua@CGa@o@GIMS}BmDaAwAaEiGk@w@MUOU"
                     },
                     "start_location" : {
                        "lat" : 29.435113,
                        "lng" : -98.4934284
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 250
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 29.87916,
                        "lng" : -97.92527559999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e205\u003c/b\u003e toward \u003cb\u003eTX-80 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWimberley\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLuling\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eFarm to Market Rd 12 W\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "epjuDpmutQAKAGGMWc@IMM[]q@KUc@}@g@aAWi@]w@CGEO"
                     },
                     "start_location" : {
                        "lat" : 29.8779498,
                        "lng" : -97.92745269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 453
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 29.8818252,
                        "lng" : -97.9217273
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eN Interstate 35 Frontage Rd\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "wwjuD~_utQOUo@}@g@u@]e@]m@Yg@OUGKc@m@S[q@gAEGc@m@KQ[a@u@cAEGgAuA"
                     },
                     "start_location" : {
                        "lat" : 29.87916,
                        "lng" : -97.92527559999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 768
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 29.8788837,
                        "lng" : -97.9269201
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIH 35 S\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "mhkuDxittQUGICIAG?G@I@IBEBIFW^o@`AU^ERAN?@@R?HAX\\ZTTVV~@|@`@`@RTh@f@`A`AVVp@p@j@j@b@b@BBtEbFnBzB"
                     },
                     "start_location" : {
                        "lat" : 29.8818252,
                        "lng" : -97.9217273
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1907
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 29.8673286,
                        "lng" : -97.9414551
                     },
                     "html_instructions" : "Take the ramp on the \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eI-35 S\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "_vjuDfjutQPDD@BDHFVXp@t@?@`@d@VZHJFJFDDBPDbCpDDFHLv@lAv@jA^j@|@pA~@xAf@r@bA`BRX~BfDjEvG|AfCLTLRd@j@fA`BtArB^j@LPFJvChEz@lA~BvCt@|@RTX\\RVXZHHrAbB^`@FF|@dAh@n@dAhAl@r@"
                     },
                     "start_location" : {
                        "lat" : 29.8788837,
                        "lng" : -97.9269201
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 276
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 29.8657648,
                        "lng" : -97.9436408
                     },
                     "html_instructions" : "Take exit \u003cb\u003e202\u003c/b\u003e toward \u003cb\u003eWonder World Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eFarm to Market Rd 3407\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ymhuDbextQBL@F@DBF^f@@@n@|@b@l@PVX^LRpBnCBD@D@BBL"
                     },
                     "start_location" : {
                        "lat" : 29.8673286,
                        "lng" : -97.9414551
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1299
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 81
                     },
                     "end_location" : {
                        "lat" : 29.8574234,
                        "lng" : -97.9530666
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eIH 35 S\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_dhuDvrxtQfApAdAjAFJX\\Z^l@t@p@x@l@r@x@|@f@n@fAnArA|AfBvBt@|@^b@`@d@b@f@@@LNHJBDLLNP`HhIVZ|@dAz@bAdAlA@Bl@l@VVLPv@|@RVZ^BB^`@NR"
                     },
                     "start_location" : {
                        "lat" : 29.8657648,
                        "lng" : -97.9436408
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 640
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 29.8605016,
                        "lng" : -97.94862929999999
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Interstate 35 Frontage Rd\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "{ofuDtmztQJBD@B?HBHAFA@ANGDEDE@ABEBEBE@C?A?E@E?E?IAKAMeBkBeAkACCeAoA{@aAMQOOEG_AiAc@k@Y[AA}@gAW[SUo@s@UU]a@a@e@"
                     },
                     "start_location" : {
                        "lat" : 29.8574234,
                        "lng" : -97.9530666
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "50.3 km",
                        "value" : 50299
                     },
                     "duration" : {
                        "text" : "30 mins",
                        "value" : 1783
                     },
                     "end_location" : {
                        "lat" : 30.2643175,
                        "lng" : -97.7350768
                     },
                     "html_instructions" : "Take the ramp on the \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eI-35 N\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "ccguD|qytQ[OECECAACCUWQOGIYYy@w@IKMMAAY[WYAA[[kAuAMMKGQGi@o@a@e@_AiAUWu@{@iHsI_@a@mAyAcBqBY]Y_@sBaCaGaH{BiC]a@QUY]UWOSY]Y]MOEGm@u@W[o@y@CCk@w@[c@GKc@o@i@w@GIACACU[qAoBc@q@k@{@oAoBY_@W_@]g@]g@Wc@KQy@mAeCuDs@gAkA_BCEa@k@Ya@Ua@CGa@o@GIMS}BmDaAwAaEiGk@w@MUOUw@iAaA{A}BoDiCqD_BwBY]y@cA}AiBgBsBkBmBq@o@o@o@wBqBSSy@s@gDwCm@g@m@i@iBaBmBcBQQ_@[[WwAqAa@_@c@_@e@a@sAkA}AsA[Ya@_@USkAeAuAmAMK{CkCEE_DqCyDcDg@c@c@a@MKMMQOYWCCYWKK{DkDgC_C_B{AEESSGE[YqAoA[YkAiAqCiCSSGESSkBaB}A}AWUkC_CuAsA_Ay@sCeCyBcB[U[Wk@_@QMuAcAECUO_Am@wAaAWOo@_@eBcAECsBiAECyBgAgCmAWKkCgAyAm@_CcAqBy@w@[oAi@kLyE_Bo@kEiBc@QA?a@OaIiDiDwAkCgA{Aq@mBu@s@[kDwAaMcFiBu@}IuDcP{Gm@Q_@Qs@YsEoBq@YwHaDuJ_EkBw@kEiBeAc@OGOGOGk@UiCgAw@]ICOGOGa@QoAi@mHyCaAc@iBu@qCiAkDyAgLyESIaAa@]QkGgCyCoAu@[WKqBy@iAe@oAi@YMq@Yk@Ui@SmAe@{@]g@Qg@Q}@YqAc@i@QqA_@}@Wi@O}@Q{@UyA]e@MoBa@YGyCi@?AgDe@YEkC[IAaBUcBSwH}@oDc@YGwAQeJkAcBSsAOgBUm@G{Ca@cBSk@IcAMiBU_AMaC[oDa@cBSuASQAaBU_AKwBUu@IG?c@EaAKg@EUCMAgBKc@EwCOaFWoAGk@AsAIe@AoBISAs@Ca@E{AG_AEG?kBIc@CSAO?GA_@A[CO?GAc@CC?_@Cc@CIAYAc@CgAEc@Ca@A[CG?]Ai@Cc@CSAI?EAy@CM?oAG_AGQA}@E_@AgAGa@COAy@GQAKAiAKy@IsBUuBUkAQ}ASEAoBQeBQyC[wBUGAcBUmAMeAK]EGAw@IkC[sC]wGw@gBYm@K}Ck@kCk@eDy@mDaAgA]{@Y_A[eDkAsBw@SKo@Wc@SsFiCCAaAe@uG}CaFeCqB_Ac@Sa@SkDcBu@_@c@W_@OWM_@QQI?AIE_@QoAo@mDaBiB}@yGeDIEWM_@QOG_By@OG_@Q_@SmAk@s@]q@[iCqACAuBcAk@WsAq@[OUKYOsBcAeAm@c@U]Si@[c@Wm@a@_@UQKKGe@YOKk@_@{AaA{AaAy@g@QMcAo@sBsAECsA{@IGeAq@mCcBg@]a@WoEsC]ScAq@}B{AiCaB}@k@sA}@s@c@eAq@qA{@YQMIq@c@_Am@GEUOeC_B{@i@SMeAs@qBoA{AaAcAo@{ByAk@_@{@i@eBiAe@Ym@_@iBgAc@WsAs@a@Wi@WSKa@Uu@]MIqB}@gBw@MEQIs@Y_@O_Bo@iBq@gBs@AACAGC_@OYKQG}D}AkHsCcE_B{@]yB}@u@Y_Bo@a@OEC_@O[MwB{@oCeAOGQGw@[ICUKIC{@]iAc@OGOGo@UyAm@{Am@qBu@_A_@UKQIyAm@aA]a@OOGOGwAk@a@OKESIaA_@KEUIKEu@[aA_@cBq@ICUKKE_FmBaDoAs@Y{CkAcG_CcCaAcC_A{D}AcDoAgCeAy@[{DwAYMa@Ma@OgCaAaA_@_Bo@eAa@QKoDuAc@OaAa@cE_BeBs@eGaCA?]OCAaA_@aDoAAA]MCAeEaBa@Q_Bm@AA]MAAeDqAcBq@_@OeCaAkLsEeBq@eDmAkAc@uCkA}B_Aa@OgBq@c@QsAg@cE_B]OCCA?_@OyEkBME}CmAiBu@kBw@wAo@WKkAi@aBw@c@SOIyEeCgIaE_GwCa@Ue@UAAA?e@Ug@WgCkAQIqFgCg@UGE{Aq@wAo@}Aq@aAa@}@a@UKs@[uAo@kB}@aCeAq@YcCaAcDsA?AeHiC_@MkBq@cBm@KEOGuCcAUKa@Mk@UUIm@Su@Yc@Oa@O_A]iE}AcBo@_@OaAa@a@OaFoBkDmA_@MAAa@Mc@Os@Wq@WQGMEcA_@QGMEw@YKEQGa@MiC{@OGMEMGi@SyAg@cA]iBo@ECQGOECC_AYcBi@a@Mu@WoAa@[KECk@QWIsEyAKE}@WqAa@kDeAiEoAUGKE{Bo@KE{Bo@uC{@WIcA[cA[gCw@y@UKEeCs@i@Qc@MA?{Bq@WIGAAA[ImCw@sAa@e@MYIAAOEMEeA[A?QGy@S_@MoAa@k@OA?a@MgCu@oCw@qDeAk@Qa@Ma@MmA]EAgCq@oBk@?AiA]QEkCw@A?GC}Bo@k@Qk@Q_@KcBe@A?wAa@q@Ss@SaBi@aAY}Bo@_@MEAICA?MCYIm@QaBe@wBm@{@Ye@OC?GCq@SiBg@eCs@EAsHqB]IiCq@QEiA[k@OeEeAcBc@wCw@}A_@ICGAg@OgD{@k@OmBi@a@KKCUGa@K}A_@ICEA[I{@SQEYIyDu@sBa@cEy@iB]sAYcB]ICo@KOEQCc@Ka@Io@MEAICIA{@QiAUaASC?MCWG_@GeASEAA?YICAgCg@SEi@K}Be@UCq@KOEa@IaASi@K]I_@Ka@I{@SKE}Aa@qEsAiDiAiA_@}@_@c@QwB{@cCiAkB{@yC{AiBeAIE[QAAUMKGOIUOe@Wg@Ym@]{BsAu@a@q@_@GEWMQKIEUOSMeAm@OIyAy@SMqAu@MI[QYOIG}@g@[SwBmA}BqA}A}@WOECwAy@UMmAs@YO]SiC{AKGGEgCyAWMg@Y]U}@g@oC}AcB_Ae@Y_Ai@c@W_@SOKGEUOGCGEIEOGMI_@S_@U]Sc@WYO_@SMIQKUMGE_@S]SIEg@[}@g@_@UKGGCg@[A?MI}@g@]USKo@_@SMEA_@U_@Qm@]o@_@aAk@gAo@]SKG]SA?AAg@W[S_B_AqBiA_CsAoEaCMIAA]SKI_@SeG_Em@e@cA}@m@g@{@m@WQ{@o@CCoBwAEEaD}BQMsB{AwB}AwB}AqC{B[WKIkAw@KIgAw@{@q@uB}AqCsB_@YAAQMAAc@[g@c@eIqG{@u@w@m@w@m@]U[WYS]WcEaDe@]CCyC{BuB}AcFyDsAaAwAcAkCeBaDoBqDqBOKo@[MG_Ae@gAg@a@Su@_@gAk@}EkCOI{EkC{BmAkAm@_CoAIEc@Wy@a@ECUKAAA?CAAAQIECMGCAAAKG_@Q_@Qa@SAAWMA?CA[OCAIECAAAm@[GCCAAACAGCAA]QCCA?a@SQKA?AAECCAeBaA}@c@}@c@A?]SoAk@k@YaBy@QGSKICg@UUK[OOGo@[a@QIEEAOIIEEAQIoB{@iAg@eBy@_Ae@UKmB_Ak@UiCmAqAm@gAg@uCyAk@[o@[GEw@c@i@Yu@]AAo@[g@Wo@[_Ai@i@W}A{@cAg@w@c@mAm@o@]CCw@a@_@SYOICsFiC_Ag@{GuCu@a@_Ae@a@S}@e@m@]MGSKKEq@]MGSKKG_@Q_@SICc@UQI_@S_Ac@UKiAk@g@UWO_@S_Ae@oAo@_Ae@_G{C_@S_@QYOe@U[QWMaBy@ECCAYOeCmAoAm@MGgAa@i@S_@OWIs@O}@OWG[COCeAGU?_@Ak@@W?G@u@BmCZI@eBRqALGBC?A?A@I@K@{@NI@kANmAJmBTWDI@I@SDSBk@Hm@HKB{@J{@L{@JWDG@]DC?e@FC@i@D[DwAR{@J]DI@UDa@Fo@HoD^UB_AJQ@E@]BA?u@HgBP[Bs@Fu@DE?]@G?Y@A?C?]?g@?[?yAEYAk@ESC]EQAi@I[GqAUeAUkD{@y@QCAUEsA[mBe@kBg@WGkA]k@QcBa@}@U"
                     },
                     "start_location" : {
                        "lat" : 29.8605016,
                        "lng" : -97.94862929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 30.2654039,
                        "lng" : -97.73424949999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e234C\u003c/b\u003e toward \u003cb\u003e6th St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003e12th St\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "__vwDf{osQEGEGGEMGKEKGOGOIAAOIMI]UIESOAAIEGEEC?AGQ"
                     },
                     "start_location" : {
                        "lat" : 30.2643175,
                        "lng" : -97.7350768
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 30.2656522,
                        "lng" : -97.73417339999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eN Interstate 35 Frontage Rd\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "wevwD`vosQq@O"
                     },
                     "start_location" : {
                        "lat" : 30.2654039,
                        "lng" : -97.73424949999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 872
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 30.26806669999999,
                        "lng" : -97.7428151
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eE 6th St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "igvwDpuosQUjAY~A[fBCLEREXIl@CR{@hEe@bCUnAy@xEOv@c@tBKf@Mv@Kf@_@tBUhACLIf@I\\Qz@Mp@"
                     },
                     "start_location" : {
                        "lat" : 30.2656522,
                        "lng" : -97.73417339999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 104
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 30.2671716,
                        "lng" : -97.74313869999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCongress Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mvvwDrkqsQb@JjBf@b@J"
                     },
                     "start_location" : {
                        "lat" : 30.26806669999999,
                        "lng" : -97.7428151
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 28.8155506,
                        "lng" : -96.9257054
                     },
                     "step_index" : 15,
                     "step_interpolation" : 0.3147811482318925
                  },
                  {
                     "location" : {
                        "lat" : 29.4388698,
                        "lng" : -98.47789469999999
                     },
                     "step_index" : 35,
                     "step_interpolation" : 0.9209587154198923
                  },
                  {
                     "location" : {
                        "lat" : 29.8694273,
                        "lng" : -97.9391121
                     },
                     "step_index" : 45,
                     "step_interpolation" : 0.8296677781551318
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "uqstDh|aeQpZzDlVrQ|\\vV~kArm@rRjd@~Dn}ApC`~BhHnuEzPxaCtDnq@pXl]xeBbsBxtAd_B|uDjtDhdDlpDxeAlmAriAjbAzoB`tBb|AxqCtfArpBz]ddBxw@`tGncAbgD|w@h~C~DfqGuMtvBjI`wAb|Cd~Fh`Apn@by@fwBhvCjyGjtCxxFbmEdfI``Fp}BpuBnaD|aD~_AnwBj[zcDxv@rz@buAd`D~jGjZriAjb@~S~t@prAb~@llBlkAjc@tx@hHxf@~Hls@dv@h]`{CpNrrDtaCtdEt]jhAti@ff@lfBfdDnLvoBlz@z|ArnA`h@lqFj}Jtw@lrBpKvoAhhA~|AdbAzkBnvC~sHveAvjCnE|~Blm@jlBl}@fu@lz@xt@hPdn@d\\h}AzjAbfBz{BjkFlqBlnFxjA~iDv|AleCxaDbxHfYrf@vfB~xAltAdqA~FfI|DwEeh@_c@ssAikAflAljAri@rj@{|AhmBweBbrBugAlyAc[bn@^vr@rHthCjVfy@SjOeWbZkmA~tAcu@lz@yaCdnC_yAzdBcvEhsEsuBbhB{vA~p@ewBza@cpAfu@_qB|hAks@b`B_pBxiCo}BdtEeXtiBy_@jzBxEbTvKdFd`@vOcQnfAkOb{BQhqBfUpo@jNlRe}A~cC}mCzqEm~Dx|EivE`|Aon@pd@j@~rAe[pu@eSjyBkv@|q@yYbn@}uAxfBqoCtgDwbAnqHme@jhDo[ffHeRvbEt^llChf@`kDztBl}N`vArxJxe@xiFg@hw@s`@jd@gg@hjBuo@d`Dj@zbBenCdyCu|@fmAs|A~nA{xC|vAc_ClgAq~AtgAqQpoBwDfyCzAn}Gsx@hvHi[v{AmEpcAiBdzAug@~bCgv@htEmo@toCqPxoB}fC~AmuAnAi`Afp@yr@njAeLj^zfAr|BtXht@|C~jAx@fiCmHts@jQhb@`MzJoOyQsMem@`Ja`A{CmxCuNs{@qj@clAq]{~@k\\cVqeBcp@wdCyUseCa\\{gBoo@kiBw{Do}@{jB_{AqjBgcC{cGocAguAepA}yB{oCeuGihC_oFm|AiaCwi@q}C{}@apC_`@e[qaAyOy`Acb@cn@iv@mpCqlC_iFsqDmjE}yEchEu~EowCc~Dt~@hyAjqAt`BfFz@eYe[avAihBw_CkdCsbAct@wbDisA}uAuk@iyAaW{kBwNc{@}HkfBok@gyB}nAklGwmCwdHkrCiuFo{Ag_Baj@}nAqs@ovEyzCcvAar@icB_o@_hA`K{f@mMiQrm@hCjE"
         },
         "summary" : "US-59 S and US-87 N",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
