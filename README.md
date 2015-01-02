quiz-
=====

sample

index.html
===========

<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=default-width; user-scalable=no" />
		<title>HTML5 Test Prep</title>
		<script src="js/cordova-1.7.0.js" type="text/javascript"></script>
		<script src="js/jquery-1.8.2.js" type="text/javascript"></script>
		<script src="js/jquery-ui.js" type="text/javascript"></script>
		<script src="js/jquery.ui.touch-punch.js" type="text/javascript"></script>
		<script src="js/jquery.mobile-1.2.0.js" type="text/javascript"></script>
		<script src="js/swipe.js" type="text/javascript"></script>
		<script src="js/jquery.countdown.js" type="text/javascript"></script>
		<script src="js/vkeypad.js" type="text/javascript"></script>
		<script src="js/sciencepst.js" type="text/javascript"></script>
		<script src="js/calculator.js" type="text/javascript"></script>
		<script type="text/javascript" src="js/ready.js"></script>
		<script type="text/javascript" src="js/router.js"></script>
		<script src="js/calAct.js" type="text/javascript"></script>
		<script src="js/iscroll.js" type="text/javascript"></script>    
		<link rel="stylesheet" href="css/jquery.mobile-1.2.0.css" type="text/css"/>
		<link rel="stylesheet" href="css/style.css" type="text/css" />
		<link href="css/jquery.countdown.css" rel="stylesheet" type="text/css"/>
		<link href="css/scrollbar.css" rel="stylesheet" type="text/css"/>
		<link href="css/vkeypad.css" rel="stylesheet" type="text/css"/>
		<link href="css/calculator.css" rel="stylesheet" type="text/css"/>
		<style type="text/css">
			body 
			{
				left:0px;
				top:0px;
			}
			.swipe ul {
			    margin:0px;
			    padding:0px;   
			}
			.ui-page
			{
				min-height:100%;
				-webkit-backface-visibility:visible;
			}
			#inp1{
				width: 70px;
				margin-top: 3%;
			}
			#desTxt{
				text-align: left !important;
			}
		</style>
	</head>
<body>
<!-------------------------------------iPad Index Page Start------------------------------------->
<div id="index" data-role="page" data-position="fixed">
  <!--<div class="contentPanel" id="indexPageContainer">-->
  <div id="indexPageContainer">
	<div class="mainhome_go" onClick="window.location.href = '../index.html'"></div>
  <div class="contentPanel">
    <center>
      <!--Middle "Preparing for Standardized TESTS" logo-->
      <div id="indexLogo"><img src="images/logo_big.png" width="300px" alt=""/></div>
      <!--Middle "Preparing for Standardized TESTS" logo-->
      <!--Test Numbers Start-->
        <div id="indexPageTestIcons"><a href="#test1_1" class="btn b1"><span>Easy</span></a><br/> <br/><br/><a href="#test2_1" class="btn b2"><span>Medium</span></a><br/><br/><br/> <a href="#test3_1" class="btn b3"><span>Harder</span></a><br/><br/><br/> <a href="#test4_1" onMouseDown="imgDown('four');" class="btn b4"><span>Hardest</span></a></div>
 </div>
</div>
</div>
<!-------------------------------------iPad Index Page Start------------------------------------->
<div id="blocker">

</div>
		<div id="feedback">
		<span id="fed_correct">Correct</span><span id="cor_ans">5</span>
		<span id="fed_incorrect">Incorrect</span><span id="wro_ans">0</span>
		<div id="close_feed" onclick="block_close();"></div>
	</div>
<!------------------------------------- Test 1 Question 1 Start ------------------------------------->
<div id="test1_1" data-role="page" style="background-color:#3c006a;">
  <div class="contentPanel testPageContainer">
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div align="right" class="testPageLogo"></div>
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div class="testPageTop">
      <div id="testquestion1"><span class="testPageWhiteQuestionNo"> <span id="que_number"></span></span><span class="testPageWhiteAlpha"> </span><span style="padding-left:2em;" class="testPageWhiteQuestionNo"></span></div>
      <div style="margin-top:12px;"></div>
      <div class="testPageWhiteBoxTop">
        <!--Test Question Start-->
        <div class="normalTimes testPageWhiteBoxIndent">
          <div id="scroll1" class="wrapper">
            <div class="scroller">
            </div>
          </div>
        </div>
      </div>

      <div id='slider' class='swipe testPageGreyAnswerBoxWidth' style="color:#000000;overflow: visible !important;">
      <ul>
      <li style='display:block;'>
      <!--Answer Panel Start-->
	  <div id="answerchoice1">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>1. What is the HTML feature that divides a web page into two or more scrollable parts?</strong></div>
          <form name="q1" id="q1">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;Split Page</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;Form</label>
              <input type="radio" name="r1" id="r3" value="answer"/>
              <label for="r3" data-theme="c" class="ans1 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;Frame</label>
              <input type="radio" name="r1" id="r4" value=""/>
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;Table</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input class="submitWidth" type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q1, 'correctAns1');"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice2" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>2. 	Choose the correct HTML tag for the largest heading?</strong></div>
          <form name="q2" id="q2">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;&lt;head&gt;</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans2 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;&lt;h1&gt; </label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;&lt;h6&gt;</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;&lt;heading&gt;</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q2, 'correctAns2');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div> 
      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice3" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>3. Which HTML5 element is used to specify a footer for a document or section?</strong></div>
          <form name="q3" id="q3">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;&lt;bottom&gt;</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;&lt;section&gt;</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;&lt;top&gt;</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans3 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;&lt;footer&gt;</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q3, 'correctAns3');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice4" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>4. What is the correct HTML5 element for playing video files?</strong></div>
          <form name="q4" id="q4">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;&lt;audio&gt;</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;&lt;movie&gt;</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;&lt;media&gt;</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans4 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;&lt;video&gt;</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q4, 'correctAns4');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

       
      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice5" style="display:none;">
       

 <div class="testpageWidth">

	 <div class="normalTimes" style="margin-top:-14px;margin-left:23px; text-indent:-23px;"><table style="width:98%"><tr><td style="float: left;width:78%;font-size: 14pt;"><strong>5. What is the latest version of HTML ?<span style="font-size:12pt">Focus the input box and Type user answer.</span></strong></td><td style="float:left;width: 14%;"><input type="text" class="numTxt"  readonly ="readonly" id="inp1"/></td></tr></table></div>
          <form name="q5" id="q5">
            <fieldset data-role="controlgroup">
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q5, 'correctAns5');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
	
      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice6" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>6. The &lt;canvas&gt; element in HTML5 is used to?</strong></div>
          <form name="q6" id="q6">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;manipulate data in MySQL</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;display database records.</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans6 radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;draw graphics.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;create draggable elements
.</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q6, 'correctAns6');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice7" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>7. Which built-in HTML5 object is used to draw on the canvas?</strong></div>
          <form name="q7" id="q7">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;getContent</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans7 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;getContext</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;getCanvas</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;getGraphics</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q7, 'correctAns7');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice8" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>8. In HTML5, which attribute is used to specify that an input field must be filled out?</strong></div>
          <form name="q8" id="q8">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;placeholder</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans8 radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;required</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;validate</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;formvalidate</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q8, 'correctAns8');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice9" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>9. Which input type defines a slider control?</strong></div>
          <form name="q9" id="q9">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;search</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;slider</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans9 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;range</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp; controls</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q9, 'correctAns9');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
      <li style='display:none;'>
      <div id="answerchoice10" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>10. Which of the following elements is no longer supported in HTML5?</strong></div>
          <form name="q10" id="q10">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans10 radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;&lt;acronym&gt;</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;&lt;cite&gt;</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;&lt;base&gt;</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;&lt;abbr&gt;</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q10, 'correctAns10');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
      </li>
      <!--Answer Panel End-->
      </ul>
      <!--Answer Panel End-->
  </div>
  </div>

  <!--Navigation-->
  <div class="submit_icon" id="sub_1" onclick="submit_1();">SUBMIT</div>
  
  <div id="feed">
	<img src="images/tick.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="correct_ans">5</span>
	<img src="images/wrong.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="wrong_ans">a</span>
  </div>
  <div class="home_go" onClick="chkTimer('#index');"></div>
  <div class="calc-container"></div>
  <div align="center" data-role="footer" data-theme="f" class="testFooterNavAlign" id="question1" style="display:block;">
    <table cellpadding="0" cellspacing="0" class="testFooter">
      <tr>
        <!--<td class="testMenu"><a href="#index" onClick="chkTimer('#index');" data-transition="slide" data-reverse="true" data-role="button" data-inline="true" data-icon="home" data-theme="c"><span class="footerBlackText">Menu<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <!--<td class="testBack"><a id="Back_But" href="#test1_2" onClick="goBack();" data-role="button" data-inline="true" data-transition="none" data-icon="back" data-iconpos="left" data-theme="c" data-back="false" style="visibility:hidden;"><div class="go_prev" onClick="goBack();"></div></a></td>-->
       <!--<td class="testNext"><a href="#test1_2" onClick="chkquestime();" data-role="button" data-inline="true" data-transition="none" data-icon="forward" data-iconpos="right" data-theme="c" data-back="false"><span class="footerBlackText">Next<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <div class="foot_ques"><span id="simple_Q">1</span><span> / 5</span></div>
	<div class="go_prev testBack" id="Back_But" style="visibility:hidden;" onClick="goBack();"></div>
	<div class="go_next testNext" id="next1" onClick="chkquestime();"></div>
	
      </tr>
    </table>
  </div>  </div>
  <!--Navigation-->
</div>
<!------------------------------------- Test 1 Question 1 End ------------------------------------->

<!------------------------------------- Test 2 Question 1 Start -------------------------------------> 
<div id="test2_1" data-role="page" style="background-color:#3c006a;">
  <div class="contentPanel testPageContainer">
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div align="right" class="testPageLogo"></div>
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div class="testPageTop">
      <div id="testquestion1"><span class="testPageWhiteQuestionNo"><span id="que_number1"></span></span><span class="testPageWhiteAlpha"> </span><span style="padding-left:2em;" class="testPageWhiteQuestionNo"></span></div>
      <div style="margin-top:12px;"></div>
      <div class="testPageWhiteBoxTop">
        <!--Test Question Start-->
        <div class="normalTimes testPageWhiteBoxIndent">
          <div id="scroll2" class="wrapper">
            <div class="scroller">
              </div>
          </div>
        </div>
      </div>
      <div id='slider1' class='swipe testPageGreyAnswerBoxWidth' style="color:#000000;">
      <ul>
      <li style='display:block;'>
      <!--Answer Panel Start-->
      <div id="answerchoise1" style="height:450px;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>1. How can you open a link in its own unique new window?</strong></div>
        <form name="q11" id="q11">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;
target=_new</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;target=new</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans11 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;target=_blank</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;target=_window</label>
            </fieldset>
        </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q11, 'correctAns11');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoise2" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>2. How to insert an e-mail link?</strong></div>
          <form name="q12" id="q12">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;Add 'mail:'</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans12 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;Add 'mailto:'</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;Add 'email:'</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;Just like any other link</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q12, 'correctAns12');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoise3" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>3. Which attribute is NOT valid for the &lt;BODY&gt; tag?</strong></div>
          <form name="q13" id="q13">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans13 radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;color</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;background</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;vlink</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;leftmargin</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q13, 'correctAns13');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoise4" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>4. Which is NOT a valid extension for HTML files ?</strong></div>
          <form name="q14" id="q14">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="" />
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;htm</label>
              <input type="radio" name="r1" id="r2" value="" />
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;shtml</label>
              <input type="radio" name="r1" id="r3" value="answer" />
              <label for="r3" data-theme="c" class="ans14 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;xml</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;phtml</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q14, 'correctAns14');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
          <li style='display:none;'>
      <div id="answerchoise5" style="display:none;">
        <div class="testpageWidth">

        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>5. How can you make a list that lists the items with numbers?</strong></div>
          <form name="q15" id="q15">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="" />
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;&lt;list&gt;</label>
              <input type="radio" name="r1" id="r2" value="" />
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;&lt;ul&gt;</label>
              <input type="radio" name="r1" id="r3" value="" />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;&lt;dl&gt;</label>
              <input type="radio" name="r1" id="r4" value="answer" />
              <label for="r4" data-theme="c" class="ans15 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;&lt;ol&gt;</label>
            </fieldset>
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q15, 'correctAns15');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
          </li>
      <!--Answer Panel End-->
       </ul>
      <!--Answer Panel End-->
  </div>
  </div>

  <!--Navigation-->

  <div class="submit_icon" id="sub_2" onclick="submit_2();">SUBMIT</div>
  <div id="feed2">
	<img src="images/tick.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="correct_ans2">5</span>
	<img src="images/wrong.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="wrong_ans2">a</span>
  </div>
  <div class="home_go" onClick="chkTimer('#index');"></div>
  <div class="calc-container"></div>
  <div align="center" data-role="footer" data-theme="f" class="testFooterNavAlign" id="question1" style="display:block;">
    <table cellpadding="0" cellspacing="0" class="testFooter">
      <tr>
        <!--<td class="testMenu"><a href="#index" onClick="chkTimer('#index');" data-back="true" data-role="button" data-inline="true" data-transition="none" data-icon="home" data-theme="c"><span class="footerBlackText">Menu<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <!--<td class="testBack"><a id="Back_But1" href="#test2_2" onClick="goBack1();" data-role="button" data-inline="true" data-transition="none" data-icon="back" data-iconpos="left" data-theme="c" data-back="false" style="visibility:hidden;"><span class="footerBlackText">Back<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
       <!--<td class="testNext"><a href="#test2_2" onClick="chkquestime1();" data-role="button" data-inline="true" data-transition="none" data-icon="forward" data-iconpos="right" data-theme="c" data-back="false"><span class="footerBlackText">Next<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
       <div class="foot_ques"><span id="medium_Q">1</span> / 5</div>
	<div class="go_prev testBack" id="Back_But1" style="visibility:hidden;" onClick="goBack1();"></div>
	<div class="go_next testNext" id="next2" onClick="chkquestime1();"></div>
      </tr>
    </table>
  </div>  </div>
  <!--Navigation-->
</div>
<!------------------------------------- Test 2 Question 1 End -------------------------------------> 
<!------------------------------------- Test 3 Question 1 Start ---------------------------------->
<div id="test3_1" data-role="page" style="background-color:#3c006a;">
  <div class="contentPanel testPageContainer">
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div align="right" class="testPageLogo"></div>
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div class="testPageTop">
      <div id="testquestion1"><span class="testPageWhiteQuestionNo"><span id="que_number2"></span></span><span class="testPageWhiteAlpha"></span><span style="padding-left:2em;" class="testPageWhiteQuestionNo"></span></div>
      <div style="margin-top:12px;"></div>
      <div class="testPageWhiteBoxTop">
        <!--Test Question Start-->
        <div class="normalTimes testPageWhiteBoxIndent">
          <div id="scroll3" class="wrapper">
            <div class="scroller">
            </div>
          </div>
        </div>
      </div>
      <!--Answer Panel Start-->
    <div id='slider2' class='swipe testPageGreyAnswerBoxWidth' style="color:#000000;overflow: visible !important;">
     <ul>
      <li style='display:block;'>
      <div id="answerchoose1">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-top:-14px;margin-left:23px; text-indent:-23px;">
			
			<table style="width:98%"><tr><td style="float: left;width:78%;font-size: 14pt;"><strong>1. which is used to create web page? <span style="font-size:12pt">Drag the option and drop in the box.</span></strong></td><td style="float:left;width: 14%;"><div class="dropDiv"></div></td></tr></table>
	</div>
		  
		  
		  
		  
            <div style="width:85%; position: relative; padding-left: 30px;margin-top: 13%;">
		<div class="drgDiv">DTD</div></br>
		<div class="drgDiv">JVM</div></br>
		<div class="drgDiv">HTML</div></br>
		<div class="drgDiv">C</div>
          </div>
        </div>
              <div class="Banner_Timer">
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose2" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>2. Which of the following is not property of &lt;video&gt; element?</strong></div>
          <form name="q30" id="q30">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans30 radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;abort</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;currentTime </label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;currentSrc</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;videoWidth</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q30, 'correctAns30');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose3" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>3. How to make an element draggable . Write syntax?</strong>
		
	</div>
	<div class="audio_top" style="position:absolute;  left:20%;" onclick="AudioState()">
			<img src="images/audioICON.png" width="50px" height="50px">
		</div>
          <form name="q31" id="q31">
            <fieldset data-role="controlgroup">
             <textarea id="desTxt" placeholder="Type Your comment here.."></textarea>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns31" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">B is the best answer</span> because Figure 1 shows that ST1 is an original stem cell producing a stem cell just like itself.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson1_p1" onClick="chkTimer('#lesson1_p1');" style="color:#0000FF"><span class="linkColor">Find Data and Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose4" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-top:-14px;margin-left:23px; text-indent:-23px;">
		  
		  <table style="width:98%"><tr><td style="float: left;width:78%;font-size: 14pt;"><strong>4. Which one is not a value for Position Attribute?<span style="font-size:12pt">Drag the option and drop in the box.</span> </strong></td><td style="float:left;width: 14%;"><div class="dropDiv1"></div></td></tr></table>
			
		  </div>
            <div style="width:85%; position: relative; padding-left: 30px;margin-top: 13%;">
		<div class="drgDiv1">Absolute</div></br>
		<div class="drgDiv1">Fixed</div></br>
		<div class="drgDiv1">Relative</div></br>
		<div class="drgDiv1">Dynamic</div>
          </div>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q32, 'correctAns32');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose5" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>5. Which method will use to get the dragged data?</strong></div>
          <form name="q33" id="q33">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;dataTransfer.getdata</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;dataTransfer.getdrag</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;dataTransfer.sedata</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans33 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;dataTransfer.gedata</label>
            </fieldset>
           
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q33, 'correctAns33');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose6" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>6. According to the passage, what was the first step researchers used to detect stem cells in an existing tumor?</strong></div>
          <form name="q34" id="q34">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;They dyed the stem cells and watched them reproduce.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong> &nbsp;They isolated individual cells and watched which ones acted in two ways.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong> &nbsp;They treated all the cells and watched which ones didn't die.</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans34 radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;They dyed tumor cells that resemble regular stem cells.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q34, 'correctAns34');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns34" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">J is the best answer</span> because the passage says this is what researchers did after identifying the cell to use. F is not correct because it includes more than one step and inaccurately describes the steps.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson6_p1" onClick="chkTimer('#lesson6_p1');" style="color:#0000FF"><span class="linkColor">Recognize Components of Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose7" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>7. According to the passage, how did researchers identify possible cancer stem cells?</strong></div>
          <form name="q35" id="q35">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;by dying them</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;by closely studying the tumors that disappeared</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;by treating a tumor with drugs and seeing which cells died</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans35 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;by seeing which cells "reseeded" a returning tumor</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q35, 'correctAns35');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns35" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">D is the best answer</span> because the passage calls these "possibly the hypothesized CSTs."</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson6_p1" onClick="chkTimer('#lesson6_p1');" style="color:#0000FF"><span class="linkColor">Recognize Components of Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose8" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>8. Which is a normal role of stem cells in the body?</strong></div>
          <form name="q36" id="q36">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans36 radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;repairing damage</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;seeding cancer</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;reproducing specialized cells</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;renewing cell lines</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q36, 'correctAns36');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns36" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">F is the best answer</span> because the passage says this is what stem cells do.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson1_p1" onClick="chkTimer('#lesson1_p1');" style="color:#0000FF"><span class="linkColor">Find Data and Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose9" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>9. Which is the best explanation of how the dye showed that stem cells were possibly at work?</strong></div>
          <form name="q37" id="q37">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;The medicine that killed rapidly dividing cells did not eradicate the dye from the first group of tumors.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;The dye infiltrated specialized cancer cells in the second group of tumors but not in the first group of tumors.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp; The stem cells in the second group of tumors all contained the dye from the first group.</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans37 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;The growing number of dyed cells in the second set of tumors behaved like stem cells in that they were self-renewing and differentiating.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q37, 'correctAns37');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns37" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">D is the best answer</span> because it covers both the appearance and the behavior of the possible stem cells.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson8_p1" onClick="chkTimer('#lesson8_p1');" style="color:#0000FF"><span class="linkColor">Evaluate Models.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose10" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>10. Which is one possible conclusion researchers could draw from these results regarding drug development?</strong></div>
          <form name="q38" id="q38">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;Drugs that target specialized cancer cells will inevitably fail to cure cancer.</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans38 radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;Researchers should try to develop drugs that target cancer stem cells.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;Preventing stem cells from reproducing is one way to reduce the number of specialized cancer cells.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;Drugs should not be developed if all they do is eradicate rapidly dividing cells.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q38, 'correctAns38');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose11" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>11. Why might scientists conclude that the surviving cells could be stem cells?</strong></div>
          <form name="q39" id="q39">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>A.</strong> &nbsp;The drug that kills CSPs did not kill them.</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans39 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;Tumor B came to include more cells like them, indicating that they were self-renewing.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;Only stem cells are able to give rise to CSPs in a tumor.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;They resemble the stem cells in normal human organs.</label>
            </fieldset>
           
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q39, 'correctAns39');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns39" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">B is the best answer</span> because it describes something that stem cells do; A and C do not accurately describe what happens, and D could refer to appearance rather than behavior.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson7_p1" onClick="chkTimer('#lesson7_p1');" style="color:#0000FF"><span class="linkColor">Match Data and Models to Hypotheses, Predictions, and Conclusions.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose12" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>12. What assumption underlies the use of dye in this experiment?</strong></div>
          <form name="q40" id="q40">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans40 radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;Cells that resemble stem cells are cancer stem cells.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;Only cancer stem cells would take up the particular kind of dye used in the experiment.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;The drugs that kill CSPs are known to avoid cells containing this particular dye.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;Dyes are an effective way of telling one kind of cell from another kind of cell.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q40, 'correctAns40');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns40" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">F is the best answer</span> because researchers did not know that the cells were CSTs. The third paragraph of the passage says that they resembled regular STs.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson8_p1" onClick="chkTimer('#lesson8_p1');" style="color:#0000FF"><span class="linkColor">Evaluate Models.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose13" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>13. Use the information in Figures 1 and 2 to decide what the dyed cells are probably doing in Tumor B.</strong></div>
          <form name="q41" id="q41">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>A.</strong> &nbsp;reproducing rapidly</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;differentiating into CSPs</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans41 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;self-renewing</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;dividing uncontrollably</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q41, 'correctAns41');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns41" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">C is the best answer</span> because Figure 1 shows the colored STs as self-renewing, not differentiating. </div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson2_p1" onClick="chkTimer('#lesson2_p1');" style="color:#0000FF"><span class="linkColor">Compare and Combine Data.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoose14" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>14. In a second experiment, researchers killed all the dyed cells in Tumor B. The tumor did not grow as large as Tumor A. What does this suggest about the cancer stem cell hypothesis?</strong></div>
          <form name="q42" id="q42">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;It suggests that the hypothesis is incorrect, because the alleged stem cells can be killed.</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans42 radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;It suggests that the hypothesis may be correct, because without the alleged stem cells, the tumor grew less rapidly.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;It suggests that the hypothesis is incomplete, because the slow growth in Tumor B could be explained by several other factors, such as the timing of the experiment.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;It suggests that the hypothesis is correct, because if the dyed cells survived the drug used to kill CSPs, they cannot be cancer stem cells.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q42, 'correctAns42');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <!--<div id="correctAns42" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">G is the best answer</span> because it accurately reflects the results. It is also best by the process of elimination: The passage does not say that stem cells cannot be killed, so F is incorrect; the passage does not contain enough information to support answer H; and J contradicts the hypothesis.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson9_p1" onClick="chkTimer('#lesson9_p1');" style="color:#0000FF"><span class="linkColor">Predict Using Models and Experimental Design.</span></a></div>
        </div>-->
      </div>
    </li>
</ul>
      <!--Answer Panel End-->
      
   </div>
  </div>

  <!--Navigation-->
    
  <div class="submit_icon" id="sub_3" onclick="submit_3();">SUBMIT</div>
  
  <div id="feed3">
	<img src="images/tick.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="correct_ans3">5</span>
	<img src="images/wrong.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="wrong_ans3">a</span>
  </div>
  <div class="home_go" onClick="chkTimer('#index');"></div>
  <div class="calc-container"></div>
  <div align="center" data-role="footer" data-theme="f" class="testFooterNavAlign" id="question1" style="display:block;">
    <table cellpadding="0" cellspacing="0" class="testFooter">
      <tr>
        <!--<td class="testMenu"><a href="#index" onClick="chkTimer('#index');" data-back="true" data-role="button" data-inline="true" data-transition="none" data-icon="home" data-theme="c"><span class="footerBlackText">Menu<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <!--<td class="testBack"><a id="Back_But2" href="#test3_2" onClick="goBack2();" data-role="button" data-inline="true" data-transition="none" data-icon="back" data-iconpos="left" data-theme="c" data-back="false" style="visibility:hidden;"><span class="footerBlackText">Back<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
      <!--<td class="testNext"><a href="#test2_2" onClick="chkquestime2();" data-role="button" data-inline="true" data-transition="none" data-icon="forward" data-iconpos="right" data-theme="c" data-back="false"><span class="footerBlackText">Next<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
      <div class="foot_ques"><span id="hard_Q">1</span> / 5</div>
	<div class="go_prev testBack" id="Back_But2" style="visibility:hidden;" onClick="goBack2();"></div>
	<div class="go_next testNext" id="next3" onClick="chkquestime2();"></div>
	
      </tr>
    </table>
  </div> </div>
  <!--Navigation-->
</div>
<!------------------------------------- Test 3 Question 1 End ------------------------------------->

<!------------------------------------- Test 4 Question 1 Start ---------------------------------->
<div id="test4_1" data-role="page" style="background-color:#3c006a;">
  <div class="contentPanel testPageContainer">
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div align="right" class="testPageLogo"></div>
    <!--Right "Preparing for Standardized TESTS" logo-->
    <div class="testPageTop">
      <div id="testquestion1"><span class="testPageWhiteQuestionNo"><span id="que_number3"></span></span><span class="testPageWhiteAlpha"></span><span style="padding-left:2em;" class="testPageWhiteQuestionNo"></span></div>
      <div style="margin-top:12px;"></div>
      <div class="testPageWhiteBoxTop">
        <!--Test Question Start-->
        <div class="normalTimes testPageWhiteBoxIndent">
          <div id="scroll4" class="wrapper">
            <div class="scroller">
            </div>
          </div>
        </div>
      </div>
      <!--Answer Panel Start-->
        <div id='slider3' class='swipe testPageGreyAnswerBoxWidth' style="color:#000000;overflow: visible !important;">
        <ul>
        <li style='display:block;'>
	   <div id="answerchoooe1">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>1. What is difference between session storage and local storage?</strong>
	
	</div>
	<div class="audio_top" style="position:absolute;left: 6%;" onclick="AudioState1()">
			<img src="images/audioICON.png" width="50px" height="50px">
	</div>
          <form name="q43" id="q43">
            <fieldset data-role="controlgroup">
              <textarea id="desTxt" placeholder="Type Your comment here.."></textarea>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
        </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe2" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>2. Which Two properties are used to hide contents?</strong></div>
          <form name="q44" id="q44">
            <fieldset data-role="controlgroup">
              <input type="checkbox" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans44 radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;visibility:hidden</label>
              <input type="checkbox" name="r11" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;visibility:none</label>
              <input type="checkbox" name="r12" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;display:none</label>
              <input type="checkbox" name="r13" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;display:hidden</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q44, 'correctAns44');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe3" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>3. What is the difference between sessionstorage, localstorage and Cookies?</strong>
	
	
	</div>
	<div class="audio_top" style="position:absolute; left: 20%;" onclick="AudioState2()">
			<img src="images/audioICON.png" width="50px" height="50px">
	</div>
          <form name="q45" id="q45">
            <fieldset data-role="controlgroup">
              <textarea id="desTxt" placeholder="Type Your comment here.."></textarea>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe4" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend2" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>4. What are the Two values supported for INPUT type attribute?</strong></div>
          <form name="q46" id="q46">
            <fieldset data-role="controlgroup">
              <input type="checkbox" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;week</label>
              <input type="checkbox" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="ans46 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;money</label>
              <input type="checkbox" name="r1" id="r3" value="answer"/>
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;month</label>
              <input type="checkbox" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;year</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q46, 'correctAns46');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns46" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">G is the best answer</span> because M1 can drop, which gives it force due to gravity.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson5_p1" onClick="chkTimer('#lesson5_p1');" style="color:#0000FF"><span class="linkColor">Interpret New Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe5" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes margin_extend1" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>5. Two Arributes supported for Audio Tag?</strong></div>
          <form name="q47" id="q47">
            <fieldset data-role="controlgroup">
              <input type="checkbox" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans47 radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;loop</label>
              <input type="checkbox" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;play</label>
              <input type="checkbox" name="r1" id="r3" value="answer"/>
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;muted</label>
              <input type="checkbox" name="r1" id="r4" value=""/>
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;pause</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q47, 'correctAns47');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe6" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>6. A pulley is a simple machine that either changes the magnitude of the force needed to lift an object or changes the direction of a force. According to Figure 1, how did the pulley function in this experiment?</strong></div>
          <form name="q48" id="q48">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans48 radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;It changed the direction in which force M1 pulled mass M2.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong> &nbsp;It reduced the amount of force M1 needed to lift mass M2.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong> &nbsp;It changed the direction in which force M2 resisted mass M1.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;It increased the force needed to lift mass M1.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q48, 'correctAns48');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns48" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">F is the best answer</span> because G and J concern lifting, which is not part of this experiment; H is invalid because M2 is not a force; and F makes sense with Figure 1.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson5_p1" onClick="chkTimer('#lesson5_p1');" style="color:#0000FF"><span class="linkColor">Interpret New Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe7" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>7. In terms of force and mass, what would happen if M2 were greater than M1?</strong></div>
          <form name="q49" id="q49">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;M1 would be pulled up toward the pulley because M2 would have greater force.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;M1 would not move because the mass would be greater than the force.</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans49 radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;M2 would not move because the mass would be greater than the force.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;The line connecting the two masses would go slack because M1 and M2 would have no force.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q49, 'correctAns49');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns49" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">C is the best answer</span> because as it drops, M1 is the force that pulls M2. If the mass of M2 were greater than the mass of M1, M1 could not drop. M2 would not move because there would not be enough force to overcome its inertia.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson9_p1" onClick="chkTimer('#lesson9_p1');" style="color:#0000FF"><span class="linkColor">Predict Using Models and Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe8" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>8. Did the results of Group A's experiment support the hypothesis? Why or why not?</strong></div>
          <form name="q50" id="q50">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;No, because increasing M1 caused times to go down, indicating a decrease in speed.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;No, Because increasing M1 caused times to go up, indicating a decrease in speed.</label>
              <input type="radio" name="r1" id="r3" value="answer"  />
              <label for="r3" data-theme="c" class="ans50 radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;Yes, because increasing M1 caused times to go down, indicating an increase in speed.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;Yes, because increasing M1 caused times to go down, indicating a decrease in speed.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q50, 'correctAns50');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns50" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">H is the best answer</span> because it matches the data in Table 1 and matches the hypothesis.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson7_p1" onClick="chkTimer('#lesson7_p1');" style="color:#0000FF"><span class="linkColor">Match Data and Models to Hypotheses, Predictions, and Conclusions.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe9" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>9. Which graph best represents the relationship between the mass and speed of M2?</strong></div>
        
          <form name="q51" id="q51">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>A.</strong> &nbsp;</label>
              <input type="radio" name="r1" id="r2" value="answer"/>
              <label for="r2" data-theme="c" class="ans51 radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;</label>
              <input type="radio" name="r1" id="r3" value=""/>
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;</label>
              <input type="radio" name="r1" id="r4" value=""/>
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q51, 'correctAns51');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns51" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">B is the best answer</span> because Table 2 shows that as M2 increases, time increases, meaning that the speed of M2 decreases.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson4_p1" onClick="chkTimer('#lesson4_p1');" style="color:#0000FF"><span class="linkColor">Represent Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe10" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>10. At one point in each experiment, M1 was 1.50 kg and M2 was 0.50 kg. The resulting speeds differed, however: times measured were 0.70 seconds and 0.68 seconds. What best explains the difference in results?</strong></div>
          <form name="q52" id="q52">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;The distance changed in the two experiments.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;Most probably, the speed with which M1 dropped was slightly higher when M2 weighed less.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;Students in one or the other group made an error in recording the results.</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans52 radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp; Each time measurement is the average of three trials, so the minor difference is probably due to math.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q52, 'correctAns52');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns52" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">J is the best answer</span> because it is the only answer supported by information in the passage.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson6_p1" onClick="chkTimer('#lesson6_p1');" style="color:#0000FF"><span class="linkColor">Recognize Components of Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe11" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>11. The results of Group B's experiment supported the hypothesis. Which statement best summarizes a conclusion Group B could draw from its results?</strong></div>
          <form name="q53" id="q53">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"> <strong>A.</strong> &nbsp;Speed increases with increasing mass and force.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;Holding mass constant, increasing force increases speed.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;At the same speed, a greater mass will travel with less force.</label>
              <input type="radio" name="r1" id="r4" value="answer"  />
              <label for="r4" data-theme="c" class="ans53 radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;When force is held constant, mass is inversely related to speed.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q53, 'correctAns53');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns53" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">D is the best answer</span> because it matches the data in Table 2: force M1 is held constant and as mass M2 increases, speed decreases, an inverse relationship.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson7_p1" onClick="chkTimer('#lesson7_p1');" style="color:#0000FF"><span class="linkColor">Match Data and Models to Hypotheses, Predictions, and Conclusions.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe12" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>12. Speed is measured in meters/second. Suppose one of the student groups decided to increase <em>d</em> while holding all other values constant. What prediction could you make about the effect on the experimental results for that group?</strong></div>
          <form name="q54" id="q54">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans54 radioBtnAlign" style="height:auto;"> <strong>F.</strong> &nbsp;The values for speed would stay roughly the same.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>G.</strong> &nbsp;The values for speed would decrease significantly.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong> &nbsp;The values for speed would increase significantly.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;The values for speed would be inversely proportional to the change in <em>d</em>.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q54, 'correctAns54');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns54" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">F is the best answer</span> because increasing the distance <em>d</em> would increase the time needed for M2 to pass under both sensors. Both the distance and the time would increase (the numerator and denominator in the unit of measure would both increase), so speed would not change.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson9_p1" onClick="chkTimer('#lesson9_p1');" style="color:#0000FF"><span class="linkColor">Predict Using Models and Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe13" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>13. Acceleration is a change in speed, direction, or both. It is measured in meters/second squared. Based on the passage, the figure, and both tables, what can you conclude about the relationship between mass, force, and acceleration?</strong></div>
          <form name="q55" id="q55">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value="answer"/>
              <label for="r1" data-theme="c" class="ans55 radioBtnAlign" style="height:auto;"> <strong>A.</strong> &nbsp;For any given mass, as the force applied increases, acceleration increases.</label>
              <input type="radio" name="r1" id="r2" value=""/>
              <label for="r2" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>B.</strong> &nbsp;For any given mass, as acceleration increases, force decreases.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>C.</strong> &nbsp;For any given mass, as the force applied increases, acceleration decreases.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>D.</strong> &nbsp;For any given force, as mass increases, acceleration increases.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q55, 'correctAns55');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns55" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">A is the best answer</span> because it matches the data in Tables 1 and 2, and acceleration will change in the same way that speed changes.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson5_p1" onClick="chkTimer('#lesson5_p1');" style="color:#0000FF"><span class="linkColor">Interpret New Information.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    <li style='display:none;'>
      <div id="answerchoooe14" style="display:none;">
        <div class="testpageWidth">
        <div class="normalTimes" style="margin-bottom:20px;margin-left:23px; text-indent:-23px;"><strong>14. In the two experiments, which variables (force, mass, and speed) changed?</strong></div>
          <form name="q56" id="q56">
            <fieldset data-role="controlgroup">
              <input type="radio" name="r1" id="r1" value=""/>
              <label for="r1" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>F.</strong> &nbsp;Speed is the only variable that changed in both experiments.</label>
              <input type="radio" name="r1" id="r2" value="Answer"/>
              <label for="r2" data-theme="c" class="ans56 radioBtnAlign" style="height:auto;"><strong>G.</strong>&nbsp;In Group A's experiment, force and speed changed; in Group B's experiment, mass and speed changed.</label>
              <input type="radio" name="r1" id="r3" value=""  />
              <label for="r3" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>H.</strong>&nbsp;All three variables changed in both experiment.</label>
              <input type="radio" name="r1" id="r4" value=""  />
              <label for="r4" data-theme="c" class="radioBtnAlign" style="height:auto;"><strong>J.</strong> &nbsp;In Group A's experiment, mass and speed changed; in Group B's experiment, force and speed changed.</label>
            </fieldset>
            
          </form>
        </div>
              <div class="Banner_Timer">
        <div class="defaultSubmit"><input type="button" name="submit" value="Submit" data-transition="pop" data-theme="c" onMouseDown="validateNewAns(q56, 'correctAns56');" style="width:100px;"/></div>
          <div class="defaultCountdown" style="padding-top:5px; margin-top:8px;"></div>
           </div>
           <div style="clear:both;"></div>

        <div id="correctAns56" class="blackNormalTextAnswer testPageCorrectAns">
          <div><span class="blackBoldText">G is the best answer</span> because it matches the descriptions in the experiments in the passage and the results in the tables.</div>
          <div class="twentyspace"></div>
          <div>For help, see <a href="#lesson6_p1" onClick="chkTimer('#lesson6_p1');" style="color:#0000FF"><span class="linkColor">Recognize Components of Experimental Design.</span></a></div>
        </div>
      </div>
    </li>
      <!--Answer Panel End-->
      <!--Answer Panel Start-->
    </ul>
  </div>
  </div>

  <!--Navigation-->
  <div class="submit_icon" id="sub_4" onclick="submit_4();">SUBMIT</div>
  <div id="feed4">
	<img src="images/tick.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="correct_ans4">5</span>
	<img src="images/wrong.png" style="position: relative;height: 30px;margin-left: 40px;"><span id="wrong_ans4">a</span>
  </div>
  <div class="home_go" onClick="chkTimer('#index');"></div>
  <div class="calc-container"></div>
  <div align="center" data-role="footer" data-theme="f" class="testFooterNavAlign" id="question1" style="display:block;">
    <table cellpadding="0" cellspacing="0" class="testFooter">
      <tr>
        <!--<td class="testMenu"><a href="#index" onClick="chkTimer('#index');" data-back="true" data-role="button" data-inline="true" data-transition="none" data-icon="home" data-theme="c"><span class="footerBlackText">Menu<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <!--<td class="testBack"><a id="Back_But3" href="#test4_2" onClick="goBack3();" data-role="button" data-inline="true" data-transition="none" data-icon="back" data-iconpos="left" data-theme="c" data-back="false" style="visibility:hidden;"><span class="footerBlackText">Back<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
        <!--<td class="testNext"><a href="#test4_2" onClick="chkquestime3();" data-role="button" data-inline="true" data-transition="none" data-icon="forward" data-iconpos="right" data-theme="c" data-back="false"><span class="footerBlackText">Next<img src="images/spacer.png" width="1" height="20"/></span></a></td>-->
	<div class="foot_ques"><span id="hardest_Q">1</span> / 5</div>
	<div class="go_prev testBack" id="Back_But3" style="visibility:hidden;" onClick="goBack3();"></div>
	<div class="go_next testNext" id="next4" onClick="chkquestime3();"></div>
      </tr>
    </table>
  </div>  </div>
  <!--Navigation-->
</div>
<!------------------------------------- Test 4 Question 1 End ------------------------------------->
</body>
</html>


calculator.css
===============


@font-face {
    font-family: 'Source Sans Pro';
    src: url('../font/SourceSansPro-ExtraLight.woff') format('woff');
    font-weight: 400;
    font-style: normal;
}

body {
    /*background-color: #000;*/
    margin: 0;
    font-family: 'Source Sans Pro', sans-serif;
}

div {
    padding: 0;
    margin: 0;
}

#main {
    width: 100%;
}

#calculatorsource {
    display: none;
    position: absolute;
    width: 174px;
    height: 230px;
    z-index: 10;
    /* background: url(../images/calculator.png) no-repeat; */
    cursor: move;
    left: 0px;
    top: 25px;
}


#keypad {
  position: absolute;
top: 0px;
width: 100%;
height: 230px;
  /*  margin: 15px 4px 4px 4px;*/
}

#keypad > div {
    height: 39px;
    font-size: 22px;
    width: 100%;
    overflow: hidden;
    /*border-bottom: 1px solid black;*/
}

#keypad > div.display > input {
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 15pt;
    height: 51px;
    width: 97%;
    text-align: right;
    background-color: #B62323;
    color: #fff;
    border: none;
    padding: 2px;
    pointer-events: none;
}

#keypad > div > div {
    padding-top: 5px;
    border: 1px solid #575757;
    width: 23.7%;
    text-align: center;
    background-color: #CFD0D2;
    color: #272727;
    display: inline-block;
    height: 100%;
    float:left;
}
#empty {
    padding-top: 15px !important;
    border-right: 1px solid black !important;
    width: 48.5% !important;
    text-align: center !important;
    background-color: #CFD0D2 !important;
    color: #272727 !important;
    display: inline-block !important;
    height: 100% !important;
    float:left !important;
}

#keypad > div.horizontal.display {
    border: none;
    margin-bottom: -4px;
}

#keypad > div > div.double-wide {
    width: 48.5%;
}

.num-key {
    background-color: #CFD0D2;
}

#keypad > div > div.control-key {
    background-color: #C1C2C4;
    color: #1D1D1D;
}

#keypad > div > div.operation-key {
    background-color: #22A9C2;
    color: #fff;
}
.key{
    cursor: pointer;
}
#rim{
    width:274px;
    height:230px;
}
#calClose{
    background: url(../images/close_btn.png) no-repeat;
background-size: contain;
width: 26px;
position: absolute;
height: 19px;
top: -10px;
left: 165px;
z-index: 10;
}


jquery_mobile.css
===================

/*
* jQuery Mobile Framework Git Build: SHA1: b49cc06499abf8f987cf90f35349cfac0918c939 <> Date: Tue Oct 2 11:22:34 2012 -0700
* http://jquerymobile.com
*
* Copyright 2012 jQuery Foundation and other contributors
* Released under the MIT license.
* http://jquery.org/license
*
*/


/* Swatches */
/* A
-----------------------------------------------------------------------------------------------------------*/
.ui-bar-a {
	border: 1px solid 		#333 /*{a-bar-border}*/;
	background: 			#111 /*{a-bar-background-color}*/;
	color: 					#fff /*{a-bar-color}*/;
	font-weight: bold;
	text-shadow: 0 /*{a-bar-shadow-x}*/ -1px /*{a-bar-shadow-y}*/ 1px /*{a-bar-shadow-radius}*/ #000 /*{a-bar-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #3c3c3c /*{a-bar-background-start}*/), to( #111 /*{a-bar-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #3c3c3c /*{a-bar-background-start}*/, #111 /*{a-bar-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #3c3c3c /*{a-bar-background-start}*/, #111 /*{a-bar-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #3c3c3c /*{a-bar-background-start}*/, #111 /*{a-bar-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #3c3c3c /*{a-bar-background-start}*/, #111 /*{a-bar-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #3c3c3c /*{a-bar-background-start}*/, #111 /*{a-bar-background-end}*/);
}
.ui-bar-a,
.ui-bar-a input,
.ui-bar-a select,
.ui-bar-a textarea,
.ui-bar-a button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-bar-a .ui-link-inherit {
	color: #fff /*{a-bar-color}*/;
}
.ui-bar-a a.ui-link {
	color: #7cc4e7 /*{a-bar-link-color}*/;
	font-weight: bold;
}
.ui-bar-a a.ui-link:visited {
    color: #2489ce /*{a-bar-link-visited}*/;
}
.ui-bar-a a.ui-link:hover {
	color: #2489ce /*{a-bar-link-hover}*/;
}
.ui-bar-a a.ui-link:active {
	color: #2489ce /*{a-bar-link-active}*/;
}
.ui-body-a,
.ui-overlay-a {
	border: 1px solid 		#444 /*{a-body-border}*/;
	background: 			#222 /*{a-body-background-color}*/;
	color: 					#fff /*{a-body-color}*/;
	text-shadow: 0 /*{a-body-shadow-x}*/ 1px /*{a-body-shadow-y}*/ 1px /*{a-body-shadow-radius}*/ #111 /*{a-body-shadow-color}*/;
	font-weight: normal;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #444 /*{a-body-background-start}*/), to( #222 /*{a-body-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #444 /*{a-body-background-start}*/, #222 /*{a-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #444 /*{a-body-background-start}*/, #222 /*{a-body-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #444 /*{a-body-background-start}*/, #222 /*{a-body-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #444 /*{a-body-background-start}*/, #222 /*{a-body-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #444 /*{a-body-background-start}*/, #222 /*{a-body-background-end}*/);	
}
.ui-overlay-a {
	background-image: none;
	border-width: 0;
}
.ui-body-a,
.ui-body-a input,
.ui-body-a select,
.ui-body-a textarea,
.ui-body-a button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-a .ui-link-inherit {
	color: 	#fff /*{a-body-color}*/;
}
.ui-body-a .ui-link {
	color: #2489ce /*{a-body-link-color}*/;
	font-weight: bold;
}
.ui-body-a .ui-link:visited {
    color: #2489ce /*{a-body-link-visited}*/;
}
.ui-body-a .ui-link:hover {
	color: #2489ce /*{a-body-link-hover}*/;
}
.ui-body-a .ui-link:active {
	color: #2489ce /*{a-body-link-active}*/;
}
.ui-btn-up-a {
	border: 1px solid 		#111 /*{a-bup-border}*/;
	background: 			#333 /*{a-bup-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{a-bup-color}*/;
	text-shadow: 0 /*{a-bup-shadow-x}*/ 1px /*{a-bup-shadow-y}*/ 1px /*{a-bup-shadow-radius}*/ #111 /*{a-bup-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #444 /*{a-bup-background-start}*/), to( #2d2d2d /*{a-bup-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #444 /*{a-bup-background-start}*/, #2d2d2d /*{a-bup-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #444 /*{a-bup-background-start}*/, #2d2d2d /*{a-bup-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #444 /*{a-bup-background-start}*/, #2d2d2d /*{a-bup-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #444 /*{a-bup-background-start}*/, #2d2d2d /*{a-bup-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #444 /*{a-bup-background-start}*/, #2d2d2d /*{a-bup-background-end}*/);
}
.ui-btn-up-a:visited,
.ui-btn-up-a a.ui-link-inherit {
	color: 					#fff /*{a-bup-color}*/;
}
.ui-btn-hover-a {
	border: 1px solid 		#000 /*{a-bhover-border}*/;
	background: 			#444 /*{a-bhover-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{a-bhover-color}*/;
	text-shadow: 0 /*{a-bhover-shadow-x}*/ 1px /*{a-bhover-shadow-y}*/ 1px /*{a-bhover-shadow-radius}*/ #111 /*{a-bhover-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #555 /*{a-bhover-background-start}*/), to( #383838 /*{a-bhover-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #555 /*{a-bhover-background-start}*/, #383838 /*{a-bhover-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #555 /*{a-bhover-background-start}*/, #383838 /*{a-bhover-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #555 /*{a-bhover-background-start}*/, #383838 /*{a-bhover-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #555 /*{a-bhover-background-start}*/, #383838 /*{a-bhover-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #555 /*{a-bhover-background-start}*/, #383838 /*{a-bhover-background-end}*/);
}
.ui-btn-hover-a:visited,
.ui-btn-hover-a:hover,
.ui-btn-hover-a a.ui-link-inherit {
	color: 					#fff /*{a-bhover-color}*/;
}
.ui-btn-down-a {
	border: 1px solid 		#000 /*{a-bdown-border}*/;
	background: 			#222 /*{a-bdown-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{a-bdown-color}*/;
	text-shadow: 0 /*{a-bdown-shadow-x}*/ 1px /*{a-bdown-shadow-y}*/ 1px /*{a-bdown-shadow-radius}*/ #111 /*{a-bdown-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #202020 /*{a-bdown-background-start}*/), to( #2c2c2c /*{a-bdown-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #202020 /*{a-bdown-background-start}*/, #2c2c2c /*{a-bdown-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #202020 /*{a-bdown-background-start}*/, #2c2c2c /*{a-bdown-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #202020 /*{a-bdown-background-start}*/, #2c2c2c /*{a-bdown-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #202020 /*{a-bdown-background-start}*/, #2c2c2c /*{a-bdown-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #202020 /*{a-bdown-background-start}*/, #2c2c2c /*{a-bdown-background-end}*/);
}
.ui-btn-down-a:visited,
.ui-btn-down-a:hover,
.ui-btn-down-a a.ui-link-inherit {
	color: 					#fff /*{a-bdown-color}*/;
}
.ui-btn-up-a,
.ui-btn-hover-a,
.ui-btn-down-a {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
	text-decoration: none;
}
/* B
-----------------------------------------------------------------------------------------------------------*/
.ui-bar-b {
	border: 1px solid 		#456f9a /*{b-bar-border}*/;
	background: 			#5e87b0 /*{b-bar-background-color}*/;
	color: 					#fff /*{b-bar-color}*/;
	font-weight: bold;
	text-shadow: 0 /*{b-bar-shadow-x}*/ 1px /*{b-bar-shadow-y}*/ 1px /*{b-bar-shadow-radius}*/ #3e6790 /*{b-bar-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #6facd5 /*{b-bar-background-start}*/), to( #497bae /*{b-bar-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #6facd5 /*{b-bar-background-start}*/, #497bae /*{b-bar-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #6facd5 /*{b-bar-background-start}*/, #497bae /*{b-bar-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #6facd5 /*{b-bar-background-start}*/, #497bae /*{b-bar-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #6facd5 /*{b-bar-background-start}*/, #497bae /*{b-bar-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #6facd5 /*{b-bar-background-start}*/, #497bae /*{b-bar-background-end}*/);
}
.ui-bar-b,
.ui-bar-b input,
.ui-bar-b select,
.ui-bar-b textarea,
.ui-bar-b button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-bar-b .ui-link-inherit {
	color: 	#fff /*{b-bar-color}*/;
}
.ui-bar-b a.ui-link {
	color: #ddf0f8 /*{b-bar-link-color}*/;
	font-weight: bold;
}
.ui-bar-b a.ui-link:visited {
    color: #ddf0f8 /*{b-bar-link-visited}*/;
}
.ui-bar-b a.ui-link:hover {
	color: #ddf0f8 /*{b-bar-link-hover}*/;
}
.ui-bar-b a.ui-link:active {
	color: #ddf0f8 /*{b-bar-link-active}*/;
}
.ui-body-b,
.ui-overlay-b {
	border: 1px solid 		#999 /*{b-body-border}*/;
	background: 			#f3f3f3 /*{b-body-background-color}*/;
	color: 					#222 /*{b-body-color}*/;
	text-shadow: 0 /*{b-body-shadow-x}*/ 1px /*{b-body-shadow-y}*/ 0 /*{b-body-shadow-radius}*/ #fff /*{b-body-shadow-color}*/;
	font-weight: normal;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #ddd /*{b-body-background-start}*/), to( #ccc /*{b-body-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #ddd /*{b-body-background-start}*/, #ccc /*{b-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #ddd /*{b-body-background-start}*/, #ccc /*{b-body-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #ddd /*{b-body-background-start}*/, #ccc /*{b-body-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #ddd /*{b-body-background-start}*/, #ccc /*{b-body-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #ddd /*{b-body-background-start}*/, #ccc /*{b-body-background-end}*/);
}
.ui-overlay-b {
	background-image: none;
	border-width: 0;
}
.ui-body-b,
.ui-body-b input,
.ui-body-b select,
.ui-body-b textarea,
.ui-body-b button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-b .ui-link-inherit {
	color: 	#333 /*{b-body-color}*/;
}
.ui-body-b .ui-link {
	color: #2489ce /*{b-body-link-color}*/;
	font-weight: bold;
}
.ui-body-b .ui-link:visited {
    color: #2489ce /*{b-body-link-visited}*/;
}
.ui-body-b .ui-link:hover {
	color: #2489ce /*{b-body-link-hover}*/;
}
.ui-body-b .ui-link:active {
	color: #2489ce /*{b-body-link-active}*/;
}
.ui-btn-up-b {
	border: 1px solid 		#044062 /*{b-bup-border}*/;
	background: 			#396b9e /*{b-bup-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{b-bup-color}*/;
	text-shadow: 0 /*{b-bup-shadow-x}*/ 1px /*{b-bup-shadow-y}*/ 1px /*{b-bup-shadow-radius}*/ #194b7e /*{b-bup-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #5f9cc5 /*{b-bup-background-start}*/), to( #396b9e /*{b-bup-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #5f9cc5 /*{b-bup-background-start}*/, #396b9e /*{b-bup-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #5f9cc5 /*{b-bup-background-start}*/, #396b9e /*{b-bup-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #5f9cc5 /*{b-bup-background-start}*/, #396b9e /*{b-bup-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #5f9cc5 /*{b-bup-background-start}*/, #396b9e /*{b-bup-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #5f9cc5 /*{b-bup-background-start}*/, #396b9e /*{b-bup-background-end}*/);
}
.ui-btn-up-b:visited,
.ui-btn-up-b a.ui-link-inherit {
	color: 					#fff /*{b-bup-color}*/;
}
.ui-btn-hover-b {
	border: 1px solid 		#00415e /*{b-bhover-border}*/;
	background: 			#4b88b6 /*{b-bhover-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{b-bhover-color}*/;
	text-shadow: 0 /*{b-bhover-shadow-x}*/ 1px /*{b-bhover-shadow-y}*/ 1px /*{b-bhover-shadow-radius}*/ #194b7e /*{b-bhover-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #6facd5 /*{b-bhover-background-start}*/), to( #4272a4 /*{b-bhover-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #6facd5 /*{b-bhover-background-start}*/, #4272a4 /*{b-bhover-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #6facd5 /*{b-bhover-background-start}*/, #4272a4 /*{b-bhover-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #6facd5 /*{b-bhover-background-start}*/, #4272a4 /*{b-bhover-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #6facd5 /*{b-bhover-background-start}*/, #4272a4 /*{b-bhover-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #6facd5 /*{b-bhover-background-start}*/, #4272a4 /*{b-bhover-background-end}*/);
}
.ui-btn-hover-b:visited,
.ui-btn-hover-b:hover,
.ui-btn-hover-b a.ui-link-inherit {
	color: 					#fff /*{b-bhover-color}*/;
}
.ui-btn-down-b {
	border: 1px solid 		#225377 /*{b-bdown-border}*/;
	background: 			#4e89c5 /*{b-bdown-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{b-bdown-color}*/;
	text-shadow: 0 /*{b-bdown-shadow-x}*/ 1px /*{b-bdown-shadow-y}*/ 1px /*{b-bdown-shadow-radius}*/ #194b7e /*{b-bdown-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #295b8e /*{b-bdown-background-start}*/), to( #3e79b5 /*{b-bdown-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #295b8e /*{b-bdown-background-start}*/, #3e79b5 /*{b-bdown-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #295b8e /*{b-bdown-background-start}*/, #3e79b5 /*{b-bdown-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #295b8e /*{b-bdown-background-start}*/, #3e79b5 /*{b-bdown-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #295b8e /*{b-bdown-background-start}*/, #3e79b5 /*{b-bdown-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #295b8e /*{b-bdown-background-start}*/, #3e79b5 /*{b-bdown-background-end}*/);
}
.ui-btn-down-b:visited,
.ui-btn-down-b:hover,
.ui-btn-down-b a.ui-link-inherit {
	color: 					#fff /*{b-bdown-color}*/;
}
.ui-btn-up-b,
.ui-btn-hover-b,
.ui-btn-down-b {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
	text-decoration: none;
}
/* C
-----------------------------------------------------------------------------------------------------------*/
.ui-bar-c {
	border: 1px solid 		#b3b3b3 /*{c-bar-border}*/;
	background: 			#eee /*{c-bar-background-color}*/;
	color: 					#3e3e3e /*{c-bar-color}*/;
	font-weight: bold;
	text-shadow: 0 /*{c-bar-shadow-x}*/ 1px /*{c-bar-shadow-y}*/ 1px /*{c-bar-shadow-radius}*/ 	#fff /*{c-bar-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #f0f0f0 /*{c-bar-background-start}*/), to( #ddd /*{c-bar-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #f0f0f0 /*{c-bar-background-start}*/, #ddd /*{c-bar-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #f0f0f0 /*{c-bar-background-start}*/, #ddd /*{c-bar-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #f0f0f0 /*{c-bar-background-start}*/, #ddd /*{c-bar-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #f0f0f0 /*{c-bar-background-start}*/, #ddd /*{c-bar-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #f0f0f0 /*{c-bar-background-start}*/, #ddd /*{c-bar-background-end}*/);
}
.ui-bar-c .ui-link-inherit {
	color: 	#3e3e3e /*{c-bar-color}*/;
}
.ui-bar-c a.ui-link {
	color: #7cc4e7 /*{c-bar-link-color}*/;
	font-weight: bold;
}
.ui-bar-c a.ui-link:visited {
    color: #2489ce /*{c-bar-link-visited}*/;
}
.ui-bar-c a.ui-link:hover {
	color: #2489ce /*{c-bar-link-hover}*/;
}
.ui-bar-c a.ui-link:active {
	color: #2489ce /*{c-bar-link-active}*/;
}
.ui-bar-c,
.ui-bar-c input,
.ui-bar-c select,
.ui-bar-c textarea,
.ui-bar-c button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-c,
.ui-overlay-c {
	border: 1px solid 		#aaa /*{c-body-border}*/;
	color: 					#333 /*{c-body-color}*/;
	/*text-shadow: 0 /*{c-body-shadow-x}*/ 1px /*{c-body-shadow-y}*/ 0 /*{c-body-shadow-radius}*/ #fff /*{c-body-shadow-color}*/;*/
	background: 			#f9f9f9 /*{c-body-background-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #f9f9f9 /*{c-body-background-start}*/), to( #eee /*{c-body-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #f9f9f9 /*{c-body-background-start}*/, #eee /*{c-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #f9f9f9 /*{c-body-background-start}*/, #eee /*{c-body-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #f9f9f9 /*{c-body-background-start}*/, #eee /*{c-body-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #f9f9f9 /*{c-body-background-start}*/, #eee /*{c-body-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #f9f9f9 /*{c-body-background-start}*/, #eee /*{c-body-background-end}*/);
}
.ui-overlay-c {
	background-image: none;
	border-width: 0;
}
.ui-body-c,
.ui-body-c input,
.ui-body-c select,
.ui-body-c textarea,
.ui-body-c button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-c .ui-link-inherit {
	color: 	#333 /*{c-body-color}*/;
}
.ui-body-c .ui-link {
	color: #2489ce /*{c-body-link-color}*/;
	font-weight: bold;
}
.ui-body-c .ui-link:visited {
    color: #2489ce /*{c-body-link-visited}*/;
}
.ui-body-c .ui-link:hover {
	color: #2489ce /*{c-body-link-hover}*/;
}
.ui-body-c .ui-link:active {
	color: #2489ce /*{c-body-link-active}*/;
}
.ui-btn-up-c {
	border: 1px solid #ccc /*{c-bup-border}*/;
	background:#eee /*{c-bup-background-color}*/;
	font-weight: bold;
	color: #ffffff /*{c-bup-color}*/;
	
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fff /*{c-bup-background-start}*/), to( #f1f1f1 /*{c-bup-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fff /*{c-bup-background-start}*/, #f1f1f1 /*{c-bup-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fff /*{c-bup-background-start}*/, #f1f1f1 /*{c-bup-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fff /*{c-bup-background-start}*/, #f1f1f1 /*{c-bup-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fff /*{c-bup-background-start}*/, #f1f1f1 /*{c-bup-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fff /*{c-bup-background-start}*/, #f1f1f1 /*{c-bup-background-end}*/);
	
	
	
	
	background: rgba(3, 28, 58, 0.5);
	border-radius: 4px;
	border: 1px solid #0c364e;
	-webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	-moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	
	
}
.ui-btn-up-c:visited,
.ui-btn-up-c a.ui-link-inherit {
	color: 					#2f3e46 /*{c-bup-color}*/;
}
.ui-btn-hover-c {
	border: 1px solid 		#bbb /*{c-bhover-border}*/;
	background: 			rgba(161, 193, 231, 0.5) /*{c-bhover-background-color}*/;
	font-weight: bold;
	color: 					#222 /*{c-bhover-color}*/;
	text-shadow: 0 /*{c-bhover-shadow-x}*/ 1px /*{c-bhover-shadow-y}*/ 0 /*{c-bhover-shadow-radius}*/ #fff /*{c-bhover-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #f6f6f6 /*{c-bhover-background-start}*/), to( #e0e0e0 /*{c-bhover-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #f6f6f6 /*{c-bhover-background-start}*/, #e0e0e0 /*{c-bhover-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #f6f6f6 /*{c-bhover-background-start}*/, #e0e0e0 /*{c-bhover-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #f6f6f6 /*{c-bhover-background-start}*/, #e0e0e0 /*{c-bhover-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #f6f6f6 /*{c-bhover-background-start}*/, #e0e0e0 /*{c-bhover-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #f6f6f6 /*{c-bhover-background-start}*/, #e0e0e0 /*{c-bhover-background-end}*/);
}
.ui-btn-hover-c:visited,
.ui-btn-hover-c:hover,
.ui-btn-hover-c a.ui-link-inherit {
	color: 					#fff /*{c-bhover-color}*/;
	background: 			rgba(161, 193, 231, 0.5) /*{c-bhover-background-color}*/;
}
.ui-btn-down-c {
	border: 1px solid 		#bbb /*{c-bdown-border}*/;
	background: 			#d6d6d6 /*{c-bdown-background-color}*/;
	font-weight: bold;
	color: 					#222 /*{c-bdown-color}*/;
	text-shadow: 0 /*{c-bdown-shadow-x}*/ 1px /*{c-bdown-shadow-y}*/ 0 /*{c-bdown-shadow-radius}*/ #fff /*{c-bdown-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #d0d0d0 /*{c-bdown-background-start}*/), to( #dfdfdf /*{c-bdown-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #d0d0d0 /*{c-bdown-background-start}*/, #dfdfdf /*{c-bdown-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #d0d0d0 /*{c-bdown-background-start}*/, #dfdfdf /*{c-bdown-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #d0d0d0 /*{c-bdown-background-start}*/, #dfdfdf /*{c-bdown-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #d0d0d0 /*{c-bdown-background-start}*/, #dfdfdf /*{c-bdown-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #d0d0d0 /*{c-bdown-background-start}*/, #dfdfdf /*{c-bdown-background-end}*/);
}
.ui-btn-down-c:visited,
.ui-btn-down-c:hover,
.ui-btn-down-c a.ui-link-inherit {
	color: 					#2f3e46 /*{c-bdown-color}*/;
}
.ui-btn-up-c,
.ui-btn-hover-c,
.ui-btn-down-c {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
	text-decoration: none;
}
/* D
-----------------------------------------------------------------------------------------------------------*/
.ui-bar-d {
	border: 1px solid 		#bbb /*{d-bar-border}*/;
	background: 			#bbb /*{d-bar-background-color}*/;
	color: 					#333 /*{d-bar-color}*/;
	font-weight: bold;
	text-shadow: 0 /*{d-bar-shadow-x}*/ 1px /*{d-bar-shadow-y}*/ 0 /*{d-bar-shadow-radius}*/ #eee /*{d-bar-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #ddd /*{d-bar-background-start}*/), to( #bbb /*{d-bar-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #ddd /*{d-bar-background-start}*/, #bbb /*{d-bar-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #ddd /*{d-bar-background-start}*/, #bbb /*{d-bar-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #ddd /*{d-bar-background-start}*/, #bbb /*{d-bar-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #ddd /*{d-bar-background-start}*/, #bbb /*{d-bar-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #ddd /*{d-bar-background-start}*/, #bbb /*{d-bar-background-end}*/);
}
.ui-bar-d,
.ui-bar-d input,
.ui-bar-d select,
.ui-bar-d textarea,
.ui-bar-d button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-bar-d .ui-link-inherit {
	color: 	#333 /*{d-bar-color}*/;
}
.ui-bar-d a.ui-link {
	color: #2489ce /*{d-bar-link-color}*/;
	font-weight: bold;
}
.ui-bar-d a.ui-link:visited {
    color: #2489ce /*{d-bar-link-visited}*/;
}
.ui-bar-d a.ui-link:hover {
	color: #2489ce /*{d-bar-link-hover}*/;
}
.ui-bar-d a.ui-link:active {
	color: #2489ce /*{d-bar-link-active}*/;
}
.ui-body-d,
.ui-overlay-d {
	border: 1px solid 		#bbb /*{d-body-border}*/;
	color: 					#333 /*{d-body-color}*/;
	text-shadow: 0 /*{d-body-shadow-x}*/ 1px /*{d-body-shadow-y}*/ 0 /*{d-body-shadow-radius}*/ 	#fff /*{d-body-shadow-color}*/;
	background: 			#fff /*{d-body-background-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fff /*{d-body-background-start}*/), to( #fff /*{d-body-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fff /*{d-body-background-start}*/, #fff /*{d-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fff /*{d-body-background-start}*/, #fff /*{d-body-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fff /*{d-body-background-start}*/, #fff /*{d-body-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fff /*{d-body-background-start}*/, #fff /*{d-body-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fff /*{d-body-background-start}*/, #fff /*{d-body-background-end}*/);
}
.ui-overlay-d {
	background-image: none;
	border-width: 0;
}
.ui-body-d,
.ui-body-d input,
.ui-body-d select,
.ui-body-d textarea,
.ui-body-d button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-d .ui-link-inherit {
	color: 	#333 /*{d-body-color}*/;
}
.ui-body-d .ui-link {
	color: #2489ce /*{d-body-link-color}*/;
	font-weight: bold;
}
.ui-body-d .ui-link:visited {
    color: #2489ce /*{d-body-link-visited}*/;
}
.ui-body-d .ui-link:hover {
	color: #2489ce /*{d-body-link-hover}*/;
}
.ui-body-d .ui-link:active {
	color: #2489ce /*{d-body-link-active}*/;
}
.ui-btn-up-d {
	border: 1px solid 		#bbb /*{d-bup-border}*/;
	background: 			#fff /*{d-bup-background-color}*/;
	font-weight: bold;
	color: 					#333 /*{d-bup-color}*/;
	text-shadow: 0 /*{d-bup-shadow-x}*/ 1px /*{d-bup-shadow-y}*/ 0 /*{d-bup-shadow-radius}*/ #fff /*{d-bup-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fafafa /*{d-bup-background-start}*/), to( #f6f6f6 /*{d-bup-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fafafa /*{d-bup-background-start}*/, #f6f6f6 /*{d-bup-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fafafa /*{d-bup-background-start}*/, #f6f6f6 /*{d-bup-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fafafa /*{d-bup-background-start}*/, #f6f6f6 /*{d-bup-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fafafa /*{d-bup-background-start}*/, #f6f6f6 /*{d-bup-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fafafa /*{d-bup-background-start}*/, #f6f6f6 /*{d-bup-background-end}*/);
}
.ui-btn-up-d:visited,
.ui-btn-up-d a.ui-link-inherit {
	color: 					#333 /*{d-bup-color}*/;
}
.ui-btn-hover-d {
	border: 1px solid 		#aaa /*{d-bhover-border}*/;
	background: 			#eee /*{d-bhover-background-color}*/;
	font-weight: bold;
	color: 					#333 /*{d-bhover-color}*/;
	cursor: pointer;
	text-shadow: 0 /*{d-bhover-shadow-x}*/ 1px /*{d-bhover-shadow-y}*/ 0 /*{d-bhover-shadow-radius}*/ 	#fff /*{d-bhover-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #eee /*{d-bhover-background-start}*/), to( #fff /*{d-bhover-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #eee /*{d-bhover-background-start}*/, #fff /*{d-bhover-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #eee /*{d-bhover-background-start}*/, #fff /*{d-bhover-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #eee /*{d-bhover-background-start}*/, #fff /*{d-bhover-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #eee /*{d-bhover-background-start}*/, #fff /*{d-bhover-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #eee /*{d-bhover-background-start}*/, #fff /*{d-bhover-background-end}*/);
}
.ui-btn-hover-d:visited,
.ui-btn-hover-d:hover,
.ui-btn-hover-d a.ui-link-inherit {
	color: 					#333 /*{d-bhover-color}*/;
}
.ui-btn-down-d {
	border: 1px solid 		#aaa /*{d-bdown-border}*/;
	background: 			#eee /*{d-bdown-background-color}*/;
	font-weight: bold;
	color: 					#333 /*{d-bdown-color}*/;
	text-shadow: 0 /*{d-bdown-shadow-x}*/ 1px /*{d-bdown-shadow-y}*/ 0 /*{d-bdown-shadow-radius}*/ 	#fff /*{d-bdown-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #e5e5e5 /*{d-bdown-background-start}*/), to( #f2f2f2 /*{d-bdown-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #e5e5e5 /*{d-bdown-background-start}*/, #f2f2f2 /*{d-bdown-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #e5e5e5 /*{d-bdown-background-start}*/, #f2f2f2 /*{d-bdown-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #e5e5e5 /*{d-bdown-background-start}*/, #f2f2f2 /*{d-bdown-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #e5e5e5 /*{d-bdown-background-start}*/, #f2f2f2 /*{d-bdown-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #e5e5e5 /*{d-bdown-background-start}*/, #f2f2f2 /*{d-bdown-background-end}*/);
}
.ui-btn-down-d:visited,
.ui-btn-down-d:hover,
.ui-btn-down-d a.ui-link-inherit {
	color: 					#333 /*{d-bdown-color}*/;
}
.ui-btn-up-d,
.ui-btn-hover-d,
.ui-btn-down-d {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
	text-decoration: none;
}
/* E
-----------------------------------------------------------------------------------------------------------*/
.ui-bar-e {
	border: 1px solid 		#f7c942 /*{e-bar-border}*/;
	background: 			#fadb4e /*{e-bar-background-color}*/;
	color: 					#333 /*{e-bar-color}*/;
	font-weight: bold;
	text-shadow: 0 /*{e-bar-shadow-x}*/ 1px /*{e-bar-shadow-y}*/ 0 /*{e-bar-shadow-radius}*/ 	#fff /*{e-bar-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fceda7 /*{e-bar-background-start}*/), to( #fbef7e /*{e-bar-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fceda7 /*{e-bar-background-start}*/, #fbef7e /*{e-bar-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fceda7 /*{e-bar-background-start}*/, #fbef7e /*{e-bar-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fceda7 /*{e-bar-background-start}*/, #fbef7e /*{e-bar-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fceda7 /*{e-bar-background-start}*/, #fbef7e /*{e-bar-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fceda7 /*{e-bar-background-start}*/, #fbef7e /*{e-bar-background-end}*/);
}
.ui-bar-e,
.ui-bar-e input,
.ui-bar-e select,
.ui-bar-e textarea,
.ui-bar-e button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-bar-e .ui-link-inherit {
	color: 	#333 /*{e-bar-color}*/;
}
.ui-bar-e a.ui-link {
	color: #2489ce /*{e-bar-link-color}*/;
	font-weight: bold;
}
.ui-bar-e a.ui-link:visited {
    color: #2489ce /*{e-bar-link-visited}*/;
}
.ui-bar-e a.ui-link:hover {
	color: #2489ce /*{e-bar-link-hover}*/;
}
.ui-bar-e a.ui-link:active {
	color: #2489ce /*{e-bar-link-active}*/;
}
.ui-body-e,
.ui-overlay-e {
	border: 1px solid 		#f7c942 /*{e-body-border}*/;
	color: 					#222 /*{e-body-color}*/;
	text-shadow: 0 /*{e-body-shadow-x}*/ 1px /*{e-body-shadow-y}*/ 0 /*{e-body-shadow-radius}*/ 	#fff /*{e-body-shadow-color}*/;
	background: 			#fff9df /*{e-body-background-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fffadf /*{e-body-background-start}*/), to( #fff3a5 /*{e-body-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fffadf /*{e-body-background-start}*/, #fff3a5 /*{e-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fffadf /*{e-body-background-start}*/, #fff3a5 /*{e-body-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fffadf /*{e-body-background-start}*/, #fff3a5 /*{e-body-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fffadf /*{e-body-background-start}*/, #fff3a5 /*{e-body-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fffadf /*{e-body-background-start}*/, #fff3a5 /*{e-body-background-end}*/);
}
.ui-overlay-e {
	background-image: none;
	border-width: 0;
}
.ui-body-e,
.ui-body-e input,
.ui-body-e select,
.ui-body-e textarea,
.ui-body-e button {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-body-e .ui-link-inherit {
	color: 	#222 /*{e-body-color}*/;
}
.ui-body-e .ui-link {
	color: #2489ce /*{e-body-link-color}*/;
	font-weight: bold;
}
.ui-body-e .ui-link:visited {
    color: #2489ce /*{e-body-link-visited}*/;
}
.ui-body-e .ui-link:hover {
	color: #2489ce /*{e-body-link-hover}*/;
}
.ui-body-e .ui-link:active {
	color: #2489ce /*{e-body-link-active}*/;
}
.ui-btn-up-e {
	border: 1px solid 		#f4c63f /*{e-bup-border}*/;
	background: 			#fadb4e /*{e-bup-background-color}*/;
	font-weight: bold;
	color: 					#222 /*{e-bup-color}*/;
	text-shadow: 0 /*{e-bup-shadow-x}*/ 1px /*{e-bup-shadow-y}*/ 0 /*{e-bup-shadow-radius}*/ 	#fff /*{e-bup-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #ffefaa /*{e-bup-background-start}*/), to( #ffe155 /*{e-bup-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #ffefaa /*{e-bup-background-start}*/, #ffe155 /*{e-bup-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #ffefaa /*{e-bup-background-start}*/, #ffe155 /*{e-bup-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #ffefaa /*{e-bup-background-start}*/, #ffe155 /*{e-bup-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #ffefaa /*{e-bup-background-start}*/, #ffe155 /*{e-bup-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #ffefaa /*{e-bup-background-start}*/, #ffe155 /*{e-bup-background-end}*/);
}
.ui-btn-up-e:visited,
.ui-btn-up-e a.ui-link-inherit {
	color: 					#222 /*{e-bup-color}*/;
}
.ui-btn-hover-e {
	border: 1px solid 		#f2c43d /*{e-bhover-border}*/;
	background: 			#fbe26f /*{e-bhover-background-color}*/;
	font-weight: bold;
	color: 					#111 /*{e-bhover-color}*/;
	text-shadow: 0 /*{e-bhover-shadow-x}*/ 1px /*{e-bhover-shadow-y}*/ 0 /*{e-bhover-shadow-radius}*/ 	#fff /*{e-bhover-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #fff5ba /*{e-bhover-background-start}*/), to( #fbdd52 /*{e-bhover-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #fff5ba /*{e-bhover-background-start}*/, #fbdd52 /*{e-bhover-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #fff5ba /*{e-bhover-background-start}*/, #fbdd52 /*{e-bhover-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #fff5ba /*{e-bhover-background-start}*/, #fbdd52 /*{e-bhover-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #fff5ba /*{e-bhover-background-start}*/, #fbdd52 /*{e-bhover-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #fff5ba /*{e-bhover-background-start}*/, #fbdd52 /*{e-bhover-background-end}*/);
}
.ui-btn-hover-e:visited,
.ui-btn-hover-e:hover,
.ui-btn-hover-e a.ui-link-inherit {
	color: 					#333 /*{e-bhover-color}*/;
}
.ui-btn-down-e {
	border: 1px solid 		#f2c43d /*{e-bdown-border}*/;
	background: 			#fceda7 /*{e-bdown-background-color}*/;
	font-weight: bold;
	color: 					#111 /*{e-bdown-color}*/;
	text-shadow: 0 /*{e-bdown-shadow-x}*/ 1px /*{e-bdown-shadow-y}*/ 0 /*{e-bdown-shadow-radius}*/ 	#fff /*{e-bdown-shadow-color}*/;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #f8d94c /*{e-bdown-background-start}*/), to( #fadb4e /*{e-bdown-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #f8d94c /*{e-bdown-background-start}*/, #fadb4e /*{e-bdown-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #f8d94c /*{e-bdown-background-start}*/, #fadb4e /*{e-bdown-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #f8d94c /*{e-bdown-background-start}*/, #fadb4e /*{e-bdown-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #f8d94c /*{e-bdown-background-start}*/, #fadb4e /*{e-bdown-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #f8d94c /*{e-bdown-background-start}*/, #fadb4e /*{e-bdown-background-end}*/);
}
.ui-btn-down-e:visited,
.ui-btn-down-e:hover,
.ui-btn-down-e a.ui-link-inherit {
	color: 					#333 /*{e-bdown-color}*/;
}
.ui-btn-up-e,
.ui-btn-hover-e,
.ui-btn-down-e {
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
	text-decoration: none;
}
/* Structure */
/* links within "buttons" 
-----------------------------------------------------------------------------------------------------------*/
a.ui-link-inherit {
	text-decoration: none !important;
}
/* Active class used as the "on" state across all themes
-----------------------------------------------------------------------------------------------------------*/
.ui-btn-active {
	border: 1px solid 		#2373a5 /*{global-active-border}*/;
	background: 			#5393c5 /*{global-active-background-color}*/;
	font-weight: bold;
	color: 					#fff /*{global-active-color}*/;
	cursor: pointer;
	text-shadow: 0 /*{global-active-shadow-x}*/ 1px /*{global-active-shadow-y}*/ 1px /*{global-active-shadow-radius}*/ #3373a5 /*{global-active-shadow-color}*/;
	text-decoration: none;
	background-image: -webkit-gradient(linear, left top, left bottom, from( #5393c5 /*{global-active-background-start}*/), to( #6facd5 /*{global-active-background-end}*/)); /* Saf4+, Chrome */
	background-image: -webkit-linear-gradient( #5393c5 /*{global-active-background-start}*/, #6facd5 /*{global-active-background-end}*/); /* Chrome 10+, Saf5.1+ */
	background-image:    -moz-linear-gradient( #5393c5 /*{global-active-background-start}*/, #6facd5 /*{global-active-background-end}*/); /* FF3.6 */
	background-image:     -ms-linear-gradient( #5393c5 /*{global-active-background-start}*/, #6facd5 /*{global-active-background-end}*/); /* IE10 */
	background-image:      -o-linear-gradient( #5393c5 /*{global-active-background-start}*/, #6facd5 /*{global-active-background-end}*/); /* Opera 11.10+ */
	background-image:         linear-gradient( #5393c5 /*{global-active-background-start}*/, #6facd5 /*{global-active-background-end}*/);
	font-family: Helvetica, Arial, sans-serif /*{global-font-family}*/;
}
.ui-btn-active:visited,
.ui-btn-active:hover,
.ui-btn-active a.ui-link-inherit {
	color: 					#fff /*{global-active-color}*/;
}
/* button inner top highlight
-----------------------------------------------------------------------------------------------------------*/
.ui-btn-inner {
	border-top: 1px solid 	#fff;
	border-color: 			rgba(255,255,255,.3);
}
/* corner rounding classes
-----------------------------------------------------------------------------------------------------------*/
.ui-corner-tl {
	-moz-border-radius-topleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-left-radius: 			.6em /*{global-radii-blocks}*/;
}
.ui-corner-tr {
	-moz-border-radius-topright: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-right-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-right-radius: 			.6em /*{global-radii-blocks}*/;
}
.ui-corner-bl {
	-moz-border-radius-bottomleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-bottom-left-radius: 			.6em /*{global-radii-blocks}*/;
}
.ui-corner-br {
	-moz-border-radius-bottomright: 	.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-right-radius: .6em /*{global-radii-blocks}*/;
	border-bottom-right-radius: 		.6em /*{global-radii-blocks}*/;
}
.ui-corner-top {
	-moz-border-radius-topleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-left-radius: 			.6em /*{global-radii-blocks}*/;
	-moz-border-radius-topright: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-right-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-right-radius: 			.6em /*{global-radii-blocks}*/;
}
.ui-corner-bottom {
	-moz-border-radius-bottomleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-bottom-left-radius: 			.6em /*{global-radii-blocks}*/;
	-moz-border-radius-bottomright: 	.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-right-radius: .6em /*{global-radii-blocks}*/;
	border-bottom-right-radius: 		.6em /*{global-radii-blocks}*/;
	}
.ui-corner-right {
	-moz-border-radius-topright: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-right-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-right-radius: 			.6em /*{global-radii-blocks}*/;
	-moz-border-radius-bottomright: 	.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-right-radius: .6em /*{global-radii-blocks}*/;
	border-bottom-right-radius: 		.6em /*{global-radii-blocks}*/;
}
.ui-corner-left {
	-moz-border-radius-topleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-top-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-top-left-radius: 			.6em /*{global-radii-blocks}*/;
	-moz-border-radius-bottomleft: 		.6em /*{global-radii-blocks}*/;
	-webkit-border-bottom-left-radius: 	.6em /*{global-radii-blocks}*/;
	border-bottom-left-radius: 			.6em /*{global-radii-blocks}*/;
}
.ui-corner-all {
	-moz-border-radius: 				.6em /*{global-radii-blocks}*/;
	-webkit-border-radius: 				.6em /*{global-radii-blocks}*/;
	border-radius: 						.6em /*{global-radii-blocks}*/;
}
.ui-corner-none {
	-moz-border-radius: 				   0;
	-webkit-border-radius: 				   0;
	border-radius: 						   0;
}
/* Form field separator
-----------------------------------------------------------------------------------------------------------*/
.ui-br {
	border-bottom: rgb(130,130,130);
	border-bottom: rgba(130,130,130,.3);
	border-bottom-width: 1px;
	border-bottom-style: solid;
}
/* Interaction cues
-----------------------------------------------------------------------------------------------------------*/
.ui-disabled {
	filter: Alpha(Opacity=30);
	opacity: .3;
	zoom: 1;
}
.ui-disabled,
.ui-disabled a {
	cursor: default !important;
	pointer-events: none;
}
/* Icons
-----------------------------------------------------------------------------------------------------------*/
.ui-icon,
.ui-icon-searchfield:after {
	background: 						#666 /*{global-icon-color}*/;
	background: 						rgba(0,0,0,.4) /*{global-icon-disc}*/;
	background-image: url(../images/icons-18-white.png) /*{global-icon-set}*/;
	background-repeat: no-repeat;
	-moz-border-radius: 				9px;
	-webkit-border-radius: 				9px;
	border-radius: 						9px;
}
/* Alt icon color
-----------------------------------------------------------------------------------------------------------*/
.ui-icon-alt {
	background: 						#fff;
	background: 						rgba(255,255,255,.3);
	background-image: url(../images/icons-18-black.png);
	background-repeat: no-repeat;
}
/* HD/"retina" sprite
-----------------------------------------------------------------------------------------------------------*/
@media only screen and (-webkit-min-device-pixel-ratio: 1.5),
       only screen and (min--moz-device-pixel-ratio: 1.5),
       only screen and (min-resolution: 240dpi) {
	
	.ui-icon-plus, .ui-icon-minus, .ui-icon-delete, .ui-icon-arrow-r,
	.ui-icon-arrow-l, .ui-icon-arrow-u, .ui-icon-arrow-d, .ui-icon-check,
	.ui-icon-gear, .ui-icon-refresh, .ui-icon-forward, .ui-icon-back,
	.ui-icon-grid, .ui-icon-star, .ui-icon-alert, .ui-icon-info, .ui-icon-home, .ui-icon-search, .ui-icon-searchfield:after, 
	.ui-icon-checkbox-off, .ui-icon-checkbox-on, .ui-icon-radio-off, .ui-icon-radio-on {
		background-image: url(../images/icons-36-white.png);
		-moz-background-size: 776px 18px;
		-o-background-size: 776px 18px;
		-webkit-background-size: 776px 18px;
		background-size: 776px 18px;
	}
	.ui-icon-alt {
		background-image: url(../images/icons-36-black.png);
	}
}
/* plus minus */
.ui-icon-plus {
	background-position: 	-0 50%;
}
.ui-icon-minus {
	background-position: 	-36px 50%;
}
/* delete/close */
.ui-icon-delete {
	background-position: 	-72px 50%;
}
/* arrows */
.ui-icon-arrow-r {
	background-position: 	-108px 50%;
}
.ui-icon-arrow-l {
	background-position: 	-144px 50%;
}
.ui-icon-arrow-u {
	background-position: 	-180px 50%;
}
.ui-icon-arrow-d {
	background-position: 	-216px 50%;
}
/* misc */
.ui-icon-check {
	background-position: 	-252px 50%;
}
.ui-icon-gear {
	background-position: 	-288px 50%;
}
.ui-icon-refresh {
	background-position: 	-324px 50%;
}
.ui-icon-forward {
	background-position: 	-360px 50%;
}
.ui-icon-back {
	background-position: 	-396px 50%;
}
.ui-icon-grid {
	background-position: 	-432px 50%;
}
.ui-icon-star {
	background-position: 	-468px 50%;
}
.ui-icon-alert {
	background-position: 	-504px 50%;
}
.ui-icon-info {
	background-position: 	-540px 50%;
}
.ui-icon-home {
	background-position: 	-576px 50%;
}
.ui-icon-search,
.ui-icon-searchfield:after {
	background-position: 	-612px 50%;
}
.ui-icon-checkbox-off {
	background-position: 	-684px 50%;
}
.ui-icon-checkbox-on {
	background-position: 	-648px 50%;
}
.ui-icon-radio-off {
	background-position: 	-756px 50%;
}
.ui-icon-radio-on {
	background-position: 	-720px 50%;
}
/* checks,radios */
.ui-checkbox .ui-icon,
.ui-selectmenu-list .ui-icon {
	-moz-border-radius: 3px;
	-webkit-border-radius: 3px;
	border-radius: 3px;
}
.ui-icon-checkbox-off,
.ui-icon-radio-off {
	background-color: transparent;	
}
.ui-checkbox-on .ui-icon,
.ui-radio-on .ui-icon {
	background-color: #4596ce /*{global-active-background-color}*/; /* NOTE: this hex should match the active state color. It's repeated here for cascade */
}
/* loading icon */
.ui-icon-loading {
	background: url(../images/ajax-loader.gif);
	background-size: 46px 46px;
}
/* Button corner classes
-----------------------------------------------------------------------------------------------------------*/
.ui-btn-corner-tl {
	-moz-border-radius-topleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-left-radius: 	1em /*{global-radii-buttons}*/;
	border-top-left-radius: 			1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-tr {
	-moz-border-radius-topright: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-right-radius: 	1em /*{global-radii-buttons}*/;
	border-top-right-radius: 			1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-bl {
	-moz-border-radius-bottomleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-left-radius: 	1em /*{global-radii-buttons}*/;
	border-bottom-left-radius: 			1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-br {
	-moz-border-radius-bottomright: 	1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-right-radius: 1em /*{global-radii-buttons}*/;
	border-bottom-right-radius: 		1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-top {
	-moz-border-radius-topleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-left-radius: 	1em /*{global-radii-buttons}*/;
	border-top-left-radius: 			1em /*{global-radii-buttons}*/;
	-moz-border-radius-topright: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-right-radius: 	1em /*{global-radii-buttons}*/;
	border-top-right-radius: 			1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-bottom {
	-moz-border-radius-bottomleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-left-radius: 	1em /*{global-radii-buttons}*/;
	border-bottom-left-radius: 			1em /*{global-radii-buttons}*/;
	-moz-border-radius-bottomright: 	1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-right-radius: 1em /*{global-radii-buttons}*/;
	border-bottom-right-radius: 		1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-right {
	 -moz-border-radius-topright: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-right-radius: 	1em /*{global-radii-buttons}*/;
	border-top-right-radius: 			1em /*{global-radii-buttons}*/;
	-moz-border-radius-bottomright: 	1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-right-radius: 1em /*{global-radii-buttons}*/;
	border-bottom-right-radius: 		1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-left {
	-moz-border-radius-topleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-top-left-radius: 	1em /*{global-radii-buttons}*/;
	border-top-left-radius: 			1em /*{global-radii-buttons}*/;
	-moz-border-radius-bottomleft: 		1em /*{global-radii-buttons}*/;
	-webkit-border-bottom-left-radius: 	1em /*{global-radii-buttons}*/;
	border-bottom-left-radius: 			1em /*{global-radii-buttons}*/;
}
.ui-btn-corner-all {
	-moz-border-radius: 				1em /*{global-radii-buttons}*/;
	-webkit-border-radius: 				1em /*{global-radii-buttons}*/;
	border-radius: 						1em /*{global-radii-buttons}*/;
}
/* radius clip workaround for cleaning up corner trapping */
.ui-corner-tl,
.ui-corner-tr,
.ui-corner-bl,
.ui-corner-br,
.ui-corner-top,
.ui-corner-bottom,
.ui-corner-right,
.ui-corner-left,
.ui-corner-all,
.ui-btn-corner-tl,
.ui-btn-corner-tr,
.ui-btn-corner-bl,
.ui-btn-corner-br,
.ui-btn-corner-top,
.ui-btn-corner-bottom,
.ui-btn-corner-right,
.ui-btn-corner-left,
.ui-btn-corner-all {
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding;
          background-clip: padding-box;
}
/* Overlay / modal
-----------------------------------------------------------------------------------------------------------*/
.ui-overlay {
	background: #666;
	filter: Alpha(Opacity=50);
	opacity: .5;
	position: absolute;
	width: 100%;
	height: 100%;
}
.ui-overlay-shadow {
	-moz-box-shadow: 0px 0px 12px 			rgba(0,0,0,.6);
	-webkit-box-shadow: 0px 0px 12px 		rgba(0,0,0,.6);
	box-shadow: 0px 0px 12px 				rgba(0,0,0,.6);
}
.ui-shadow {
	-moz-box-shadow: 0px 1px 4px /*{global-box-shadow-size}*/ 			rgba(0,0,0,.3) /*{global-box-shadow-color}*/;
	-webkit-box-shadow: 0px 1px 4px /*{global-box-shadow-size}*/ 		rgba(0,0,0,.3) /*{global-box-shadow-color}*/;
	box-shadow: 0px 1px 4px /*{global-box-shadow-size}*/ 				rgba(0,0,0,.3) /*{global-box-shadow-color}*/;
}
.ui-bar-a .ui-shadow,
.ui-bar-b .ui-shadow ,
.ui-bar-c .ui-shadow  {
	-moz-box-shadow: 0px 1px 0 				rgba(255,255,255,.3);
	-webkit-box-shadow: 0px 1px 0 			rgba(255,255,255,.3);
	box-shadow: 0px 1px 0 					rgba(255,255,255,.3);
}
.ui-shadow-inset {
	-moz-box-shadow: inset 0px 1px 4px 		rgba(0,0,0,.2);
	-webkit-box-shadow: inset 0px 1px 4px 	rgba(0,0,0,.2);
	box-shadow: inset 0px 1px 4px 			rgba(0,0,0,.2);
}
.ui-icon-shadow {
	-moz-box-shadow: 0px 1px 0 				rgba(255,255,255,.4) /*{global-icon-shadow}*/;
	-webkit-box-shadow: 0px 1px 0 			rgba(255,255,255,.4) /*{global-icon-shadow}*/;
	box-shadow: 0px 1px 0 					rgba(255,255,255,.4) /*{global-icon-shadow}*/;
}
/* Focus state - set here for specificity (note: these classes are added by JavaScript)
-----------------------------------------------------------------------------------------------------------*/
.ui-btn:focus, .ui-link-inherit:focus {
	outline: 0;
}
.ui-btn.ui-focus {
	z-index: 1;
}
.ui-focus,
.ui-btn:focus {
	-moz-box-shadow: inset 0px 0px 3px 		#387bbe /*{global-active-background-color}*/, 0px 0px 9px 		#387bbe /*{global-active-background-color}*/;
	-webkit-box-shadow: inset 0px 0px 3px 	#387bbe /*{global-active-background-color}*/, 0px 0px 9px 		#387bbe /*{global-active-background-color}*/;
	box-shadow: inset 0px 0px 3px 			#387bbe /*{global-active-background-color}*/, 0px 0px 9px 		#387bbe /*{global-active-background-color}*/;
}
.ui-input-text.ui-focus,
.ui-input-search.ui-focus {
	-moz-box-shadow: 0px 0px 12px 			#387bbe /*{global-active-background-color}*/;
	-webkit-box-shadow: 0px 0px 12px 		#387bbe /*{global-active-background-color}*/;
	box-shadow: 0px 0px 12px 					#387bbe /*{global-active-background-color}*/;	
}
/* unset box shadow in browsers that don't do it right
-----------------------------------------------------------------------------------------------------------*/
.ui-mobile-nosupport-boxshadow * {
	-moz-box-shadow: none !important;
	-webkit-box-shadow: none !important;
	box-shadow: none !important;
}
/* ...and bring back focus */
.ui-mobile-nosupport-boxshadow .ui-focus,
.ui-mobile-nosupport-boxshadow .ui-btn:focus,
.ui-mobile-nosupport-boxshadow .ui-link-inherit:focus {
	outline-width: 1px;
	outline-style: auto;
}
/* some unsets - more probably needed */
.ui-mobile, .ui-mobile body { height: 99.9%; }
.ui-mobile fieldset, .ui-page { padding: 0; margin: 0; }
.ui-mobile a img, .ui-mobile fieldset { border-width: 0; }
/* responsive page widths */
.ui-mobile-viewport { margin: 0; overflow-x: visible; -webkit-text-size-adjust: 100%; -ms-text-size-adjust:none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); }
/* Issue #2066 */
body.ui-mobile-viewport,
div.ui-mobile-viewport { overflow-x: hidden; }
/* "page" containers - full-screen views, one should always be in view post-pageload */
.ui-mobile [data-role=page], .ui-mobile [data-role=dialog], .ui-page { top: 0; left: 0; width: 100%; min-height: 100%; position: absolute; display: none; border: 0; }
.ui-mobile .ui-page-active { display: block; overflow: visible; }
/* on ios4, setting focus on the page element causes flashing during transitions when there is an outline, so we turn off outlines */
.ui-page { outline: none; }
/*orientations from js are available */
@media screen and (orientation: portrait){
.ui-mobile, .ui-mobile .ui-page { min-height: 420px; }
}
@media screen and (orientation: landscape){
.ui-mobile, .ui-mobile .ui-page { min-height: 300px; }
}
/* loading screen */
.ui-loading .ui-loader { display: block; }
.ui-loader { display: none; z-index: 9999999; position: fixed; top: 50%; left: 50%; border:0; }
.ui-loader-default { background: none; filter: Alpha(Opacity=18); opacity: .18; width: 46px; height: 46px; margin-left: -23px; margin-top: -23px; }
.ui-loader-verbose { width: 200px; filter: Alpha(Opacity=88); opacity: .88; box-shadow: 0 1px 1px -1px #fff; height: auto; margin-left: -110px; margin-top: -43px; padding: 10px; }
.ui-loader-default h1 { font-size: 0; width: 0; height: 0; overflow: hidden; }
.ui-loader-verbose h1 { font-size: 16px; margin: 0; text-align: center; }
.ui-loader .ui-icon { background-color: #000; display: block; margin: 0; width: 44px; height: 44px; padding: 1px; -webkit-border-radius: 36px; -moz-border-radius: 36px; border-radius: 36px; }
.ui-loader-verbose .ui-icon { margin: 0 auto 10px; filter: Alpha(Opacity=75); opacity: .75; }
.ui-loader-textonly { padding: 15px; margin-left: -115px; }
.ui-loader-textonly .ui-icon { display: none; }
.ui-loader-fakefix { position: absolute; }
/*fouc*/
.ui-mobile-rendering > * { visibility: hidden; }
/*headers, content panels*/
.ui-bar, .ui-body { position: relative; padding: .4em 15px; overflow: hidden; display: block; clear:both; }
.ui-bar { font-size: 16px; margin: 0; }
.ui-bar h1, .ui-bar h2, .ui-bar h3, .ui-bar h4, .ui-bar h5, .ui-bar h6 { margin: 0; padding: 0; font-size: 16px; display: inline-block; }
.ui-header, .ui-footer { position: relative; border-left-width: 0; border-right-width: 0; zoom: 1; }
.ui-header .ui-btn-left,
.ui-header .ui-btn-right,
.ui-footer .ui-btn-left,
.ui-footer .ui-btn-right { position: absolute; top: 3px; }
.ui-header .ui-btn-left,
.ui-footer .ui-btn-left { left: 5px; }
.ui-header .ui-btn-right,
.ui-footer .ui-btn-right { right: 5px; }
.ui-footer .ui-btn-icon-notext,
.ui-header .ui-btn-icon-notext { top: 6px; }
.ui-header .ui-title, .ui-footer .ui-title { min-height: 1.1em; text-align: center; font-size: 16px; display: block; margin: .6em 30% .8em; padding: 0; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; outline: 0 !important; }
.ui-footer .ui-title { margin: .6em 15px .8em; }
/*content area*/
.ui-content { border-width: 0; overflow: visible; overflow-x: hidden; padding: 15px; }
/* icons sizing */
.ui-icon { width: 18px; height: 18px; }
/* non-js content hiding */
.ui-nojs { position: absolute; left: -9999px; }
/* accessible content hiding */
.ui-hide-label label.ui-input-text, .ui-hide-label label.ui-select, .ui-hide-label label.ui-slider, .ui-hide-label label.ui-submit, .ui-hide-label .ui-controlgroup-label,
.ui-hidden-accessible { position: absolute !important; left: -9999px; clip: rect(1px 1px 1px 1px); clip: rect(1px,1px,1px,1px); }
/* Transitions originally inspired by those from jQtouch, nice work, folks */
.ui-mobile-viewport-transitioning,
.ui-mobile-viewport-transitioning .ui-page {
	width: 100%;
	height: 100%;
	overflow: hidden;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
.ui-page-pre-in {
	opacity: 0;
}
.in {
	-webkit-animation-timing-function: ease-out;
	-webkit-animation-duration: 350ms;
	-moz-animation-timing-function: ease-out;
	-moz-animation-duration: 350ms;
}
.out {
	-webkit-animation-timing-function: ease-in;
	-webkit-animation-duration: 225ms;
	-moz-animation-timing-function: ease-in;
	-moz-animation-duration: 225ms;
}
@-webkit-keyframes fadein {
    from { opacity: 0; }
    to { opacity: 1; }
}
@-moz-keyframes fadein {
    from { opacity: 0; }
    to { opacity: 1; }
}
@-webkit-keyframes fadeout {
    from { opacity: 1; }
    to { opacity: 0; }
}
@-moz-keyframes fadeout {
    from { opacity: 1; }
    to { opacity: 0; }
}
.fade.out {
	opacity: 0;
	-webkit-animation-duration: 125ms;
	-webkit-animation-name: fadeout;
	-moz-animation-duration: 125ms;
	-moz-animation-name: fadeout;
}
.fade.in {
	opacity: 1;
	-webkit-animation-duration: 225ms;
	-webkit-animation-name: fadein;
	-moz-animation-duration: 225ms;
	-moz-animation-name: fadein;
}
.pop {
	-webkit-transform-origin: 50% 50%;
	-moz-transform-origin: 50% 50%;
}
.pop.in {
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
    opacity: 1;
	-webkit-animation-name: popin;
	-moz-animation-name: popin;
	-webkit-animation-duration: 350ms;
	-moz-animation-duration: 350ms;
}
.pop.out {
	-webkit-animation-name: fadeout;
	-moz-animation-name: fadeout;
	opacity: 0;
	-webkit-animation-duration: 100ms;
	-moz-animation-duration: 100ms;
}
.pop.in.reverse {
	-webkit-animation-name: fadein;
	-moz-animation-name: fadein;
}
.pop.out.reverse {
	-webkit-transform: scale(.8);
	-moz-transform: scale(.8);
	-webkit-animation-name: popout;
	-moz-animation-name: popout;
}
@-webkit-keyframes popin {
    from {
        -webkit-transform: scale(.8);
        opacity: 0;
    }
    to {
        -webkit-transform: scale(1);
        opacity: 1;
    }
}
@-moz-keyframes popin {
    from {
        -moz-transform: scale(.8);
        opacity: 0;
    }
    to {
        -moz-transform: scale(1);
        opacity: 1;
    }
}
@-webkit-keyframes popout {
    from {
        -webkit-transform: scale(1);
        opacity: 1;
    }
    to {
        -webkit-transform: scale(.8);
        opacity: 0;
    }
}
@-moz-keyframes popout {
    from {
        -moz-transform: scale(1);
        opacity: 1;
    }
    to {
        -moz-transform: scale(.8);
        opacity: 0;
    }
}
/* keyframes for slidein from sides */
@-webkit-keyframes slideinfromright {
    from { -webkit-transform: translateX(100%); }
    to { -webkit-transform: translateX(0); }
}
@-moz-keyframes slideinfromright {
    from { -moz-transform: translateX(100%); }
    to { -moz-transform: translateX(0); }
}
@-webkit-keyframes slideinfromleft {
    from { -webkit-transform: translateX(-100%); }
    to { -webkit-transform: translateX(0); }
}
@-moz-keyframes slideinfromleft {
    from { -moz-transform: translateX(-100%); }
    to { -moz-transform: translateX(0); }
}
/* keyframes for slideout to sides */
@-webkit-keyframes slideouttoleft {
    from { -webkit-transform: translateX(0); }
    to { -webkit-transform: translateX(-100%); }
}
@-moz-keyframes slideouttoleft {
    from { -moz-transform: translateX(0); }
    to { -moz-transform: translateX(-100%); }
}
@-webkit-keyframes slideouttoright {
    from { -webkit-transform: translateX(0); }
    to { -webkit-transform: translateX(100%); }
}
@-moz-keyframes slideouttoright {
    from { -moz-transform: translateX(0); }
    to { -moz-transform: translateX(100%); }
}
.slide.out, .slide.in {
	-webkit-animation-timing-function: ease-out;
	-webkit-animation-duration: 350ms;
	-moz-animation-timing-function: ease-out;
	-moz-animation-duration: 350ms;
}
.slide.out {
	-webkit-transform: translateX(-100%);
	-webkit-animation-name: slideouttoleft;
	-moz-transform: translateX(-100%);
	-moz-animation-name: slideouttoleft;
}
.slide.in {
	-webkit-transform: translateX(0);
	-webkit-animation-name: slideinfromright;
	-moz-transform: translateX(0);
	-moz-animation-name: slideinfromright;
}
.slide.out.reverse {
	-webkit-transform: translateX(100%);
	-webkit-animation-name: slideouttoright;
	-moz-transform: translateX(100%);
	-moz-animation-name: slideouttoright;
}
.slide.in.reverse {
	-webkit-transform: translateX(0);
	-webkit-animation-name: slideinfromleft;
	-moz-transform: translateX(0);
	-moz-animation-name: slideinfromleft;
}
.slidefade.out {
	-webkit-transform: translateX(-100%);
	-webkit-animation-name: slideouttoleft;
	-moz-transform: translateX(-100%);
	-moz-animation-name: slideouttoleft;
	-webkit-animation-duration: 225ms;
	-moz-animation-duration: 225ms;
}
.slidefade.in {
	-webkit-transform: translateX(0);
	-webkit-animation-name: fadein;
	-moz-transform: translateX(0);
	-moz-animation-name: fadein;
	-webkit-animation-duration: 200ms;
	-moz-animation-duration: 200ms;
}
.slidefade.out.reverse {
	-webkit-transform: translateX(100%);
	-webkit-animation-name: slideouttoright;
	-moz-transform: translateX(100%);
	-moz-animation-name: slideouttoright;
	-webkit-animation-duration: 200ms;
	-moz-animation-duration: 200ms;
}
.slidefade.in.reverse {
	-webkit-transform: translateX(0);
	-webkit-animation-name: fadein;
	-moz-transform: translateX(0);
	-moz-animation-name: fadein;
	-webkit-animation-duration: 200ms;
	-moz-animation-duration: 200ms;
}
/* slide down */
.slidedown.out {
	-webkit-animation-name: fadeout;
	-moz-animation-name: fadeout;
	-webkit-animation-duration: 100ms;
	-moz-animation-duration: 100ms;
}
.slidedown.in {
	-webkit-transform: translateY(0);
	-webkit-animation-name: slideinfromtop;
	-moz-transform: translateY(0);
	-moz-animation-name: slideinfromtop;
	-webkit-animation-duration: 250ms;
	-moz-animation-duration: 250ms;
}
.slidedown.in.reverse {
	-webkit-animation-name: fadein;
	-moz-animation-name: fadein;
	-webkit-animation-duration: 150ms;
	-moz-animation-duration: 150ms;
}
.slidedown.out.reverse {
	-webkit-transform: translateY(-100%);
	-moz-transform: translateY(-100%);
	-webkit-animation-name: slideouttotop;
	-moz-animation-name: slideouttotop;
	-webkit-animation-duration: 200ms;
	-moz-animation-duration: 200ms;
}
@-webkit-keyframes slideinfromtop {
    from { -webkit-transform: translateY(-100%); }
    to { -webkit-transform: translateY(0); }
}
@-moz-keyframes slideinfromtop {
    from { -moz-transform: translateY(-100%); }
    to { -moz-transform: translateY(0); }
}
@-webkit-keyframes slideouttotop {
    from { -webkit-transform: translateY(0); }
    to { -webkit-transform: translateY(-100%); }
}
@-moz-keyframes slideouttotop {
    from { -moz-transform: translateY(0); }
    to { -moz-transform: translateY(-100%); }
}
/* slide up */
.slideup.out {
	-webkit-animation-name: fadeout;
	-moz-animation-name: fadeout;
	-webkit-animation-duration: 100ms;
	-moz-animation-duration: 100ms;
}
.slideup.in {
	-webkit-transform: translateY(0);
	-webkit-animation-name: slideinfrombottom;
	-moz-transform: translateY(0);
	-moz-animation-name: slideinfrombottom;
	-webkit-animation-duration: 250ms;
	-moz-animation-duration: 250ms;
}
.slideup.in.reverse {
	-webkit-animation-name: fadein;
	-moz-animation-name: fadein;
	-webkit-animation-duration: 150ms;
	-moz-animation-duration: 150ms;
}
.slideup.out.reverse {
	-webkit-transform: translateY(100%);
	-moz-transform: translateY(100%);
	-webkit-animation-name: slideouttobottom;
	-moz-animation-name: slideouttobottom;
	-webkit-animation-duration: 200ms;
	-moz-animation-duration: 200ms;
}
@-webkit-keyframes slideinfrombottom {
    from { -webkit-transform: translateY(100%); }
    to { -webkit-transform: translateY(0); }
}
@-moz-keyframes slideinfrombottom {
    from { -moz-transform: translateY(100%); }
    to { -moz-transform: translateY(0); }
}
@-webkit-keyframes slideouttobottom {
    from { -webkit-transform: translateY(0); }
    to { -webkit-transform: translateY(100%); }
}
@-moz-keyframes slideouttobottom {
    from { -moz-transform: translateY(0); }
    to { -moz-transform: translateY(100%); }
}
/* The properties in this rule are only necessary for the 'flip' transition.
 * We need specify the perspective to create a projection matrix. This will add
 * some depth as the element flips. The depth number represents the distance of
 * the viewer from the z-plane. According to the CSS3 spec, 1000 is a moderate
 * value.
 */
.viewport-flip {
	-webkit-perspective: 1000;
	-moz-perspective: 1000;
	position: absolute;
}
.flip {
	-webkit-backface-visibility:hidden;
	-webkit-transform:translateX(0); /* Needed to work around an iOS 3.1 bug that causes listview thumbs to disappear when -webkit-visibility:hidden is used. */
	-moz-backface-visibility:hidden;
	-moz-transform:translateX(0);
}
.flip.out {
	-webkit-transform: rotateY(-90deg) scale(.9);
	-webkit-animation-name: flipouttoleft;
	-webkit-animation-duration: 175ms;
	-moz-transform: rotateY(-90deg) scale(.9);
	-moz-animation-name: flipouttoleft;
	-moz-animation-duration: 175ms;
}
.flip.in {
	-webkit-animation-name: flipintoright;
	-webkit-animation-duration: 225ms;
	-moz-animation-name: flipintoright;
	-moz-animation-duration: 225ms;
}
.flip.out.reverse {
	-webkit-transform: rotateY(90deg) scale(.9);
	-webkit-animation-name: flipouttoright;
	-moz-transform: rotateY(90deg) scale(.9);
	-moz-animation-name: flipouttoright;
}
.flip.in.reverse {
	-webkit-animation-name: flipintoleft;
	-moz-animation-name: flipintoleft;
}
@-webkit-keyframes flipouttoleft {
    from { -webkit-transform: rotateY(0); }
    to { -webkit-transform: rotateY(-90deg) scale(.9); }
}
@-moz-keyframes flipouttoleft {
    from { -moz-transform: rotateY(0); }
    to { -moz-transform: rotateY(-90deg) scale(.9); }
}
@-webkit-keyframes flipouttoright {
    from { -webkit-transform: rotateY(0) ; }
    to { -webkit-transform: rotateY(90deg) scale(.9); }
}
@-moz-keyframes flipouttoright {
    from { -moz-transform: rotateY(0); }
    to { -moz-transform: rotateY(90deg) scale(.9); }
}
@-webkit-keyframes flipintoleft {
    from { -webkit-transform: rotateY(-90deg) scale(.9); }
    to { -webkit-transform: rotateY(0); }
}
@-moz-keyframes flipintoleft {
    from { -moz-transform: rotateY(-90deg) scale(.9); }
    to { -moz-transform: rotateY(0); }
}
@-webkit-keyframes flipintoright {
    from { -webkit-transform: rotateY(90deg) scale(.9); }
    to { -webkit-transform: rotateY(0); }
}
@-moz-keyframes flipintoright {
    from { -moz-transform: rotateY(90deg) scale(.9); }
    to { -moz-transform: rotateY(0); }
}
/* The properties in this rule are only necessary for the 'flip' transition.
 * We need specify the perspective to create a projection matrix. This will add
 * some depth as the element flips. The depth number represents the distance of
 * the viewer from the z-plane. According to the CSS3 spec, 1000 is a moderate
 * value.
 */
.viewport-turn {
	-webkit-perspective: 1000;
	-moz-perspective: 1000;
	position: absolute;
}
.turn {
	-webkit-backface-visibility:hidden;
	-webkit-transform:translateX(0); /* Needed to work around an iOS 3.1 bug that causes listview thumbs to disappear when -webkit-visibility:hidden is used. */
	-webkit-transform-origin: 0;
	
	-moz-backface-visibility:hidden;
	-moz-transform:translateX(0); /* Needed to work around an iOS 3.1 bug that causes listview thumbs to disappear when -webkit-visibility:hidden is used. */
	-moz-transform-origin: 0;
}
.turn.out {
	-webkit-transform: rotateY(-90deg) scale(.9);
	-webkit-animation-name: flipouttoleft;
	-moz-transform: rotateY(-90deg) scale(.9);
	-moz-animation-name: flipouttoleft;
	-webkit-animation-duration: 125ms;
	-moz-animation-duration: 125ms;
}
.turn.in {
	-webkit-animation-name: flipintoright;
	-moz-animation-name: flipintoright;
	-webkit-animation-duration: 250ms;
	-moz-animation-duration: 250ms;
	
}
.turn.out.reverse {
	-webkit-transform: rotateY(90deg) scale(.9);
	-webkit-animation-name: flipouttoright;
	-moz-transform: rotateY(90deg) scale(.9);
	-moz-animation-name: flipouttoright;
}
.turn.in.reverse {
	-webkit-animation-name: flipintoleft;
	-moz-animation-name: flipintoleft;
}
@-webkit-keyframes flipouttoleft {
    from { -webkit-transform: rotateY(0); }
    to { -webkit-transform: rotateY(-90deg) scale(.9); }
}
@-moz-keyframes flipouttoleft {
    from { -moz-transform: rotateY(0); }
    to { -moz-transform: rotateY(-90deg) scale(.9); }
}
@-webkit-keyframes flipouttoright {
    from { -webkit-transform: rotateY(0) ; }
    to { -webkit-transform: rotateY(90deg) scale(.9); }
}
@-moz-keyframes flipouttoright {
    from { -moz-transform: rotateY(0); }
    to { -moz-transform: rotateY(90deg) scale(.9); }
}
@-webkit-keyframes flipintoleft {
    from { -webkit-transform: rotateY(-90deg) scale(.9); }
    to { -webkit-transform: rotateY(0); }
}
@-moz-keyframes flipintoleft {
    from { -moz-transform: rotateY(-90deg) scale(.9); }
    to { -moz-transform: rotateY(0); }
}
@-webkit-keyframes flipintoright {
    from { -webkit-transform: rotateY(90deg) scale(.9); }
    to { -webkit-transform: rotateY(0); }
}
@-moz-keyframes flipintoright {
    from { -moz-transform: rotateY(90deg) scale(.9); }
    to { -moz-transform: rotateY(0); }
}
/* flow transition */
.flow {
	-webkit-transform-origin: 50% 30%;
	-moz-transform-origin: 50% 30%;	
	-webkit-box-shadow: 0 0 20px rgba(0,0,0,.4);
	-moz-box-shadow: 0 0 20px rgba(0,0,0,.4);
}
.ui-dialog.flow {
	-webkit-transform-origin: none;
	-moz-transform-origin: none;	
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}
.flow.out {
	-webkit-transform: translateX(-100%) scale(.7);
	-webkit-animation-name: flowouttoleft;
	-webkit-animation-timing-function: ease;
	-webkit-animation-duration: 350ms;
	-moz-transform: translateX(-100%) scale(.7);
	-moz-animation-name: flowouttoleft;
	-moz-animation-timing-function: ease;
	-moz-animation-duration: 350ms;
}
.flow.in {
	-webkit-transform: translateX(0) scale(1);
	-webkit-animation-name: flowinfromright;
	-webkit-animation-timing-function: ease;
	-webkit-animation-duration: 350ms;
	-moz-transform: translateX(0) scale(1);
	-moz-animation-name: flowinfromright;
	-moz-animation-timing-function: ease;
	-moz-animation-duration: 350ms;
}
.flow.out.reverse {
	-webkit-transform: translateX(100%);
	-webkit-animation-name: flowouttoright;
	-moz-transform: translateX(100%);
	-moz-animation-name: flowouttoright;
}
.flow.in.reverse {
	-webkit-animation-name: flowinfromleft;
	-moz-animation-name: flowinfromleft;
}
@-webkit-keyframes flowouttoleft {
    0% { -webkit-transform: translateX(0) scale(1); }
	60%, 70% { -webkit-transform: translateX(0) scale(.7); }
    100% { -webkit-transform: translateX(-100%) scale(.7); }
}
@-moz-keyframes flowouttoleft {
    0% { -moz-transform: translateX(0) scale(1); }
	60%, 70% { -moz-transform: translateX(0) scale(.7); }
    100% { -moz-transform:  translateX(-100%) scale(.7); }
}
@-webkit-keyframes flowouttoright {
    0% { -webkit-transform: translateX(0) scale(1); }
	60%, 70% { -webkit-transform: translateX(0) scale(.7); }
    100% { -webkit-transform:  translateX(100%) scale(.7); }
}
@-moz-keyframes flowouttoright {
    0% { -moz-transform: translateX(0) scale(1); }
	60%, 70% { -moz-transform: translateX(0) scale(.7); }
    100% { -moz-transform:  translateX(100%) scale(.7); }
}
@-webkit-keyframes flowinfromleft {
    0% { -webkit-transform: translateX(-100%) scale(.7); }
	30%, 40% { -webkit-transform: translateX(0) scale(.7); }
    100% { -webkit-transform: translateX(0) scale(1); }
}
@-moz-keyframes flowinfromleft {
    0% { -moz-transform: translateX(-100%) scale(.7); }
	30%, 40% { -moz-transform: translateX(0) scale(.7); }
    100% { -moz-transform: translateX(0) scale(1); }
}
@-webkit-keyframes flowinfromright {
    0% { -webkit-transform: translateX(100%) scale(.7); }
	30%, 40% { -webkit-transform: translateX(0) scale(.7); }
    100% { -webkit-transform: translateX(0) scale(1); }
}
@-moz-keyframes flowinfromright {
    0% { -moz-transform: translateX(100%) scale(.7); }
	30%, 40% { -moz-transform: translateX(0) scale(.7); }
    100% { -moz-transform: translateX(0) scale(1); }
}
/* content configurations. */
.ui-grid-a, .ui-grid-b, .ui-grid-c, .ui-grid-d { overflow: hidden; }
.ui-block-a, .ui-block-b, .ui-block-c, .ui-block-d, .ui-block-e { margin: 0; padding: 0; border: 0; float: left; min-height: 1px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; -ms-box-sizing: border-box; box-sizing: border-box; }
/* grid solo: 100 - single item fallback */
.ui-grid-solo .ui-block-a { display: block; float: none; }
/* Lower percentages for older browsers (i.e. IE7) to prevent wrapping. -.5px to fix BB5 wrap issue. */
/* grid a: 50/50 */
.ui-grid-a .ui-block-a, .ui-grid-a .ui-block-b { width: 49.95%; }
.ui-grid-a > :nth-child(n) { width: 50%; margin-right: -.5px; }
.ui-grid-a .ui-block-a { clear: left; }
/* grid b: 33/33/33 */
.ui-grid-b .ui-block-a, .ui-grid-b .ui-block-b, .ui-grid-b .ui-block-c { width: 33.25%; }
.ui-grid-b > :nth-child(n) { width: 33.333%; margin-right: -.5px; }
.ui-grid-b .ui-block-a { clear: left; }
/* grid c: 25/25/25/25 */
.ui-grid-c .ui-block-a, .ui-grid-c .ui-block-b, .ui-grid-c .ui-block-c, .ui-grid-c .ui-block-d { width: 24.925%; }
.ui-grid-c > :nth-child(n) { width: 25%; margin-right: -.5px; }
.ui-grid-c .ui-block-a { clear: left; }
/* grid d: 20/20/20/20/20 */
.ui-grid-d .ui-block-a, .ui-grid-d .ui-block-b, .ui-grid-d .ui-block-c, .ui-grid-d .ui-block-d, .ui-grid-d .ui-block-e { width: 19.925%; }
.ui-grid-d > :nth-child(n) { width: 20%; }
.ui-grid-d .ui-block-a { clear: left; }
/* fixed page header & footer configuration */
.ui-header-fixed,
.ui-footer-fixed {
	left: 0;
	right: 0;
	width: 100%;
	position: fixed;
	z-index: 1000;
}
.ui-header-fixed {
	top: 0;
}
.ui-footer-fixed {
	bottom: 0;
}
.ui-header-fullscreen,
.ui-footer-fullscreen {
	filter: Alpha(Opacity=90);
	opacity: .9;
}
.ui-page-header-fixed {
	padding-top: 2.6875em;
}
.ui-page-footer-fixed {
	padding-bottom: 2.6875em;
}
.ui-page-header-fullscreen .ui-content,
.ui-page-footer-fullscreen .ui-content {
	padding: 0;
}
.ui-fixed-hidden {
	position: absolute;
}
.ui-page-header-fullscreen .ui-fixed-hidden,
.ui-page-footer-fullscreen .ui-fixed-hidden {
	left: -9999px;
}
.ui-header-fixed .ui-btn,
.ui-footer-fixed .ui-btn { 
	z-index: 10;
}
.ui-navbar { max-width: 100%; }
.ui-navbar.ui-mini { margin: 0; }
.ui-navbar ul:before, .ui-navbar ul:after { content: " "; display: table; }
.ui-navbar ul:after { clear: both; }
.ui-navbar ul { list-style:none; margin: 0; padding: 0; position: relative; display: block; border: 0; max-width: 100%; overflow: visible; zoom: 1; }
.ui-navbar li .ui-btn { display: block; text-align: center; margin: 0 -1px 0 0; border-right-width: 0; }
.ui-navbar li .ui-btn-icon-right .ui-icon { right: 6px; }
/* add border if not in header/footer (full width) */
.ui-navbar li:last-child .ui-btn,
.ui-navbar .ui-grid-duo .ui-block-b .ui-btn { margin-right: 0; border-right-width: 1px; }
.ui-header .ui-navbar li:last-child .ui-btn,
.ui-footer .ui-navbar li:last-child .ui-btn,
.ui-header .ui-navbar .ui-grid-duo .ui-block-b .ui-btn,
.ui-footer .ui-navbar .ui-grid-duo .ui-block-b .ui-btn { margin-right: -1px; border-right-width: 0; }
.ui-navbar .ui-grid-duo li.ui-block-a:last-child .ui-btn { margin-right: -1px; border-right-width: 1px; }
.ui-header .ui-navbar li .ui-btn,
.ui-footer .ui-navbar li .ui-btn { border-top-width: 0; border-bottom-width: 0; }
/* fixing gaps caused by subpixel problem */
.ui-header .ui-navbar .ui-grid-b li.ui-block-c .ui-btn,
.ui-footer .ui-navbar .ui-grid-b li.ui-block-c .ui-btn { margin-right: -5px; }
.ui-header .ui-navbar .ui-grid-c li.ui-block-d .ui-btn,
.ui-footer .ui-navbar .ui-grid-c li.ui-block-d .ui-btn,
.ui-header .ui-navbar .ui-grid-d li.ui-block-e .ui-btn,
.ui-footer .ui-navbar .ui-grid-d li.ui-block-e .ui-btn { margin-right: -4px; }
.ui-header .ui-navbar .ui-grid-b li.ui-block-c .ui-btn-icon-right .ui-icon,
.ui-footer .ui-navbar .ui-grid-b li.ui-block-c .ui-btn-icon-right .ui-icon,
.ui-header .ui-navbar .ui-grid-c li.ui-block-d .ui-btn-icon-right .ui-icon,
.ui-footer .ui-navbar .ui-grid-c li.ui-block-d .ui-btn-icon-right .ui-icon,
.ui-header .ui-navbar .ui-grid-d li.ui-block-e .ui-btn-icon-right .ui-icon,
.ui-footer .ui-navbar .ui-grid-d li.ui-block-e .ui-btn-icon-right .ui-icon { right: 8px; }
.ui-navbar li .ui-btn .ui-btn-inner { padding-top: .7em; padding-bottom: .8em }
.ui-navbar li .ui-btn-icon-top .ui-btn-inner { padding-top: 30px; }
.ui-navbar li .ui-btn-icon-bottom .ui-btn-inner { padding-bottom: 30px; }
.ui-btn { display: block; text-align: center; cursor:pointer; position: relative; margin: .5em 0; padding: 0; }
.ui-mini { margin-top: .25em; margin-bottom: .25em; }
.ui-btn-left, .ui-btn-right, .ui-input-clear, .ui-btn-inline,
.ui-grid-a .ui-btn, .ui-grid-b .ui-btn, .ui-grid-c .ui-btn, .ui-grid-d .ui-btn, .ui-grid-e .ui-btn, .ui-grid-solo .ui-btn { margin-right: 5px; margin-left: 5px; }
.ui-btn-inner { font-size: 14px; padding: .6em 20px; min-width: .75em; display: block; position: relative; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; zoom: 1; }
.ui-btn input, .ui-btn button { z-index: 2; }
.ui-btn-left, .ui-btn-right, .ui-btn-inline { display: inline-block; vertical-align: middle; }
.ui-mobile .ui-btn-left, .ui-mobile .ui-btn-right { margin: 0; } /* .ui-mobile to increase specificity level */
.ui-btn-block { display: block; }
.ui-header > .ui-btn,
.ui-footer > .ui-btn { display: inline-block; margin: 0; }
.ui-header .ui-btn-block,
.ui-footer .ui-btn-block { display: block; }
.ui-header .ui-btn-inner,
.ui-footer .ui-btn-inner,
.ui-mini .ui-btn-inner { font-size: 12.5px; padding: .55em 11px .5em; }
.ui-fullsize .ui-btn-inner,
.ui-fullsize .ui-btn-inner { font-size: 16px; padding: .6em 20px; }
.ui-btn-icon-notext { width: 24px; height: 24px; }
.ui-btn-icon-notext .ui-btn-inner { padding: 0; height: 100%; }
.ui-btn-icon-notext .ui-btn-inner .ui-icon { margin: 2px 1px 2px 3px; float: left; }
.ui-btn-text { position: relative; z-index: 1; width: 100%; -moz-user-select: none; -webkit-user-select: none; -ms-user-select: none; }
.ui-btn-icon-notext .ui-btn-text { position: absolute; left: -9999px; }
.ui-btn-icon-left .ui-btn-inner { padding-left: 40px; }
.ui-btn-icon-right .ui-btn-inner { padding-right: 40px; }
.ui-btn-icon-top .ui-btn-inner { padding-top: 40px; }
.ui-btn-icon-bottom .ui-btn-inner { padding-bottom: 40px; }
.ui-header .ui-btn-icon-left .ui-btn-inner,
.ui-footer .ui-btn-icon-left .ui-btn-inner,
.ui-mini.ui-btn-icon-left .ui-btn-inner,
.ui-mini .ui-btn-icon-left .ui-btn-inner { padding-left: 30px; }
.ui-header .ui-btn-icon-right .ui-btn-inner,
.ui-footer .ui-btn-icon-right .ui-btn-inner,
.ui-mini.ui-btn-icon-right .ui-btn-inner,
.ui-mini .ui-btn-icon-right .ui-btn-inner { padding-right: 30px; }
.ui-header .ui-btn-icon-top .ui-btn-inner,
.ui-footer .ui-btn-icon-top .ui-btn-inner { padding: 30px 3px .5em 3px; }
.ui-mini.ui-btn-icon-top .ui-btn-inner,
.ui-mini .ui-btn-icon-top .ui-btn-inner { padding-top: 30px; }
.ui-header .ui-btn-icon-bottom .ui-btn-inner,
.ui-footer .ui-btn-icon-bottom .ui-btn-inner { padding: .55em 3px 30px 3px; }
.ui-mini.ui-btn-icon-bottom .ui-btn-inner,
.ui-mini .ui-btn-icon-bottom .ui-btn-inner { padding-bottom: 30px; }
/*btn icon positioning*/
.ui-btn-icon-notext .ui-icon { display: block; z-index: 0;}
.ui-btn-icon-left > .ui-btn-inner > .ui-icon, .ui-btn-icon-right > .ui-btn-inner > .ui-icon { position: absolute; top: 50%; margin-top: -9px; }
.ui-btn-icon-top .ui-btn-inner .ui-icon, .ui-btn-icon-bottom .ui-btn-inner .ui-icon { position: absolute; left: 50%; margin-left: -9px; }
.ui-btn-icon-left .ui-icon { left: 10px; }
.ui-btn-icon-right .ui-icon { right: 10px; }
.ui-btn-icon-top .ui-icon { top: 10px; }
.ui-btn-icon-bottom .ui-icon { top: auto; bottom: 10px; }
.ui-header .ui-btn-icon-left .ui-icon,
.ui-footer .ui-btn-icon-left .ui-icon,
.ui-mini.ui-btn-icon-left .ui-icon,
.ui-mini .ui-btn-icon-left .ui-icon { left: 5px; }
.ui-header .ui-btn-icon-right .ui-icon,
.ui-footer .ui-btn-icon-right .ui-icon,
.ui-mini.ui-btn-icon-right .ui-icon,
.ui-mini .ui-btn-icon-right .ui-icon { right: 5px; }
.ui-header .ui-btn-icon-top .ui-icon,
.ui-footer .ui-btn-icon-top .ui-icon,
.ui-mini.ui-btn-icon-top .ui-icon,
.ui-mini .ui-btn-icon-top .ui-icon { top: 5px; }
.ui-header .ui-btn-icon-bottom .ui-icon,
.ui-footer .ui-btn-icon-bottom .ui-icon,
.ui-mini.ui-btn-icon-bottom .ui-icon,
.ui-mini .ui-btn-icon-bottom .ui-icon { bottom: 5px; }
/*hiding native button,inputs */
.ui-btn-hidden { position: absolute; top: 0; left: 0; width: 100%; height: 100%; -webkit-appearance: none; cursor: pointer; background: #fff; background: rgba(255,255,255,0); filter: Alpha(Opacity=0); opacity: .1; font-size: 1px; border: none; text-indent: -9999px; }
/* Fixes IE/WP filter alpha opacity bugs */
.ui-disabled .ui-btn-hidden { display: none; }
.ui-disabled { z-index: 1; }
.ui-field-contain .ui-btn.ui-submit { margin: 0; }
label.ui-submit { font-size: 16px; line-height: 1.4; font-weight: normal; margin: 0 0 .3em; display: block; }
@media all and (min-width: 450px){
	.ui-field-contain label.ui-submit { vertical-align: top; display: inline-block; width: 20%; margin: 0 2% 0 0; }
	.ui-field-contain .ui-btn.ui-submit { width: 78%; display: inline-block; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; -ms-box-sizing: border-box; box-sizing: border-box; }
	.ui-hide-label .ui-btn.ui-submit { width: auto; display: block; }
}
.ui-collapsible-inset { margin: .5em 0; }
.ui-collapsible-heading { font-size: 16px; display: block; margin: 0 -15px; padding: 0; position: relative; }
.ui-collapsible-inset .ui-collapsible-heading { margin: 0; }
.ui-collapsible-heading .ui-btn { text-align: left; margin: 0; border-left-width: 0; border-right-width: 0; }
.ui-collapsible-inset .ui-collapsible-heading .ui-btn { border-right-width: 1px; border-left-width: 1px; }
.ui-collapsible-collapsed + .ui-collapsible:not(.ui-collapsible-inset) .ui-collapsible-heading .ui-btn { border-top-width: 0; }
.ui-collapsible-set .ui-collapsible:not(.ui-collapsible-inset) .ui-collapsible-heading .ui-btn { border-top-width: 1px; }
.ui-collapsible-heading .ui-btn-inner,
.ui-collapsible-heading .ui-btn-icon-left .ui-btn-inner { padding-left: 40px; }
.ui-collapsible-heading .ui-btn-icon-right .ui-btn-inner { padding-left: 12px; padding-right: 40px; }
.ui-collapsible-heading .ui-btn-icon-top .ui-btn-inner,
.ui-collapsible-heading .ui-btn-icon-bottom .ui-btn-inner { padding-right: 40px; text-align: center; }
.ui-collapsible-heading .ui-btn span.ui-btn { position: absolute; left: 6px; top: 50%; margin: -12px 0 0 0; width: 20px; height: 20px; padding: 1px 0px 1px 2px; text-indent: -9999px; }
.ui-collapsible-heading .ui-btn span.ui-btn .ui-btn-inner { padding: 10px 0; }
.ui-collapsible-heading .ui-btn span.ui-btn .ui-icon { left: 0; margin-top: -10px; }
.ui-collapsible-heading-status { position: absolute; top: -9999px; left:0px; }
.ui-collapsible-content {
	display: block;
	margin: 0 -15px;	
	padding: 10px 15px;
	border-left-width: 0;
	border-right-width: 0;
	border-top: none;      /* Overrides ui-body-* */
	background-image: none; /* Overrides ui-body-* */
}
.ui-collapsible-inset .ui-collapsible-content { margin: 0; border-right-width: 1px; border-left-width: 1px; }
.ui-collapsible-content-collapsed { display: none; }
.ui-collapsible-set { margin: .5em 0; }
.ui-collapsible-set .ui-collapsible { margin: -1px 0 0; }
.ui-collapsible-set .ui-collapsible:first-child { margin-top: 0; }
.ui-controlgroup, fieldset.ui-controlgroup { padding: 0; margin: .5em 0; margin-bottom:0px; zoom: 1; }
.ui-controlgroup.ui-mini, fieldset.ui-controlgroup.ui-mini { margin: .25em 0; }
.ui-field-contain .ui-controlgroup, .ui-field-contain fieldset.ui-controlgroup { margin: 0; }
.ui-bar .ui-controlgroup { margin: 0 5px; }
.ui-controlgroup-label { font-size: 16px; line-height: 1.4; font-weight: normal; margin: 0 0 .4em; }
.ui-controlgroup li { list-style: none; }
.ui-controlgroup-vertical .ui-btn,
.ui-controlgroup-vertical .ui-checkbox, .ui-controlgroup-vertical .ui-radio { margin: 0; border-bottom-width: 0; }
.ui-controlgroup-vertical .ui-controlgroup-last { border-bottom-width: 1px; }
.ui-controlgroup-controls label.ui-select { position: absolute; left: -9999px; }
.ui-controlgroup .ui-btn-icon-notext { width: auto; height: auto; top: auto; }
.ui-controlgroup .ui-btn-icon-notext .ui-btn-inner { height: 20px; padding: .6em 20px .6em 20px }
.ui-controlgroup-horizontal .ui-btn-icon-notext .ui-btn-inner { width: 18px; }
.ui-controlgroup.ui-mini .ui-btn-icon-notext .ui-btn-inner,
.ui-header .ui-controlgroup .ui-btn-icon-notext .ui-btn-inner,
.ui-footer .ui-controlgroup .ui-btn-icon-notext .ui-btn-inner { height: 16px; padding: .55em 11px .5em 11px; }
.ui-controlgroup .ui-btn-icon-notext .ui-btn-inner .ui-icon { position: absolute; top: 50%; right: 50%; margin: -9px -9px 0 0; }
.ui-controlgroup-horizontal .ui-controlgroup-controls:before,
.ui-controlgroup-horizontal .ui-controlgroup-controls:after { content: ""; display: table; }
.ui-controlgroup-horizontal .ui-controlgroup-controls:after { clear: both; }
.ui-controlgroup-horizontal .ui-controlgroup-controls { display: inline-block; vertical-align: middle; zoom: 1; }
.ui-controlgroup-horizontal .ui-btn-inner { text-align: center; }
.ui-controlgroup-horizontal.ui-mini .ui-btn-inner { height: 16px; line-height: 16px; }
.ui-controlgroup-horizontal .ui-btn, .ui-controlgroup-horizontal .ui-select,
.ui-controlgroup-horizontal .ui-checkbox, .ui-controlgroup-horizontal .ui-radio { float: left; clear: none; margin: 0 -1px 0 0; }
.ui-controlgroup-horizontal .ui-select .ui-btn,
.ui-controlgroup-horizontal .ui-checkbox .ui-btn, .ui-controlgroup-horizontal .ui-radio .ui-btn { float: none; margin: 0; }
.ui-controlgroup-horizontal .ui-controlgroup-last, .ui-controlgroup-horizontal .ui-select:last-child,
.ui-controlgroup-horizontal .ui-checkbox:last-child, .ui-controlgroup-horizontal .ui-radio:last-child { margin-right: 0; }
.ui-controlgroup .ui-checkbox label, .ui-controlgroup .ui-radio label { font-size: 16px; }
@media all and (min-width: 450px){
	.ui-field-contain .ui-controlgroup-label { vertical-align: top; display: inline-block; width: 20%; margin: 0 2% 0 0; }
	.ui-field-contain .ui-controlgroup-controls { width: 78%; display: inline-block; }
	.ui-field-contain .ui-controlgroup .ui-select { width: 100%; display: block; } 
	.ui-field-contain .ui-controlgroup-horizontal .ui-select { width: auto; }
	.ui-hide-label .ui-controlgroup-controls { width: 100%; }
}	
.ui-dialog {
	 background: none !important; /* this is to ensure that dialog theming does not apply (by default at least) on the page div */
}
.ui-dialog-contain {
	width: 92.5%;
	max-width: 500px;
	margin: 10% auto 15px auto;
	padding: 0;
	position: relative;
	top: -15px;
}
.ui-dialog-contain > .ui-header, 
.ui-dialog-contain > .ui-content, 
.ui-dialog-contain > .ui-footer { 
	display: block;
	position: relative; 
	width: auto;
	margin: 0;
}
.ui-dialog-contain > .ui-header {
	border: none;
	overflow: hidden;
	z-index: 10; 
	padding: 0;
}
.ui-dialog-contain > .ui-content { 
	padding: 15px; 
}
.ui-dialog-contain > .ui-footer {
	z-index: 10; 
	padding: 0 15px; 
}
.ui-popup-open .ui-header-fixed,
.ui-popup-open .ui-footer-fixed {
	position: absolute !important; 	/* See line #553 of popup.js */
}
.ui-popup-screen {
	background-image: url(data:image/gif;base64,R0lGODlhAQABAID/AMDAwAAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==); /* Necessary to set some form of background to ensure element is clickable in IE6/7. While legacy IE won't understand the data-URI'd image, it ensures no additional requests occur in all other browsers with little overhead. */
	top: 0px;
	left: 0px;
	right: 0px;
	bottom: 1px;
	position: absolute;
	filter: Alpha(Opacity=0);
	opacity: 0;
	z-index: 1099;
}
.ui-popup-screen.in {
	opacity: 0.5;
	filter: Alpha(Opacity=50);
}
.ui-popup-screen.out {
	opacity: 0;
	filter: Alpha(Opacity=0);
}
.ui-popup-container {
	z-index: 1100;
	display: inline-block;
	position: absolute;
	padding: 0;
	outline: 0;
}
.ui-popup {
	position: relative;
}
.ui-popup.ui-content,
.ui-popup .ui-content {
	overflow: visible;
}
.ui-popup > p,
.ui-popup > h1,
.ui-popup > h2,
.ui-popup > h3,
.ui-popup > h4,
.ui-popup > h5,
.ui-popup > h6 {
	margin: .5em 7px;
}
.ui-popup > span {
	display: block;
	margin: .5em 7px;
}
.ui-popup .ui-title {
	font-size: 16px;
	font-weight: bold;
	margin-top: .5em;
	margin-bottom: .5em;
}
.ui-popup-container .ui-content > p,
.ui-popup-container .ui-content > h1,
.ui-popup-container .ui-content > h2,
.ui-popup-container .ui-content > h3,
.ui-popup-container .ui-content > h4,
.ui-popup-container .ui-content > h5,
.ui-popup-container .ui-content > h6 {
	margin: .5em 0;
}
.ui-popup-container .ui-content > span {
	margin: 0;
}
.ui-popup-container .ui-content > p:first-child,
.ui-popup-container .ui-content > h1:first-child,
.ui-popup-container .ui-content > h2:first-child,
.ui-popup-container .ui-content > h3:first-child,
.ui-popup-container .ui-content > h4:first-child,
.ui-popup-container .ui-content > h5:first-child,
.ui-popup-container .ui-content > h6:first-child {
	margin-top: 0;
}
.ui-popup-container .ui-content > p:last-child,
.ui-popup-container .ui-content > h1:last-child,
.ui-popup-container .ui-content > h2:last-child,
.ui-popup-container .ui-content > h3:last-child,
.ui-popup-container .ui-content > h4:last-child,
.ui-popup-container .ui-content > h5:last-child,
.ui-popup-container .ui-content > h6:last-child {
	margin-bottom: 0;
}
.ui-popup > img {
	width: auto;
	height: auto;
	max-width: 100%;
	max-height: 100%;
	vertical-align: middle;
}
.ui-popup iframe {
	vertical-align: middle;
}
@media all and (min-width: 450px){
	.ui-popup .ui-field-contain label.ui-submit,
	.ui-popup .ui-field-contain .ui-controlgroup-label,
	.ui-popup .ui-field-contain label.ui-select,
	.ui-popup .ui-field-contain label.ui-input-text {
		font-size: 16px; line-height: 1.4; display: block; font-weight: normal; margin: 0 0 .3em;
	}
	.ui-popup .ui-field-contain .ui-btn.ui-submit,
	.ui-popup .ui-field-contain .ui-controlgroup-controls,
	.ui-popup .ui-field-contain .ui-select,
	.ui-popup .ui-field-contain input.ui-input-text,
	.ui-popup .ui-field-contain textarea.ui-input-text,
	.ui-popup .ui-field-contain .ui-input-search {
		width: 100%; display: block;
	}
}
.ui-popup > .ui-btn-left,
.ui-popup > .ui-btn-right {
	position: absolute; 
	top: -9px;
	margin: 0;
	z-index: 1101;
}
.ui-popup > .ui-btn-left { left: -9px; }
.ui-popup > .ui-btn-right { right: -9px; }
.ui-popup.ui-corner-all > .ui-header,
.ui-popup.ui-corner-all ~ .ui-content,
.ui-popup.ui-corner-all > .ui-content:first-child {
	-webkit-border-top-left-radius:  inherit;
	border-top-left-radius:          inherit;
	-webkit-border-top-right-radius: inherit;
	border-top-right-radius:         inherit;
}
.ui-popup.ui-corner-all > .ui-content,
.ui-popup.ui-corner-all > .ui-footer,
.ui-popup.ui-corner-all > .ui-header:nth-child(n):last-child {
	-webkit-border-bottom-left-radius:  inherit;
	border-bottom-left-radius:          inherit;
	-webkit-border-bottom-right-radius: inherit;
	border-bottom-right-radius:         inherit;
}
.ui-popup.ui-corner-all > .ui-content:nth-child(2),
.ui-popup.ui-corner-all > .ui-header:nth-child(2) {
	-webkit-border-top-left-radius:  0;
	border-top-left-radius:          0;
	-webkit-border-top-right-radius: 0;
	border-top-right-radius:         0;
}
.ui-popup.ui-corner-all > .ui-content:nth-last-child(1n+2),
.ui-popup.ui-corner-all > .ui-footer:nth-last-child(1n+2) {
	-webkit-border-bottom-left-radius:  0;
	border-bottom-left-radius:          0;
	-webkit-border-bottom-right-radius: 0;
	border-bottom-right-radius:         0;
}
.ui-popup.ui-corner-all > .ui-header:only-child,
.ui-popup.ui-corner-all > .ui-footer:only-child {
	-webkit-border-radius: inherit;
	border-radius:         inherit;
}
.ui-checkbox, .ui-radio { position: relative; clear: both; margin: 0; z-index: 1; }
.ui-checkbox .ui-btn, .ui-radio .ui-btn { margin-top: .5em; margin-bottom: 0em; text-align: left; z-index: 2; }
.ui-checkbox .ui-btn.ui-mini, .ui-radio .ui-btn.ui-mini { margin: .25em 0; }
.ui-controlgroup .ui-checkbox .ui-btn, .ui-controlgroup .ui-radio .ui-btn { margin: 0; }
.ui-checkbox .ui-btn-inner, .ui-radio .ui-btn-inner { white-space: normal; }
.ui-checkbox .ui-btn-icon-left .ui-btn-inner,.ui-radio .ui-btn-icon-left .ui-btn-inner { padding-left: 45px; }
.ui-checkbox .ui-mini.ui-btn-icon-left .ui-btn-inner,.ui-radio .ui-mini.ui-btn-icon-left .ui-btn-inner { padding-left: 36px; }
.ui-checkbox .ui-btn-icon-right .ui-btn-inner, .ui-radio .ui-btn-icon-right .ui-btn-inner { padding-right: 45px; }
.ui-checkbox .ui-mini.ui-btn-icon-right .ui-btn-inner, .ui-radio .ui-mini.ui-btn-icon-right .ui-btn-inner { padding-right: 36px; }
.ui-checkbox .ui-btn-icon-top .ui-btn-inner,.ui-radio .ui-btn-icon-top .ui-btn-inner { padding-right: 0; padding-left: 0; text-align: center; }
.ui-checkbox .ui-btn-icon-bottom .ui-btn-inner, .ui-radio .ui-btn-icon-bottom .ui-btn-inner { padding-right: 0; padding-left: 0; text-align: center; }
.ui-checkbox .ui-icon, .ui-radio .ui-icon { top: 1.1em; }
.ui-checkbox .ui-btn-icon-left .ui-icon, .ui-radio .ui-btn-icon-left .ui-icon { left: 15px; }
.ui-checkbox .ui-mini.ui-btn-icon-left .ui-icon, .ui-radio .ui-mini.ui-btn-icon-left .ui-icon { left: 9px; }
.ui-checkbox .ui-btn-icon-right .ui-icon, .ui-radio .ui-btn-icon-right .ui-icon { right: 15px; }
.ui-checkbox .ui-mini.ui-btn-icon-right .ui-icon, .ui-radio .ui-mini.ui-btn-icon-right .ui-icon { right: 9px; }
.ui-checkbox .ui-btn-icon-top .ui-icon, .ui-radio .ui-btn-icon-top .ui-icon { top: 10px; }
.ui-checkbox .ui-btn-icon-bottom .ui-icon, .ui-radio .ui-btn-icon-bottom .ui-icon { top: auto; bottom: 10px; }
.ui-checkbox .ui-btn-icon-right .ui-icon, .ui-radio .ui-btn-icon-right .ui-icon { right: 15px; }
.ui-checkbox .ui-mini.ui-btn-icon-right .ui-icon, .ui-radio .ui-mini.ui-btn-icon-right .ui-icon { right: 9px; }
/* input, label positioning */
.ui-checkbox input,.ui-radio input { position:absolute; left:20px; top:50%; width: 10px; height: 10px; margin:-5px 0 0 0; outline: 0 !important; z-index: 1; }
.ui-field-contain, fieldset.ui-field-contain { padding: .8em 0; margin: 0; border-width: 0 0 1px 0; overflow: visible; }
.ui-field-contain:last-child { border-bottom-width: 0; }
.ui-field-contain { max-width: 100%; } /* This prevents horizontal scrollbar in IE7 */
@media all and (min-width: 450px){
	.ui-field-contain, .ui-mobile fieldset.ui-field-contain { border-width: 0; padding: 0; margin: 1em 0; }
}
.ui-select { display: block; position: relative; }
.ui-select select { position: absolute; left: -9999px; top: -9999px; }
.ui-select .ui-btn { overflow: hidden; opacity: 1; }
.ui-field-contain .ui-select .ui-btn { margin: 0; }
/* Fixes #2588: When Windows Phone 7.5 (Mango) tries to calculate a numeric opacity for a select (including "inherit") without explicitly specifying an opacity on the parent to give it context, a bug appears where clicking elsewhere on the page after opening the select will open the select again. */
.ui-select .ui-btn select { cursor: pointer; -webkit-appearance: none; left: 0; top:0; width: 100%; min-height: 1.5em; min-height: 100%; height: 3em; max-height: 100%; filter: Alpha(Opacity=0); opacity: 0; z-index: 2; }
.ui-select .ui-disabled { opacity: .3; }
/* Display none because of issues with IE/WP's filter alpha opacity */
.ui-select .ui-disabled select { display: none; }
@-moz-document url-prefix() { .ui-select .ui-btn select { opacity: 0.0001; }}
.ui-select .ui-btn.ui-select-nativeonly { border-radius: 0; border: 0; }
.ui-select .ui-btn.ui-select-nativeonly select { opacity: 1; text-indent: 0; display: block; }
.ui-select .ui-disabled.ui-select-nativeonly .ui-btn-inner { opacity: 0; }
.ui-select .ui-btn-icon-right .ui-btn-inner, .ui-select .ui-li-has-count .ui-btn-inner { padding-right: 45px; }
.ui-select .ui-mini.ui-btn-icon-right .ui-btn-inner { padding-right: 32px; }
.ui-select .ui-btn-icon-right.ui-li-has-count .ui-btn-inner { padding-right: 80px; }
.ui-select .ui-mini.ui-btn-icon-right.ui-li-has-count .ui-btn-inner { padding-right: 67px; }
.ui-select .ui-btn-icon-right .ui-icon { right: 15px; }
.ui-select .ui-mini.ui-btn-icon-right .ui-icon { right: 7px; }
.ui-select .ui-btn-icon-right.ui-li-has-count .ui-li-count { right: 45px; }
.ui-select .ui-mini.ui-btn-icon-right.ui-li-has-count .ui-li-count { right: 32px; }
/* labels */
label.ui-select { font-size: 16px; line-height: 1.4; font-weight: normal; margin: 0 0 .3em; display: block; }
/*listbox*/
.ui-select .ui-btn-text, .ui-selectmenu .ui-btn-text { display: block; min-height: 1em; overflow: hidden !important;
/* This !important is required for iPad Safari specifically. See https://github.com/jquery/jquery-mobile/issues/2647 */ }
.ui-select .ui-btn-text { text-overflow: ellipsis; }
.ui-selectmenu { padding: 6px; min-width: 160px; }
.ui-selectmenu .ui-listview { margin: 0; }
.ui-selectmenu .ui-btn.ui-li-divider { cursor: default; }
.ui-selectmenu-hidden { top: -99999px; left: -9999px; }
.ui-screen-hidden, .ui-selectmenu-list .ui-li .ui-icon { display: none; }
.ui-selectmenu-list .ui-li .ui-icon { display: block; }
.ui-li.ui-selectmenu-placeholder { display: none; }
.ui-selectmenu .ui-header { margin: 0; padding: 0; }
.ui-selectmenu .ui-header .ui-title { margin: 0.6em 46px 0.8em; }
@media all and (min-width: 450px){
	.ui-field-contain label.ui-select { vertical-align: top; display: inline-block; width: 20%; margin: 0 2% 0 0; }
	.ui-field-contain .ui-select { width: 78%; display: inline-block; }
	.ui-hide-label .ui-select { width: 100%; } 
}
/* when no placeholder is defined in a multiple select, the header height doesn't even extend past the close button.  this shim's content in there */
.ui-selectmenu .ui-header h1:after { content: '.'; visibility: hidden; }
label.ui-input-text { font-size: 16px; line-height: 1.4; display: block; font-weight: normal; margin: 0 0 .3em; }
input.ui-input-text, textarea.ui-input-text { background-image: none; padding: .4em; margin: .5em 0; line-height: 1.4; font-size: 16px; display: block; width: 100%; outline: 0; text-align: center; }
input.ui-input-text.ui-mini, textarea.ui-input-text.ui-mini { margin: .25em 0; }
.ui-field-contain input.ui-input-text, .ui-field-contain textarea.ui-input-text { margin: 0; }
input.ui-input-text, textarea.ui-input-text, .ui-input-search { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; -ms-box-sizing: border-box; box-sizing: border-box; }
input.ui-input-text { -webkit-appearance: none; }
textarea.ui-input-text { height: 50px; -webkit-transition: height 200ms linear; -moz-transition: height 200ms linear; -o-transition: height 200ms linear; transition: height 200ms linear; }
.ui-input-search { padding: 0 30px; margin: .5em 0; background-image: none; position: relative; }
.ui-input-search.ui-mini { margin: .25em 0; }
.ui-field-contain .ui-input-search { margin: 0; }
.ui-icon-searchfield:after { position: absolute; left: 7px; top: 50%; margin-top: -9px; content: ""; width: 18px; height: 18px; opacity: .5; }
.ui-input-search input.ui-input-text { border: none; width: 98%; padding: .4em 0; margin: 0; display: block; background: transparent none; outline: 0 !important; }
.ui-input-search .ui-input-clear { position: absolute; right: 0; top: 50%; margin-top: -13px; }
.ui-mini .ui-input-clear { right: -3px; }
.ui-input-search .ui-input-clear-hidden { display: none; }
input.ui-mini, .ui-mini input, textarea.ui-mini { font-size: 14px; }
textarea.ui-mini { height: 45px; }
@media all and (min-width: 450px){
	.ui-field-contain label.ui-input-text  { vertical-align: top; display: inline-block; width: 20%; margin: 0 2% 0 0 }
	.ui-field-contain input.ui-input-text, 
	.ui-field-contain textarea.ui-input-text, 
	.ui-field-contain .ui-input-search { width: 78%; display: inline-block; } 
	.ui-hide-label input.ui-input-text, 
	.ui-hide-label textarea.ui-input-text, 
	.ui-hide-label .ui-input-search { width: 100%; }
	.ui-input-search input.ui-input-text { width: 98%; /*echos rule from above*/ }
}
.ui-listview { margin: 0; }
ol.ui-listview, ol.ui-listview .ui-li-divider { counter-reset: listnumbering; }
.ui-content .ui-listview { margin: -15px; }
.ui-collapsible-content > .ui-listview { margin: -10px -15px; }
.ui-content .ui-listview-inset { margin: 1em 0; }
.ui-collapsible-content .ui-listview-inset { margin: .5em 0; }
.ui-listview, .ui-li { list-style:none; padding:0; }
.ui-li, .ui-li.ui-field-contain { display: block; margin:0; position: relative; overflow: visible; text-align: left; border-width: 0; border-top-width: 1px; }
.ui-li.ui-btn { margin: 0; }
.ui-li .ui-btn-text a.ui-link-inherit { text-overflow: ellipsis; overflow: hidden; white-space: nowrap; }
.ui-li-static { background-image: none; }
.ui-li-divider { padding: .5em 15px; font-size: 14px; font-weight: bold; }
ol.ui-listview .ui-link-inherit:before, ol.ui-listview .ui-li-static:before, .ui-li-dec { font-size: .8em; display: inline-block; padding-right: .3em; font-weight: normal; counter-increment: listnumbering; content: counter(listnumbering) ". "; }
ol.ui-listview .ui-li-jsnumbering:before { content: "" !important; } /* to avoid chance of duplication */
.ui-listview-inset .ui-li { border-right-width: 1px; border-left-width: 1px; }
.ui-li-last, .ui-li.ui-field-contain.ui-li-last { border-bottom-width: 1px; }
.ui-collapsible [class*="ui-body"] > .ui-listview:not(.ui-listview-inset) .ui-li-last { border-bottom-width: 0; }
.ui-collapsible-content > .ui-listview:not(.ui-listview-inset) .ui-li:first-child { border-top-width: 0; }
.ui-collapsible-content > .ui-listview:not(.ui-listview-inset),
.ui-collapsible-content > .ui-listview:not(.ui-listview-inset) .ui-li-last { -webkit-border-bottom-left-radius: inherit; -webkit-border-bottom-right-radius: inherit; border-bottom-left-radius: inherit; border-bottom-right-radius: inherit; }
.ui-collapsible-content > .ui-listview:not(.ui-listview-inset) .ui-li-last .ui-li-link-alt { -webkit-border-bottom-right-radius: inherit; border-bottom-right-radius: inherit; }
.ui-li>.ui-btn-inner { display: block; position: relative; padding: 0; }
.ui-li .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li { padding: .7em 15px; display: block; }
.ui-li-has-thumb .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-thumb  { min-height: 60px; padding-left: 100px; }
.ui-li-has-icon .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-icon { min-height: 20px; padding-left: 40px; }
.ui-li-has-count .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-count, .ui-li-divider.ui-li-has-count { padding-right: 45px; }
.ui-li-has-arrow .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-arrow { padding-right: 40px; }
.ui-li-has-arrow.ui-li-has-count .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-arrow.ui-li-has-count { padding-right: 75px; }
.ui-li-heading { font-size: 16px; font-weight: bold; display: block; margin: .6em 0; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; }
.ui-li-desc { font-size: 12px; font-weight: normal; display: block; margin: -.5em 0 .6em; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; }
.ui-li-thumb, .ui-listview .ui-li-icon { position: absolute; left: 1px; top: 0; max-height: 80px; max-width: 80px; }
.ui-listview .ui-li-icon { max-height: 16px; max-width: 16px; left: 10px; top: .9em; }
.ui-li-thumb, .ui-listview .ui-li-icon, .ui-li-content { float: left; margin-right: 10px; }
.ui-li-aside { float: right; width: 50%; text-align: right; margin: .3em 0; }
@media all and (min-width: 480px){
	 .ui-li-aside { width: 45%; }
}	 
.ui-li-divider { cursor: default; }
.ui-li-has-alt .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-alt { padding-right: 53px; }
.ui-li-has-alt.ui-li-has-count .ui-btn-inner a.ui-link-inherit, .ui-li-static.ui-li-has-alt.ui-li-has-count { padding-right: 88px; }
.ui-li-has-count .ui-li-count { position: absolute; font-size: 11px; font-weight: bold; padding: .2em .5em; top: 50%; margin-top: -.9em; right: 10px; }
.ui-li-has-count.ui-li-divider .ui-li-count, .ui-li-has-count .ui-link-inherit .ui-li-count { margin-top: -.95em; }
.ui-li-has-arrow.ui-li-has-count .ui-li-count { right: 40px; }
.ui-li-has-alt.ui-li-has-count .ui-li-count { right: 53px; }
.ui-li-link-alt { position: absolute; width: 40px; height: 100%; border-width: 0; border-left-width: 1px; top: 0; right: 0; margin: 0; padding: 0; z-index: 2; }
.ui-li-link-alt .ui-btn { overflow: hidden; position: absolute; right: 8px; top: 50%; margin: -13px 0 0 0; border-bottom-width: 1px; z-index: -1;}
.ui-li-link-alt .ui-btn-inner { padding: 0; height: 100%; position: absolute; width: 100%; top: 0; left: 0;}
.ui-li-link-alt .ui-btn .ui-icon { right: 50%; margin-right: -9px; }
.ui-li-link-alt .ui-btn-icon-notext .ui-btn-inner .ui-icon { position: absolute; top: 50%; margin-top: -9px; }
.ui-listview * .ui-btn-inner > .ui-btn > .ui-btn-inner { border-top: 0px; }
.ui-listview-filter { border-width: 0; overflow: hidden; margin: -15px -15px 15px -15px; }
.ui-collapsible-content .ui-listview-filter { margin: -10px -15px 10px -15px; border-bottom: inherit; }
.ui-listview-filter-inset { margin: -15px -5px; background: transparent; }
.ui-collapsible-content .ui-listview-filter-inset { margin: -5px; border-bottom-width: 0; }
.ui-listview-filter .ui-input-search { margin: 5px; width: auto; display: block; }
.ui-li.ui-screen-hidden{ display:none; }
/* Odd iPad positioning issue. */
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
    .ui-li .ui-btn-text { overflow:  visible; }
}
label.ui-slider { font-size: 16px; line-height: 1.4; font-weight: normal; margin: 0 0 .3em; display: block; }
input.ui-slider-input,
.ui-field-contain input.ui-slider-input { display: inline-block; width: 50px; background-image: none; padding: .4em; margin: .5em 0; line-height: 1.4; font-size: 16px; outline: 0; }
input.ui-slider-input.ui-mini,
.ui-field-contain input.ui-slider-input.ui-mini { width: 45px; margin: .25em 0; font-size: 14px; }
.ui-field-contain input.ui-slider-input { margin: 0; }
input.ui-slider-input, .ui-field-contain input.ui-slider-input { -webkit-box-sizing: content-box; -moz-box-sizing: content-box; -ms-box-sizing: content-box; box-sizing: content-box; }
/* Fixes input fields being to small on Safari/Mac because of the up and down arrows. */
.ui-slider-input::-webkit-outer-spin-button { margin: 0; }
select.ui-slider-switch { display: none; }
div.ui-slider { position: relative; display: inline-block; overflow: visible; height: 15px; padding: 0; margin: 0 2% 0 20px; top: 4px; width: 65%; }
div.ui-slider-mini { height: 12px; margin-left: 10px; top: 2px; }
div.ui-slider-bg { border: none; height: 100%; padding-right: 8px; }
.ui-controlgroup a.ui-slider-handle, a.ui-btn.ui-slider-handle { position: absolute; z-index: 1; top: 50%; width: 28px; height: 28px; margin: -15px 0 0 -15px; outline: 0; }
a.ui-btn.ui-slider-handle .ui-btn-inner { padding: 0; height: 100%; }
div.ui-slider-mini a.ui-slider-handle { height: 14px; width: 14px; margin: -8px 0 0 -7px; }
div.ui-slider-mini a.ui-slider-handle .ui-btn-inner { height: 30px; width: 30px; padding: 0; margin: -9px 0 0 -9px; border-top: none; }
@media all and (min-width: 450px){
	.ui-field-contain label.ui-slider { vertical-align: top; display: inline-block; width: 20%; margin: 0 2% 0 0; }
	.ui-field-contain div.ui-slider { width: 43%; }
	.ui-field-contain div.ui-slider-switch { width: 5.5em; }
}	
div.ui-slider-switch { height: 32px; margin-left: 0; width: 5.8em; }
a.ui-slider-handle-snapping { -webkit-transition: left 70ms linear; -moz-transition: left 70ms linear; }
div.ui-slider-switch .ui-slider-handle { margin: 1px 0 0 -15px; }
.ui-slider-inneroffset { margin: 0 16px; position: relative; z-index: 1; }
div.ui-slider-switch.ui-slider-mini { width: 5em; height: 29px; }
div.ui-slider-switch.ui-slider-mini .ui-slider-inneroffset { margin: 0 15px 0 14px; }
div.ui-slider-switch.ui-slider-mini .ui-slider-handle { width: 25px; height: 25px; margin: 1px 0 0 -13px; }
div.ui-slider-switch.ui-slider-mini a.ui-slider-handle .ui-btn-inner { height: 30px; width: 30px; padding: 0; margin: 0; }
span.ui-slider-label { position: absolute; text-align: center; width: 100%; overflow: hidden; font-size: 16px; top: 0; line-height: 2; min-height: 100%; border-width: 0; white-space: nowrap; }
.ui-slider-mini span.ui-slider-label { font-size: 14px; }
span.ui-slider-label-a { z-index: 1; left: 0; text-indent: -1.5em; }
span.ui-slider-label-b { z-index: 0; right: 0; text-indent: 1.5em;}
.ui-slider-inline { width: 120px; display: inline-block; }


scrollbar.css
=============
/**
 *
 * Horizontal Scrollbar
 *
 */
.myScrollbarH {
	position:absolute;
	z-index:100;
	height:7px;
	bottom:1px;
	left:2px;
	right:7px
}

.myScrollbarH > div {
	height:100%;
}


/**
 *
 * Vertical Scrollbar
 *
 */
.myScrollbarV {
	position:absolute;
	width:7px;
	bottom:7px;
	top:2px;
	right:1px;
	z-index:100;
	left:98%;
}

.myScrollbarV > div {
	width:100%;
}


/**
 *
 * Both Scrollbars
 *
 */
.myScrollbarH > div,
.myScrollbarV > div {
	position:absolute;
	z-index:100;

	/* The following is probably what you want to customize */
	box-sizing:border-box;
	-o-box-sizing:border-box;
	-moz-box-sizing:border-box;
	-webkit-box-sizing:border-box;

	border:1px solid #000;
	border-width:3px;
	border-image:url(../images/scrollbar.png) 6 6 6 6;
	-moz-border-image:url(../images/scrollbar.png) 6 6 6 6;
	-webkit-border-image:url(../images/scrollbar.png) 6 6 6 6;
}



style.css
============

/* Index Page CSS */

*{       
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}

#indexPageContainer
{
	width:100%;
	min-height:100%;
	height:auto;
	position:relative;
	left:0px;
	top:0px;
	background:url(../images/appBg.png) repeat;
}

#index{
    background:url(../images/appBg.png) repeat;
}

#indexLogo
{
	margin-top:5%;
}
#indexPageTestIcons
{
	margin-top:5%;
    margin-left:2%;
}
.indexPageLessonsText
{
	font-family:boldFont;
	font-size:18pt;
	color:#ffffff;
}
#indexPageLessons
{
	text-align:center;
	margin-top:5%;
}
#indexHrLine
{
	width:80%;
}
.indexPageLessonTitleText
{
	font-family:boldFont;
	font-size:12pt;
	color:#ffffff;
}
#indexPageLeft
{
    float:left;
    min-width:250px;
	width:50%;
	height:100%;
}
#indexPageRight
{
    float:left;
    min-width:250px;
    width:50%;
	height:100%;
}
#indexPageWidth
{
    width:70%;
	height:100%;
}
.indexFooterNavAlign
{
	height:61px;
	position:relative;
	margin-top:60px;

}
.indexLeft
{
    width:55%;
    float:left;
}
.indexRight
{
    float:right;
    margin-right:10%;
}
/* Index Page CSS */

/* About Page CSS */
.aboutPageContainer
{
	width:100%;
	min-height:100%;
	height:auto;
	position:absolute;
    background-color:#56006a;
	left:0px;
	top:0px;
}
#aboutPageLogo
{
	margin-top:12px;
	margin-right:12px;
	background-image:url(../images/logo.png);
	width:191px;
	height:62px;
	float:left;
}
#aboutPageWhitBoxTop
{
	border:1px solid #ffffff;
	border-radius:25px;
	box-shadow: 5px 5px 15px #000000;
	-webkit-box-shadow: 5px 5px 15px #000000;
	background-color:#ffffff;
	margin-left:5%;
	margin-right:5%;
	margin-top:90px;
}
#aboutPageContentIndent
{
	padding-left:5%;
	padding-right:5%;
	padding-top:24px;
}
.aboutPageblueHeadingText{
	font-family:boldFont;
	font-size:12pt;
	color:#25408f;
	text-decoration:none;
}
.aboutBlackNormalText{
	font-family:normalFont;
	font-size:11pt;
	color:#000000;
}
#aboutPageTest1
{
	background-image:url(../images/one_about_ipad.png);
	width:105px;
	height:90px;
	margin-right:20px;
	float:left;
}
#aboutPageTest2
{
	background-image:url(../images/two_about_ipad.png);
	width:105px;
	height:90px;
	margin-right:20px;
	float:left;
}
#aboutPageTest3
{
	background-image:url(../images/three_about_ipad.png);
	width:105px;
	height:90px;
	margin-right:20px;
	float:left;
}
#aboutPageTest4
{
	background-image:url(../images/four_about_ipad.png);
	width:105px;
	height:90px;
	margin-right:20px;
	float:left;
}
.aboutBlackBoldTestContents
{
	font-family:boldFont;
	font-size:10pt;
	color:#000000;
}
#aboutPageTestEasy
{
	display:inline;
	margin-left:39px;
}
#aboutPageTestHarder
{
	display:inline;
	margin-left:30px;
}
#aboutPageTestEvenHarder
{
	display:inline;
	margin-left:15px;
}
#aboutPageTestHardest
{
	display:inline;
	margin-left:30px;
}
#aboutPageGreenlightLogo
{
	float:left;

}
#aboutPageGreenlightLogoContent
{
	float:left;
	padding-left:10px;
}
#aboutPageGreenlightLogoHeight
{
	height:100px;
	width:90%;
}
.aboutPageCapsAuthor
{
	font-family:normalFont;
	text-transform:uppercase;
	font-size:9pt;
	color:#000000;
}

.aboutFooterNavAlign
{
	height:61px;
    width:100%;
    position:relative;
    margin-top:10%;
}
.aboutFooter
{
	width:100%;
    margin-left:40px;
	margin-right:40px;
}
.aboutMenu
{
	width:50%;
}
.aboutBack
{
	width:8%;
}
.aboutNext
{
	width:16%;
}
/* About Page CSS */

/* Test Page CSS */
.testPageContainer
{
	width:100%;
	min-height:100%;
	height:auto;
	background:url(../images/appBg.png) repeat;
	position:absolute;
	left:0px;
	top:0px;
}
.testPageLogo
{
    position: absolute;
    right: 5%;
    top: 3%;
    background-image: url(../images/logo.png);
    width: 191px;
    height: 62px;
    float: left;
    background-size: 100% 100%;
}
.testPageTop
{
	margin-left:5%;
	margin-right:5%;
	margin-top:124px;
	overflow: hidden;
}
.testPageWhiteQuestionNo{
	font-family:boldFont;
	font-size:12pt;
	color:#ffffff;
}
.testPageWhiteAlpha{
	font-family:boldFont;
	font-size:12pt;
	color:#ffffff;
}
.testPageWhiteBoxTop
{
	border:1px solid #000000;
	border-radius:10px;
	box-shadow: 5px 5px 15px #000000;
	background-color:#ffffff;
}
.testPageWhiteBoxIndent
{
	position:relative;
	padding-left:5%;
	padding-right:5%;
	padding-top:24px;
	padding-bottom:0px;
	height:70px;
}
.testPageTextIndent
{
	text-indent:50px;
}
.testPageGreyAnswerBoxHeight
{
	height:auto;
}
.testPageGreyAnswerBoxWidth
{
    margin-top:-60px;
}
.testpageWidth
{
    margin-left:4%;
    margin-right:5%;
    float:left;
    width:94%;
    /*background:#FFF;*/
    border-bottom-right-radius:10px;
    border-bottom-left-radius:10px;
}
.defaultSubmit
{
    float:right;
    margin-right:5%;
    z-index:10;
    display: none;
}
.testPageCorrectAns
{
    border:1px solid #000000;
    border-radius:25px;
    box-shadow: 5px 5px 15px #000000;
    background-color:#fffcdb;
    display:none;
    margin-top:-10px;
    padding:17px;
    margin-left:4%;
    margin-right:4%;
    margin-bottom:20px;
    z-index:15;
}

form
{
    margin-top:100px;
}

.testFooterNavAlign
{
    height: 65px;
    width: 100%;
    position: absolute;
    /* margin-top: 23%; */
    bottom: 0%;
    /*border-top: 1px solid black;*/
    -webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
}

.testFooter
{
    width:90%;
    margin-left:5%;
    margin-right:5%;
}
.testMenu
{
	width:74%;
}
.testBack
{
	width:8%;
	position: absolute;
	left: 0%;
}
.testNext
{
	position: absolute;
	right: 0%;
	width:8%;
}
/* Test Page CSS */

/* Lesson Page CSS */
.lessonPageContainer
{
	width:100%;
	min-height:100%;
	height:auto;
	background-color:#c6dce8;
	position:absolute;
	left:0px;
	top:0px;
}
.lessonPageLogo
{
    margin-top:12px;
    margin-left:12px;
    background-image:url(../images/logo.png);
    width:191px;
    height:62px;
    float:left;
}
.lessonPageTop
{
	margin-left:3%;
	margin-right:3%;
	margin-top:84px;
}
.lessonPageWhiteTop
{
	border:1px solid #000000;
	border-radius:25px;
	box-shadow: 5px 5px 15px #000000;
	background-color:#ffffff;
}
.lessonPageSteps
{
	float:left;
	width:98%;
	margin-left:7px;
	margin-top:-105px;
}
.lessonPageSteps1
{
	float:left;
	width:98%;
	margin-left:7px;
	margin-top:-75px;
}
.lessonPageSteps2
{
	float:left;
	width:98%;
	margin-left:7px;
	margin-top:-143px;
}
.lessonPageWhiteBoxIndent
{
	padding-left:5%;
	padding-right:5%;
	padding-top:24px;
	padding-bottom:18px;
}
.lessonPageTextIndent
{
	text-indent:30px;
}
.lessonFooterNavAlign
{
	height:75px;
    width:100%;
    position:relative;
    margin-top:10%;
}

.lessonFooter
{
	width:100%;
}

.lessonLeft
{
    width:32%;
    float:left;
    padding-left:0%;
	margin-left:3%;
}
.lessonRight
{
    width:61%;
    float:right;
    padding-right:0%;
	margin-right:3%;
}
.lessonFooter
{
	width:90%;
    margin-left:5%;
	margin-right:5%;
}
.lessonMenu
{
	width:74%;
}
.lessonBack
{
	width:8%;
}
.lessonNext
{
	width:8%;
}
.lessonRuleBox
{
    /*-webkit-box-shadow: inset 0 0 15px #99ace3;
    background:#f2f4f8;
    border-radius:20px;*/
    background:#00b95c;
    border-radius:10px;
    padding-left:15px;
    padding-right:15px;
    padding-top:8px;
    padding-bottom:8px;
}
.lessonRuleBrownText
{
	font-family:boldFont;
	font-size:14pt;
	color:#b92900;
}
.lessonRuleBlueText
{
	font-family:boldFont;
	font-size:14pt;
	color:#ffff00	;
}
.lessonRuleBlueBoldItalicText
{
	font-family:bolditalicFont;
	font-size:14pt;
	color:#25408f;
}
/* Lesson Page CSS */

/* Result Page CSS */

.resultFooterNavAlign
{
	height:61px;
	bottom:0px;
	position:relative;
	}
.resultFooter
{
	width:90%;
    margin-left:5%;
	margin-right:5%;
}
.resultMenu
{
	width:50%;
}
.resultBack
{
	width:8%;
}
.resultNext
{
	width:16%;
}
.resultQuestionNumber
{
    float:left;
    width:100px;
}
.resultImages
{
    float:left;
    width:30px;
}
.resultLesson
{
    float:left;

}
.resultQuestion
{
    padding-left:5%;
    width:90%;
    padding-right:5%;
}
.resultHrLine
{
    padding-left:5%;
    padding-right:5%;
}

/* Result Page CSS */

/* Common CSS */
a
{
	text-decoration:none;
}
.footerBlackText
{
	font-size:16pt;
	font-family:normalFont;
	color:#000;
}
.blackNormalTextAnswer{
	font-family:normalFont;
	font-size:14pt;
	color:#000000;
}
.blackBoldText{
	font-family:boldFont;
	font-size:14pt;
	color:#000000;
}
.blackBoldItalicText{
	font-family:bolditalicFont;
	font-size:14pt;
	color:#000000;
}
.redItalicText{
	font-family:italicFont;
	font-size:14pt;
	color:#F00;
}
.bigBoldText{
	font-family:boldFont;
	font-size:14pt;
	color:#000000;
    letter-spacing:0.75pt;
}
.smallBoldText{
	font-family:boldFont;
	font-size:12pt;
	color:#000000;
    letter-spacing:0.75pt;
}
.blackHeadText{
	font-family:boldFont;
	font-size:16pt;
	color:#000000;
	font-weight:bold;
}
.blackHeadItalicText{
	font-family:bolditalicFont;
	font-size:16pt;
	color:#000000;
}
.page1of2WhiteText{
	font-family:normalFont;
	font-size:14pt;
	color:#ffffff;
}
.normalTimes{
	font-family:"Times New Roman", Times, serif;
	font-size:14pt;
	color:#000000;
	width: 80%;
}
.normalTimes1{
	font-family:"Times New Roman", Times, serif;
	font-size:13.5pt;
	color:#000000;
}
.normalTimes2{
	font-family:"Times New Roman", Times, serif;
	font-size:12pt;
	color:#000000;
}
.smallNormalTimes{
	font-family:"Times New Roman", Times, serif;
	font-size:12pt;
	color:#000000;
}
.smallOfficiana{
	font-family:boldFont;
	font-size:12pt;
	color:#000000;
}
.blackNormalText{
	font-family:normalFont;
	font-size:14pt;
	color:#000000;
}
.blueNormalText{
	font-family:normalFont;
	font-size:14pt;
	color:#116399;
}
.violetNormalText{
	font-family:normalFont;
	font-size:14pt;
	color:#343B8D;
}
.violetBoldText{
	font-family:boldFont;
	font-size:14pt;
	color:#343B8D;
}
.blueNormalTextItalic{
	font-family:italicFont;
	font-size:14pt;
	color:#116399;
	font-style:italic;
}
.whiteBoldTextBig{
	font-family:boldFont;
	font-size:14pt;
	color:#ffffff;
}
.blackNormalItalic{
	font-family:italicFont;
	font-size:14pt;
	color:#000000;
    font-style:italic;
}
.blackNormalBoldItalic{
	font-family:bolditalicFont;
	font-size:14pt;
	color:#000000;
    font-style:italic;
	font-weight:bold;
}

.blueNormalTextResultPage{
	font-family:normalFont;
	font-size:16pt;
	color:#25408f;
}

.smallBlueNormalText{
	font-family:normalFont;
	font-size:12pt;
	color:#116399;
}
.smallBlueBullNormalText{
	font-family:normalFont;
	font-size:8pt;
	color:#116399;
}
.smallBlueNormalTextItalic{
	font-family:italicFont;
	font-size:12pt;
	color:#116399;
}
.blueNormalTextAnswer{
	font-family:normalFont;
	font-size:14pt;
	color:#25408f;
}
.blueBoldText{
	font-family:boldFont;
	font-size:14pt;
	color:#116399;
	text-decoration:none;
}
.blueBoldItalicText{
	font-family:bolditalicFont;
	font-size:14pt;
	color:#116399;
	text-decoration:none;
}
.greenBoldText{
	font-family:boldFont;
	font-size:14pt;
	color:#41ad49;
}
.greenBoldTextAbout{
	font-family:boldFont;
	font-size:14pt;
	color:#0f4f00;
}
.normalBlueTimes{
	font-family:"Times New Roman", Times, serif;
	font-size:14pt;
	color:#116399;
	line-height:25px;
}
.whiteBoldHead{
	font-family:boldFont;
	font-size:18pt;
	color:#ffffff;
}
label {
	height:50px;
}
.radioBtnAlign .ui-btn-inner .ui-icon {
	top:0.95em
}
.radioBtnAlign .ui-btn-inner .ui-btn-text {
	top:-0.1em
}
.linkColor
{
	color:#116399;
	font-family:boldFont;
}
.linkColor1
{
	color:#116399;
	font-family:bolditalicFont;
}
.linkColor2
{
	color:#116399;
	font-family:boldFont;
}

.violetHighlight
{
	background-color:#d3d9e9;
}
.yellowHighlight
{
	background-color:#fff56d;
}
.roseHighlight
{
	background-color:#ffbcd4;
}
/* Common CSS */

/* Space CSS */
.fivespace
{
	margin-top:5px;
}
.tenspace
{
	margin-top:10px;
}
.fifteenspace
{
	margin-top:15px;
}
.twentyspace
{
	margin-top:20px;
}
.thirtyspace
{
	margin-top:30px;
}
.fourtyspace
{
	margin-top:40px;
}
.fiftyspace
{
	margin-top:100px;
}
.yellowBg
{
	background-color:#fff56d;
}
.greenBg
{
	background-color:#C3E784;
}
.redBg
{
	background-color:#fc7174;
}
.blueBg
{
	background-color:#99E3FF;
}
.pinkBg
{
	background-color:#FFBCD4;
}
.violetBg
{
	background-color:#D4C3FF;
}
sup
{
	font-size:10pt;
}
sub
{
	font-size:10pt;
}
.defaultCountdown {
    display: none;
    font-family: boldFont;
    font-size:14pt;
    width: 120px;
    height: 34px;
    text-align:center;
    padding-bottom:3px;
    position:relative;
    margin-left:5%;
    float:left;
}

.Banner_Timer
{
	width:100%;
	height:auto;
	position:relative;
}

.ui-radio label .ui-btn-text {
	font-weight:normal;
}
.ui-btn-inner .ui-btn-text
{
	color:#ffffff;
}
div.ui-btn-corner-all span.ui-btn-inner
{
	padding:.6em 25px;
}
.blueFont 
{
	text-decoration:none;
	color:#a9ceec;
}
/* PST Specific fonts */
@font-face 
{
	font-family: normalFont;
	src: url('fonts/OfficinaSansStd-Book.otf') format("opentype");
}
@font-face 
{
	font-family: boldFont;
	src: url('fonts/OfficinaSansStd-Bold.otf') format("opentype");
	font-weight:bold;
}
@font-face
{
	font-family: italicFont;
	src: url('fonts/OfficinaSansStd-BookItalic.otf') format("opentype");
}
@font-face
{
	font-family: bolditalicFont;
	src: url('fonts/OfficinaSansStd-BoldItalic.otf') format("opentype");
}
/* PST Specific fonts */

.wrapper
{
	position:absolute;
	z-index:100;
	top:45px;
	bottom:80px;
	padding-left:0px;
	padding-right:20px;
}
.scroller {
	position:relative;
	-webkit-tap-highlight-color:rgba(0,0,0,0);
	width:100%;
	padding:0;
	overflow:auto;
}
.strikethrough
{
	background-image:url(../images/str.png);
	background-repeat:repeat-x;
}
.bulletIndent
{
	margin-left:23px;
}
.bigColon
{
    font-family:boldFont;
    font-size:26pt;
    color:#B63200;
}
.redfont
{
    color:#F00;
}

.table-caption{
    text-align:left;
    font-size:12px;
    color:#000;
}
	
	
	
#txt1,#txt2,#txt3,#txt4,#txt5,#txt6,#txt7,#txt8{
    position: relative;
    width: 90%;
    min-height: 200px;
    resize: vertical;
}

#desTxt{
    position: relative;
    width: 100%;
    min-height: 180px;
    resize: none;
    border: none !important;
}


#resultpg_1,#resultpg_2,#resultpg_3,#resultpg_4,#resultpg_5,#resultpg_6,#resultpg_7,#resultpg_8 {
    position: relative;
    width: 90%;
    min-height: 200px;
    border: 1px solid #ccc;
    background: white;
    overflow: scroll;
    float: right;
    -webkit-border-radius: .6em;
    border-radius: .6em;
    -webkit-box-shadow: inset 0px 1px 4px rgba(0,0,0,.2);
    box-shadow: inset 0px 1px 4px rgba(0,0,0,.2);
    text-align: left;
}

th, td {
    font-size: 12pt;
    padding: 2px;
    padding-top: 8px;
    padding-bottom: 8px;
}


#div1 {width:20%;height:100px;border:1px solid #aaaaaa;}


.drgDiv,.drgDiv1{
    position: relative;
    width: 100px;
    height: 40px;
    line-height: 40px;
    text-align: center;
    background: #8080ff;
    border-radius: 5px;
	border: 1px solid #fff;
}

.dropDiv,.dropDiv1{
position: absolute;
width: 1%;
height: 30px;
line-height: 30px;
margin-right: 200px;
float: right;
text-align: center;
border: 1px solid #0A0625;
vertical-align: middle;
display: inline-block;
/* padding-left: 18px; */
top: -1%;
color: #ffffff;
text-indent: 0px;
border-radius: 4px;
background: rgb(255, 255, 229);
}
.dropDiv{}
.dropDiv1{}


.btn {
    position: relative;
    width:120px;
    height: 40px;
    line-height: 40px;
    -webkit-border-radius: 10;
    border-radius: 10px;
    font-family: Arial;
    font-size: 28px;
    color: #ffffff !important;
    /*color: #105174 !important;*/
    padding: 10px 20px 10px 20px;
    text-decoration: none;
    display: inline-block;
}

.btn:hover {
    background: #008080 !important;
    text-decoration: none;
}
#testquestion1
{
    display: none;
}
.home_go
{
position: absolute;
height: 40px;
width: 40px;
top: 5%;
left: 5%;
float: left;
background: url(../images/tocIcon.png) no-repeat;
background-size: contain;
}


.calc-container
{
position: absolute;
height: 40px;
width: 40px;
top: 5%;
left: 14%;
float: left;
background: url(../images/calc.png) no-repeat;
background-size: contain;
}




.mainhome_go
{
position: absolute;
height: 40px;
width: 40px;
top: -2%;
left: 5%;
float: left;
background: url(../images/homeIcon.png) no-repeat;
background-size: contain;
}
.go_next
{
position: absolute;
right: 0%;
bottom: 0%;
height: 65px;
width: 65px;
/*top: -2%;
left: 5%;
float: left;*/
background: url(../images/nextActive.png) no-repeat;
background-size: contain;    
}
.go_prev
{
position: absolute;
left: 0%;
bottom: 0%;
height: 65px;
width: 65px;
/*top: -2%;
left: 5%;
float: left;*/
background: url(../images/prevActive.png) no-repeat;
background-size: contain;    
}
.foot_ques
{
    position: relative;
    color: #ffffff;
    font-size: 28px;
    margin: auto;
    margin-top: 6px;
    width: 6% !important;
    /*border-radius: 10px;
    background: #fff;*/
    padding: 10px;
    background: rgba(3, 28, 58, 0.5);
    border-radius: 4px;
    border: 1px solid #0c364e;
    -webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
    -moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
    box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5)    
}

.submit_icon
{
    position: relative;
    margin: auto;
    margin-top: 2%;
    width: 10% !important;
    height: 6%;
    line-height: 40px;
    text-align: center;
    display: none;
    background: rgba(3, 28, 58, 0.5);
    border-radius: 4px;
    border: 1px solid #fff;
    -webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
    -moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
    box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
    color: #ffffff;
}

#feed,#feed2,#feed3,#feed4
{
    position: absolute;
top: 75%;
width: 50%;
/*border: 1px solid black;*/
display: none;
left: 37%;
}
#correct_ans,#wrong_ans,#correct_ans2,#wrong_ans2,#correct_ans3,#wrong_ans3,#correct_ans4,#wrong_ans4
{
    position: relative;
    margin-left: 30px;
    font-size: 50px;
}
#wrong_ans,#wrong_ans2,#wrong_ans3,#wrong_ans4
{
color: rgb(202, 29, 42);
}
#correct_ans,#correct_ans2,#correct_ans3,#correct_ans4
{
    color: rgb(68, 175, 73);
}




@media all and (max-width: 1000px) {
    .foot_ques
    {
	position:  relative;
	color: #ffffff;
	font-size: 28px;
	margin: auto;
	margin-top: 6px;
	width: 18% !important;
	padding: 10px;
	background: rgba(3, 28, 58, 0.5);
	border-radius: 4px;
	border: 1px solid #0c364e;
	-webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	-moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5)    
    }
    
    .submit_icon
    {
	position: relative;
	margin: auto;
	margin-top: 2%;
	width: 18% !important;
	height: 6%;
	line-height: 40px;
	text-align: center;
	display: none;
	background: rgba(3, 28, 58, 0.5);
	border-radius: 4px;
	border: 1px solid #fff;
	-webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	-moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
        color: #ffffff;
    }
    .calc-container {
        left: 14%;
    }
    #indexLogo img
    {
	width: 300px;
    }
    .testPageWhiteBoxTop
    {
	height: px;
    }
    .testPageGreyAnswerBoxWidth {
        margin-top: -60px;
    }
	
	.dropDiv,.dropDiv1{
		position: absolute;
		width: 1%;
		margin-top: ;
	}
	.margin_extend1
	{
		margin-top: ;
	}
	.margin_extend2
	{
		margin-top: ;
	}
	.audio_top
	{
	    top: -4px !important;
	}
}

@media all and (max-width: 550px) {
    .foot_ques
    {
	position:  relative;
	color: #ffffff;
	font-size: 28px;
	margin: auto;
	margin-top: 6px;
	width: 20% !important;
	padding: 10px;
	background: rgba(3, 28, 58, 0.5);
	border-radius: 4px;
	border: 1px solid #0c364e;
	-webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	-moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5)    
    }
    
    .submit_icon
    {
	position: relative;
	margin: auto;
	margin-top: 2%;
	width: 26% !important;
	height: 6%;
	line-height: 40px;
	text-align: center;
	display: none;
	background: rgba(3, 28, 58, 0.5);
	border-radius: 4px;
	border: 1px solid #fff;
	-webkit-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	-moz-box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
	box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
        color: #ffffff;
    }

    .calc-container {
        left: 18%;
    }
    #indexLogo img
    {
	width: 220px;
    }
    .testPageWhiteBoxTop
    {
	height: 130px;
    }
    .testPageGreyAnswerBoxWidth {
        margin-top: -110px;
    }
    .normalTimes{
	/*width: 70%;*/
    }
	.dropDiv,.dropDiv1{
		position: absolute;
		width: 80px;
		margin-top: 30px;
	}
	.margin_extend1
	{
		margin-top: 20px;
	}
	.margin_extend2
	{
		margin-top: 10px;
	}
	.audio_top
	{
	    top: 16px !important;
	}
}

#blocker
{
	position: absolute;
	width: 100%;
	height: 100%;
	display: none;
	background: rgba(0,0,0,0.5);
	z-index: 20;
}

#feedback
{
    position: absolute;
    width: 30%;
    height: 30%;
    top: 30%;
    left: 35%;
    z-index: 21;
    display: none;
    color: #ffffff;
    background:#1176bf;
    border-radius: 15px;
}

#close_feed
{
    position: absolute;
    width: 20px;
    height: 20px;
    top: -4%;
    right: -2%;
    background: url(../images/close_btn.png);
    background-size: 100% 100%;
}
#fed_correct,#cor_ans
{
	position: absolute;
	top: 30%;
	left: 17%;
	color:#ffffff;
	line-height: 25px;;
	font-size: 180%;

}
#fed_incorrect,#wro_ans
{
	position: absolute;
	top: 55%;
	left: 17%;
	color:#ffffff;
	line-height: 25px;;
	font-size: 180%;

}
#cor_ans
{
    left: 74%;
}
#wro_ans
{
    left: 74%;
}
.b1
{
    background: #24475e;
    background-image: -webkit-linear-gradient(top, #94DAFF, #5cb85c);
    background-image: -moz-linear-gradient(top, #94DAFF, #5cb85c);
    background-image: -ms-linear-gradient(top, #94DAFF, #5cb85c);
    background-image: -o-linear-gradient(top, #94DAFF, #5cb85c);
    background-image: linear-gradient(to bottom, #94DAFF,#5cb85c);
    /*background:#5cb85c;*/
    
    background: -webkit-gradient(linear, left top, left bottom, from(#c8dd95), to(#428739));
    /*border: 1px solid rgba(0, 0, 0, 0.3);*/
    -webkit-box-shadow: 0 0 .05em rgba(0, 0, 0, 0.4);
}

.b1:hover {
    background: #428739 !important;
    text-decoration: none;
}

.b1 span{
    border-top: 0px solid rgba(255, 255, 255, 0.5);
    display: block;
    border-radius: .3em;
    background-image: -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05))), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05)));
    background-size: 3px 3px;
}


.b2
{
    background: #24475e;
    background-image: -webkit-linear-gradient(top, #9dddff, #5bc0de);
    background-image: -moz-linear-gradient(top, #9dddff, #5bc0de);
    background-image: -ms-linear-gradient(top, #9dddff, #5bc0de);
    background-image: -o-linear-gradient(top, #9dddff, #5bc0de);
    background-image: linear-gradient(to bottom, #9dddff,#5bc0de);
    /*background:#5bc0de;*/
    
    background: -webkit-gradient(linear, left top, left bottom, from(#B8A9F3), to(#6F50E7));
    /*border: 1px solid rgba(0, 0, 0, 0.3);*/
    -webkit-box-shadow: 0 0 .05em rgba(0, 0, 0, 0.4);
    
}

.b2 span{
    border-top: 0px solid rgba(255, 255, 255, 0.5);
    display: block;
    border-radius: .3em;
    background-image: -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05))), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05)));
    background-size: 3px 3px;
}


.b2:hover {
    background: #6F50E7 !important;
    text-decoration: none;
}

.b3
{
    background: #24475e;
    background-image: -webkit-linear-gradient(top, #94DAFF, #f0ad4e);
    background-image: -moz-linear-gradient(top, #94DAFF, #f0ad4e);
    background-image: -ms-linear-gradient(top, #94DAFF, #f0ad4e);
    background-image: -o-linear-gradient(top, #94DAFF, #f0ad4e);
    background-image: linear-gradient(to bottom, #94DAFF,#f0ad4e);
    /*background:#f0ad4e;*/
    
    background:-webkit-gradient(linear, left top, left bottom, from(#FAE6A7), to(#E79616));
    /*border: 1px solid rgba(0, 0, 0, 0.3);*/
    -webkit-box-shadow: 0 0 .05em rgba(0, 0, 0, 0.4);
    
}

.b3 span{
    border-top: 0px solid rgba(255, 255, 255, 0.5);
    display: block;
    border-radius: .3em;
    background-image: -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05))), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05)));
    background-size: 3px 3px;
}

.b3:hover {
    background: #f09c15 !important;
    text-decoration: none;
}


.b4
{
    background: #24475e;
    background-image: -webkit-linear-gradient(top, #94DAFF, #d9534f);
    background-image: -moz-linear-gradient(top, #94DAFF, #d9534f);
    background-image: -ms-linear-gradient(top, #94DAFF, #d9534f);
    background-image: -o-linear-gradient(top, #94DAFF, #d9534f);
    background-image: linear-gradient(to bottom, #94DAFF,#d9534f);
    /*background:#d9534f;*/
    
    background: -webkit-gradient(linear, left top, left bottom, from(#EC889F), to(#F2566D));
     /*border: 1px solid rgba(0, 0, 0, 0.3);*/
    -webkit-box-shadow: 0 0 .05em rgba(0, 0, 0, 0.4);
}


.b4 span{
    border-top: 0px solid rgba(255, 255, 255, 0.5);
    display: block;
    border-radius: .3em;
    background-image: -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.25, rgba(0, 0, 0, 0.05)), color-stop(.25, transparent), to(transparent)), -webkit-gradient(linear, 0 0, 100% 100%, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05))), -webkit-gradient(linear, 0 100%, 100% 0, color-stop(.75, transparent), color-stop(.75, rgba(0, 0, 0, 0.05)));
    background-size: 3px 3px;
}


.b4:hover {
    background: #D82741 !important;
    text-decoration: none;
}



.numTxt{
    font-size: 100% !important;
}

#answerchoose1,#answerchoose4
{
    height: 400px;
}


@media all and (max-width: 350px) {
    #indexLogo img{
	margin-top: 14%;
    }
    .testPageLogo{
	width: 140px;
    }

    .home_go
    {
	left: 6px;
    }
    .calc-container
    {
	left: 56px;
    }
    #feedback{
	width: 190px;
	left: 14%;
    }
   
    .audio_top
    {
	top: 5px !important;
    }
    
    .dropDiv, .dropDiv1{
	width:60px;
    }
	
    #inp1{
	width: 62px !important;
	
    }
    
    form {
	margin-top: 70px;
    }
    
    .audio_top img{
	width: 40px;
	height: 40px;
    }
    
}
.audio_top
	{
	    top: -12px;
	}
	
	
	vkeypad.css
	============
	
	@font-face{font-family:'mclarenregular'; src:url(../fonts/mclarenregular-webfont.ttf)}
.keypadHolder{
   display: none;
    z-index:9010; /*font-weight:bold;*/ background: #77B087; z-index: 3000; border-radius:5px; box-shadow: rgba(0, 0, 30, 0.1) 0px 2px 10px 8px;
   height: 210px !important;
   }
.vkBtnKey{vertical-align:middle; text-align:center; background:#fff;  border-radius:5px;  font-size:28px; margin: 4px; line-height: 40px;}
.vkBtnKey.disabled{background:#486b25; color: #ccc;}
.vkBtnKey.active>*{opacity: 0.2;}
.vkBtnKey>*{display:inline-block; width:100%;}
.key_multi_0.inactive, .key_multi_1.inactive{opacity: 0.2;}
.vkBtnEmpty{vertical-align:middle; text-align:center; display:table-cell;}
.vkBtnCls{text-align:center; font-size: 14px; width: 20px; height: 20px; background:url(../images/close_btn.png) no-repeat; cursor: pointer;}
#key_close{ float: right; margin-top: -10px; margin-right: -10px; height: 20px; }
#key_backspace{ float: right; background: none; }
#key_backspace>*{
   margin: auto;
   margin-top: 6px;
}
#key_shift>*{
   margin-top: 5px;
}
.vKeyPad_headerKeys{height: 10px;}
.vKeyPadKeySet > div > div {margin-top: 0px;}
.key_multi_0, .key_multi_1{font-size: 20px; line-height: 20px;}
.vkMultiKey{line-height: 20px; font-size: 20px;}

.numeric .vKeyPad_contentKeys>div:last-of-type{
   display: inline-block;
   float: left;
}

.numeric .vKeyPad_footerKeys{
   float: right;
}

.keypadContainer{
   position: absolute;
   top:300px !important;
   right:100px !important;
}



calculator.js
==========

var rnc = rnc || {};
var calFUN=false;
// Display in this case refers to the input type="text" above the buttons
rnc.Display = function () {
  var $displayControl,
    operator,
    operatorSet = false,
    equalsPressed = false,
    accumulator = null,

    add = function (x, y) {
      return x + y;
    
    },
    divide = function (x, y) {
      if (y == 0) {
        //alert("Can't divide by 0");
        return "error";
      }
      return x / y;
    },
    multiply = function (x, y) {
      return x * y;
    },
    subtract = function (x, y) {
      return x - y;
    },
    calculate = function () {
      if (calFUN==true) {
      
      
      if (!operator || accumulator == null) return;
      var currNumber = parseFloat($displayControl.value),
        newVal = 0;
           
           //console.log(operator,"operator")
        
      switch (operator) {
        case "+":
	  console.log(accumulator,currNumber,"accumulator")
          newVal = add(accumulator, currNumber);
	  
           //var strint = require("./strint");
	  //console.log(strint.add("454456546","1"),"add fun")
          break;
        case "-":
          newVal = subtract(accumulator, currNumber);
          break;
        case "*":
          newVal = multiply(accumulator, currNumber);
          break;
        case "/":
          newVal = divide(accumulator, currNumber);
          break;
        case "%":
          newVal = currNumber / 100;
          break;
        case "+/-":
          newVal = -currNumber;
          break;
      }
      setValue(newVal);
      //accumulator = newVal;
      calFUN=false;
    }
    },

    setValue = function (val) {
       if (val==".") {
	val="0."
      }
      
      $displayControl.value = val;
  
      onlyDisplayPanel.value = commafy(val);
      
     
//    if (String(val).length > 9 ) {
//        val=val.toExponential(9)
//	onlyDisplayPanel.value = commafy(val);
//	
//      }
//      else
//      {
//	console.log("display else")
//	onlyDisplayPanel.value = commafy(val);
//      }
      
       if ($("#onlyDisplayPanel").val()==Infinity) {
	$("#onlyDisplayPanel").val("error");
      }
      
    },

    getValue = function () {
      return $displayControl.value + "";
    },

  // clears all of the digits
    clearDisplay = function () {
      accumulator = null;
      equalsPressed = operatorSet = false;
      setValue("0");
      calFUN=false;
    },

  // removes the last digit entered in the display
    clearError = function () {
      var display = getValue();
      // if the string is valid, remove the right most character from it
      // remember: to be valid, must have a value and length
      if (display) {
        display = display.slice(0, display.length - 1);
        display = display ? display : "0";
        setValue(display);
      }
    },

  // handles a numeric or decimal point key being entered
    enterDigit = function (buttonValue) {
      var currentlyDisplayed = $displayControl.value;
     console.log(currentlyDisplayed.indexOf("."),operatorSet)
      // keep the max digits to a reasonable number
      if (currentlyDisplayed.length <9 || operatorSet == true || equalsPressed ==true) {
	
	  if (buttonValue === "." && currentlyDisplayed.indexOf(".") >= 0 && operatorSet==false && equalsPressed==false ) {
          return;
        }
        else  if (buttonValue === "." && currentlyDisplayed=="0") {
           setValue("0");
        }
	
        if (operatorSet == true || currentlyDisplayed === "0") {
	  console.log()
          setValue("");
          operatorSet = false;
        }
	//if (buttonValue === "." && operatorSet==true) {
	//  console.log("before return")
	//  setValue("0.")
	//}
        // already pressed a decimal point
	
        //if (buttonValue === "." && currentlyDisplayed.indexOf(".") >= 0) {
        //  return;
        //}
        //else  if (buttonValue === "." && currentlyDisplayed=="0") {
        //   setValue("0");
        //}
        //setValue($displayControl.value + buttonValue);	
        if (equalsPressed == true) {
	  console.log("enter operator")
          $displayControl.value=""
          setValue($displayControl.value + buttonValue);
	  equalsPressed =false;
        }
        else{
          setValue($displayControl.value + buttonValue);
        }
      }
      calFUN=true
    },

    setPercent = function(){
      var currentlyDisplayed = $displayControl.value;
      if(currentlyDisplayed) {
        setValue(currentlyDisplayed / 100);
      }
    },

    reverseSign = function(){
      var currentlyDisplayed = $displayControl.value;
      if(currentlyDisplayed) {
        setValue(-currentlyDisplayed);
      }
    },

    setOperator = function (newOperator) {

      if (newOperator === "=") {
        equalsPressed = true;
	
        calculate();
	accumulator=null;
        return;
      }
      console.log(newOperator,"newOperator")
      //if (!equalsPressed) calculate();
      if ( operatorSet ==false) {
      if (newOperator === "-" || newOperator === "+" || newOperator === "/" || newOperator === "*" ) {
	 calculate();
      }
       }
      equalsPressed = false;
      operator = newOperator;
      operatorSet = true;
      accumulator = parseFloat($displayControl.value);
    },

  // set the pointer to the HTML element which displays the text
    init = function (currNumber) {
      $displayControl = currNumber;
    };

  // all of the methods below are public
  return {
    clearDisplay: clearDisplay,
    clearError: clearError,
    enterDigit: enterDigit,
    setOperator: setOperator,
    setPercent: setPercent,
    reverseSign: reverseSign,
    init: init
  };
}();

rnc.calculator = function () {
  rnc.Display.init($("#displayPanel")[0]);

  $(".key").on('click', function (event) {
    var key = $(this).attr("data-rnc-tag"),
      id = this.id;

    // this is a performance boost
    event.preventDefault();
    event.stopPropagation();
    switch (id) {
      case "key0":
      case "key1":
      case "key2":
      case "key3":
      case "key4":
      case "key5":
      case "key6":
      case "key7":
      case "key8":
      case "key9":
      case "keyDecimalPoint":
        rnc.Display.enterDigit(key);
        break;
      case "keyC":
        rnc.Display.clearDisplay();
        break;
      case "keyCe":
        rnc.Display.clearError();
        break;
      case "keyAdd":
        rnc.Display.setOperator("+");
        break;
      case "keySubtract":
        rnc.Display.setOperator("-");
        break;
      case "keyMultiply":
        rnc.Display.setOperator("*");
        break;
      case "keyDivide":
        rnc.Display.setOperator("/");
        break;
      case "keyEquals":
        rnc.Display.setOperator("=");
        break;
      //case "keyPercent":
      //  rnc.Display.setPercent();
      //  break;
      //case "keyPlusMinus":
      //  rnc.Display.reverseSign();
      //  break;
    }
    return false;
  });
}
String.prototype.commafy = function () {
	return this.replace(/(^|[^\w.])(\d{4,})/g, function($0, $1, $2) {
		return $1 + $2.replace(/\d(?=(?:\d\d\d)+(?!\d))/g, "$&,");
	});
}

Number.prototype.commafy = function () {
	return String(this).commafy();
}

function commafy(num) {
    var str = num.toString().split('.');
    if (str[0].length >= 4) {
        str[0] = str[0].replace(/(\d)(?=(\d{3})+$)/g, '$1,');
    }
    if (str[1] && str[1].length >= 4) {
        str[1] = str[1].replace(/(\d{3})/g, '$1 ');
    }
    return str.join('.');
}


jquerymobile.js
==========/*
* jQuery Mobile Framework Git Build: SHA1: b49cc06499abf8f987cf90f35349cfac0918c939 <> Date: Tue Oct 2 11:22:34 2012 -0700
* http://jquerymobile.com
*
* Copyright 2012 jQuery Foundation and other contributors
* Released under the MIT license.
* http://jquery.org/license
*
*/


(function ( root, doc, factory ) {
	if ( typeof define === "function" && define.amd ) {
		// AMD. Register as an anonymous module.
		define( [ "jquery" ], function ( $ ) {
			factory( $, root, doc );
			return $.mobile;
		});
	} else {
		// Browser globals
		factory( root.jQuery, root, doc );
	}
}( this, document, function ( jQuery, window, document, undefined ) {
(function( $, window, undefined ) {

	var nsNormalizeDict = {};

	// jQuery.mobile configurable options
	$.mobile = $.extend( {}, {

		// Version of the jQuery Mobile Framework
		version: "1.2.0",

		// Namespace used framework-wide for data-attrs. Default is no namespace
		ns: "",

		// Define the url parameter used for referencing widget-generated sub-pages.
		// Translates to to example.html&ui-page=subpageIdentifier
		// hash segment before &ui-page= is used to make Ajax request
		subPageUrlKey: "ui-page",

		// Class assigned to page currently in view, and during transitions
		activePageClass: "ui-page-active",

		// Class used for "active" button state, from CSS framework
		activeBtnClass: "ui-btn-active",

		// Class used for "focus" form element state, from CSS framework
		focusClass: "ui-focus",

		// Automatically handle clicks and form submissions through Ajax, when same-domain
		ajaxEnabled: true,

		// Automatically load and show pages based on location.hash
		hashListeningEnabled: true,

		// disable to prevent jquery from bothering with links
		linkBindingEnabled: true,

		// Set default page transition - 'none' for no transitions
		defaultPageTransition: "fade",

		// Set maximum window width for transitions to apply - 'false' for no limit
		maxTransitionWidth: false,

		// Minimum scroll distance that will be remembered when returning to a page
		minScrollBack: 250,

		// DEPRECATED: the following property is no longer in use, but defined until 2.0 to prevent conflicts
		touchOverflowEnabled: false,

		// Set default dialog transition - 'none' for no transitions
		defaultDialogTransition: "pop",

		// Error response message - appears when an Ajax page request fails
		pageLoadErrorMessage: "Error Loading Page",

		// For error messages, which theme does the box uses?
		pageLoadErrorMessageTheme: "e",

		// replace calls to window.history.back with phonegaps navigation helper
		// where it is provided on the window object
		phonegapNavigationEnabled: false,

		//automatically initialize the DOM when it's ready
		autoInitializePage: true,

		pushStateEnabled: true,

		// allows users to opt in to ignoring content by marking a parent element as
		// data-ignored
		ignoreContentEnabled: false,

		// turn of binding to the native orientationchange due to android orientation behavior
		orientationChangeEnabled: true,

		buttonMarkup: {
			hoverDelay: 200
		},

		// TODO might be useful upstream in jquery itself ?
		keyCode: {
			ALT: 18,
			BACKSPACE: 8,
			CAPS_LOCK: 20,
			COMMA: 188,
			COMMAND: 91,
			COMMAND_LEFT: 91, // COMMAND
			COMMAND_RIGHT: 93,
			CONTROL: 17,
			DELETE: 46,
			DOWN: 40,
			END: 35,
			ENTER: 13,
			ESCAPE: 27,
			HOME: 36,
			INSERT: 45,
			LEFT: 37,
			MENU: 93, // COMMAND_RIGHT
			NUMPAD_ADD: 107,
			NUMPAD_DECIMAL: 110,
			NUMPAD_DIVIDE: 111,
			NUMPAD_ENTER: 108,
			NUMPAD_MULTIPLY: 106,
			NUMPAD_SUBTRACT: 109,
			PAGE_DOWN: 34,
			PAGE_UP: 33,
			PERIOD: 190,
			RIGHT: 39,
			SHIFT: 16,
			SPACE: 32,
			TAB: 9,
			UP: 38,
			WINDOWS: 91 // COMMAND
		},

		// Scroll page vertically: scroll to 0 to hide iOS address bar, or pass a Y value
		silentScroll: function( ypos ) {
			if ( $.type( ypos ) !== "number" ) {
				ypos = $.mobile.defaultHomeScroll;
			}

			// prevent scrollstart and scrollstop events
			$.event.special.scrollstart.enabled = false;

			setTimeout( function() {
				window.scrollTo( 0, ypos );
				$( document ).trigger( "silentscroll", { x: 0, y: ypos });
			}, 20 );

			setTimeout( function() {
				$.event.special.scrollstart.enabled = true;
			}, 150 );
		},

		// Expose our cache for testing purposes.
		nsNormalizeDict: nsNormalizeDict,

		// Take a data attribute property, prepend the namespace
		// and then camel case the attribute string. Add the result
		// to our nsNormalizeDict so we don't have to do this again.
		nsNormalize: function( prop ) {
			if ( !prop ) {
				return;
			}

			return nsNormalizeDict[ prop ] || ( nsNormalizeDict[ prop ] = $.camelCase( $.mobile.ns + prop ) );
		},

		// Find the closest parent with a theme class on it. Note that
		// we are not using $.fn.closest() on purpose here because this
		// method gets called quite a bit and we need it to be as fast
		// as possible.
		getInheritedTheme: function( el, defaultTheme ) {
			var e = el[ 0 ],
				ltr = "",
				re = /ui-(bar|body|overlay)-([a-z])\b/,
				c, m;

			while ( e ) {
				c = e.className || "";
				if ( c && ( m = re.exec( c ) ) && ( ltr = m[ 2 ] ) ) {
					// We found a parent with a theme class
					// on it so bail from this loop.
					break;
				}

				e = e.parentNode;
			}

			// Return the theme letter we found, if none, return the
			// specified default.

			return ltr || defaultTheme || "a";
		},

		// TODO the following $ and $.fn extensions can/probably should be moved into jquery.mobile.core.helpers
		//
		// Find the closest javascript page element to gather settings data jsperf test
		// http://jsperf.com/single-complex-selector-vs-many-complex-selectors/edit
		// possibly naive, but it shows that the parsing overhead for *just* the page selector vs
		// the page and dialog selector is negligable. This could probably be speed up by
		// doing a similar parent node traversal to the one found in the inherited theme code above
		closestPageData: function( $target ) {
			return $target
				.closest( ':jqmData(role="page"), :jqmData(role="dialog")' )
				.data( "page" );
		},

		enhanceable: function( $set ) {
			return this.haveParents( $set, "enhance" );
		},

		hijackable: function( $set ) {
			return this.haveParents( $set, "ajax" );
		},

		haveParents: function( $set, attr ) {
			if ( !$.mobile.ignoreContentEnabled ) {
				return $set;
			}

			var count = $set.length,
				$newSet = $(),
				e, $element, excluded;

			for ( var i = 0; i < count; i++ ) {
				$element = $set.eq( i );
				excluded = false;
				e = $set[ i ];

				while ( e ) {
					var c = e.getAttribute ? e.getAttribute( "data-" + $.mobile.ns + attr ) : "";

					if ( c === "false" ) {
						excluded = true;
						break;
					}

					e = e.parentNode;
				}

				if ( !excluded ) {
					$newSet = $newSet.add( $element );
				}
			}

			return $newSet;
		},

		getScreenHeight: function() {
			// Native innerHeight returns more accurate value for this across platforms,
			// jQuery version is here as a normalized fallback for platforms like Symbian
			return window.innerHeight || $( window ).height();
		}
	}, $.mobile );

	// Mobile version of data and removeData and hasData methods
	// ensures all data is set and retrieved using jQuery Mobile's data namespace
	$.fn.jqmData = function( prop, value ) {
		var result;
		if ( typeof prop !== "undefined" ) {
			if ( prop ) {
				prop = $.mobile.nsNormalize( prop );
			}

			// undefined is permitted as an explicit input for the second param
			// in this case it returns the value and does not set it to undefined
			if( arguments.length < 2 || value === undefined ){
				result = this.data( prop );
			} else {
				result = this.data( prop, value );
			}
		}
		return result;
	};

	$.jqmData = function( elem, prop, value ) {
		var result;
		if ( typeof prop !== "undefined" ) {
			result = $.data( elem, prop ? $.mobile.nsNormalize( prop ) : prop, value );
		}
		return result;
	};

	$.fn.jqmRemoveData = function( prop ) {
		return this.removeData( $.mobile.nsNormalize( prop ) );
	};

	$.jqmRemoveData = function( elem, prop ) {
		return $.removeData( elem, $.mobile.nsNormalize( prop ) );
	};

	$.fn.removeWithDependents = function() {
		$.removeWithDependents( this );
	};

	$.removeWithDependents = function( elem ) {
		var $elem = $( elem );

		( $elem.jqmData( 'dependents' ) || $() ).remove();
		$elem.remove();
	};

	$.fn.addDependents = function( newDependents ) {
		$.addDependents( $( this ), newDependents );
	};

	$.addDependents = function( elem, newDependents ) {
		var dependents = $( elem ).jqmData( 'dependents' ) || $();

		$( elem ).jqmData( 'dependents', $.merge( dependents, newDependents ) );
	};

	// note that this helper doesn't attempt to handle the callback
	// or setting of an html elements text, its only purpose is
	// to return the html encoded version of the text in all cases. (thus the name)
	$.fn.getEncodedText = function() {
		return $( "<div/>" ).text( $( this ).text() ).html();
	};

	// fluent helper function for the mobile namespaced equivalent
	$.fn.jqmEnhanceable = function() {
		return $.mobile.enhanceable( this );
	};

	$.fn.jqmHijackable = function() {
		return $.mobile.hijackable( this );
	};

	// Monkey-patching Sizzle to filter the :jqmData selector
	var oldFind = $.find,
		jqmDataRE = /:jqmData\(([^)]*)\)/g;

	$.find = function( selector, context, ret, extra ) {
		selector = selector.replace( jqmDataRE, "[data-" + ( $.mobile.ns || "" ) + "$1]" );

		return oldFind.call( this, selector, context, ret, extra );
	};

	$.extend( $.find, oldFind );

	$.find.matches = function( expr, set ) {
		return $.find( expr, null, null, set );
	};

	$.find.matchesSelector = function( node, expr ) {
		return $.find( expr, null, null, [ node ] ).length > 0;
	};
})( jQuery, this );


/*!
 * jQuery UI Widget v1.9.0-beta.1
 *
 * Copyright 2012, https://github.com/jquery/jquery-ui/blob/1.9.0-beta.1/AUTHORS.txt (http://jqueryui.com/about)
 * Dual licensed under the MIT or GPL Version 2 licenses.
 * http://jquery.org/license
 *
 * http://docs.jquery.com/UI/Widget
 */
(function( $, undefined ) {

var uuid = 0,
	slice = Array.prototype.slice,
	_cleanData = $.cleanData;
$.cleanData = function( elems ) {
	for ( var i = 0, elem; (elem = elems[i]) != null; i++ ) {
		try {
			$( elem ).triggerHandler( "remove" );
		// http://bugs.jquery.com/ticket/8235
		} catch( e ) {}
	}
	_cleanData( elems );
};

$.widget = function( name, base, prototype ) {
	var fullName, existingConstructor, constructor, basePrototype,
		namespace = name.split( "." )[ 0 ];

	name = name.split( "." )[ 1 ];
	fullName = namespace + "-" + name;

	if ( !prototype ) {
		prototype = base;
		base = $.Widget;
	}

	// create selector for plugin
	$.expr[ ":" ][ fullName ] = function( elem ) {
		return !!$.data( elem, fullName );
	};

	$[ namespace ] = $[ namespace ] || {};
	existingConstructor = $[ namespace ][ name ];
	constructor = $[ namespace ][ name ] = function( options, element ) {
		// allow instantiation without "new" keyword
		if ( !this._createWidget ) {
			return new constructor( options, element );
		}

		// allow instantiation without initializing for simple inheritance
		// must use "new" keyword (the code above always passes args)
		if ( arguments.length ) {
			this._createWidget( options, element );
		}
	};
	// extend with the existing constructor to carry over any static properties
	$.extend( constructor, existingConstructor, {
		version: prototype.version,
		// copy the object used to create the prototype in case we need to
		// redefine the widget later
		_proto: $.extend( {}, prototype ),
		// track widgets that inherit from this widget in case this widget is
		// redefined after a widget inherits from it
		_childConstructors: []
	});

	basePrototype = new base();
	// we need to make the options hash a property directly on the new instance
	// otherwise we'll modify the options hash on the prototype that we're
	// inheriting from
	basePrototype.options = $.widget.extend( {}, basePrototype.options );
	$.each( prototype, function( prop, value ) {
		if ( $.isFunction( value ) ) {
			prototype[ prop ] = (function() {
				var _super = function() {
						return base.prototype[ prop ].apply( this, arguments );
					},
					_superApply = function( args ) {
						return base.prototype[ prop ].apply( this, args );
					};
				return function() {
					var __super = this._super,
						__superApply = this._superApply,
						returnValue;

					this._super = _super;
					this._superApply = _superApply;

					returnValue = value.apply( this, arguments );

					this._super = __super;
					this._superApply = __superApply;

					return returnValue;
				};
			})();
		}
	});
	constructor.prototype = $.widget.extend( basePrototype, {
		// TODO: remove support for widgetEventPrefix
		// always use the name + a colon as the prefix, e.g., draggable:start
		// don't prefix for widgets that aren't DOM-based
		widgetEventPrefix: name
	}, prototype, {
		constructor: constructor,
		namespace: namespace,
		widgetName: name,
		// TODO remove widgetBaseClass, see #8155
		widgetBaseClass: fullName,
		widgetFullName: fullName
	});

	// If this widget is being redefined then we need to find all widgets that
	// are inheriting from it and redefine all of them so that they inherit from
	// the new version of this widget. We're essentially trying to replace one
	// level in the prototype chain.
	if ( existingConstructor ) {
		$.each( existingConstructor._childConstructors, function( i, child ) {
			var childPrototype = child.prototype;

			// redefine the child widget using the same prototype that was
			// originally used, but inherit from the new version of the base
			$.widget( childPrototype.namespace + "." + childPrototype.widgetName, constructor, child._proto );
		});
		// remove the list of existing child constructors from the old constructor
		// so the old child constructors can be garbage collected
		delete existingConstructor._childConstructors;
	} else {
		base._childConstructors.push( constructor );
	}

	$.widget.bridge( name, constructor );
};

$.widget.extend = function( target ) {
	var input = slice.call( arguments, 1 ),
		inputIndex = 0,
		inputLength = input.length,
		key,
		value;
	for ( ; inputIndex < inputLength; inputIndex++ ) {
		for ( key in input[ inputIndex ] ) {
			value = input[ inputIndex ][ key ];
			if (input[ inputIndex ].hasOwnProperty( key ) && value !== undefined ) {
				target[ key ] = $.isPlainObject( value ) ? $.widget.extend( {}, target[ key ], value ) : value;
			}
		}
	}
	return target;
};

$.widget.bridge = function( name, object ) {
	var fullName = object.prototype.widgetFullName;
	$.fn[ name ] = function( options ) {
		var isMethodCall = typeof options === "string",
			args = slice.call( arguments, 1 ),
			returnValue = this;

		// allow multiple hashes to be passed on init
		options = !isMethodCall && args.length ?
			$.widget.extend.apply( null, [ options ].concat(args) ) :
			options;

		if ( isMethodCall ) {
			this.each(function() {
				var methodValue,
					instance = $.data( this, fullName );
				if ( !instance ) {
					return $.error( "cannot call methods on " + name + " prior to initialization; " +
						"attempted to call method '" + options + "'" );
				}
				if ( !$.isFunction( instance[options] ) || options.charAt( 0 ) === "_" ) {
					return $.error( "no such method '" + options + "' for " + name + " widget instance" );
				}
				methodValue = instance[ options ].apply( instance, args );
				if ( methodValue !== instance && methodValue !== undefined ) {
					returnValue = methodValue && methodValue.jquery ?
						returnValue.pushStack( methodValue.get() ) :
						methodValue;
					return false;
				}
			});
		} else {
			this.each(function() {
				var instance = $.data( this, fullName );
				if ( instance ) {
					instance.option( options || {} )._init();
				} else {
					new object( options, this );
				}
			});
		}

		return returnValue;
	};
};

$.Widget = function( options, element ) {};
$.Widget._childConstructors = [];

$.Widget.prototype = {
	widgetName: "widget",
	widgetEventPrefix: "",
	defaultElement: "<div>",
	options: {
		disabled: false,

		// callbacks
		create: null
	},
	_createWidget: function( options, element ) {
		element = $( element || this.defaultElement || this )[ 0 ];
		this.element = $( element );
		this.uuid = uuid++;
		this.eventNamespace = "." + this.widgetName + this.uuid;
		this.options = $.widget.extend( {},
			this.options,
			this._getCreateOptions(),
			options );

		this.bindings = $();
		this.hoverable = $();
		this.focusable = $();

		if ( element !== this ) {
			// 1.9 BC for #7810
			// TODO remove dual storage
			$.data( element, this.widgetName, this );
			$.data( element, this.widgetFullName, this );
			this._on({ remove: "destroy" });
			this.document = $( element.style ?
				// element within the document
				element.ownerDocument :
				// element is window or document
				element.document || element );
			this.window = $( this.document[0].defaultView || this.document[0].parentWindow );
		}

		this._create();
		this._trigger( "create", null, this._getCreateEventData() );
		this._init();
	},
	_getCreateOptions: $.noop,
	_getCreateEventData: $.noop,
	_create: $.noop,
	_init: $.noop,

	destroy: function() {
		this._destroy();
		// we can probably remove the unbind calls in 2.0
		// all event bindings should go through this._on()
		this.element
			.unbind( this.eventNamespace )
			// 1.9 BC for #7810
			// TODO remove dual storage
			.removeData( this.widgetName )
			.removeData( this.widgetFullName )
			// support: jquery <1.6.3
			// http://bugs.jquery.com/ticket/9413
			.removeData( $.camelCase( this.widgetFullName ) );
		this.widget()
			.unbind( this.eventNamespace )
			.removeAttr( "aria-disabled" )
			.removeClass(
				this.widgetFullName + "-disabled " +
				"ui-state-disabled" );

		// clean up events and states
		this.bindings.unbind( this.eventNamespace );
		this.hoverable.removeClass( "ui-state-hover" );
		this.focusable.removeClass( "ui-state-focus" );
	},
	_destroy: $.noop,

	widget: function() {
		return this.element;
	},

	option: function( key, value ) {
		var options = key,
			parts,
			curOption,
			i;

		if ( arguments.length === 0 ) {
			// don't return a reference to the internal hash
			return $.widget.extend( {}, this.options );
		}

		if ( typeof key === "string" ) {
			// handle nested keys, e.g., "foo.bar" => { foo: { bar: ___ } }
			options = {};
			parts = key.split( "." );
			key = parts.shift();
			if ( parts.length ) {
				curOption = options[ key ] = $.widget.extend( {}, this.options[ key ] );
				for ( i = 0; i < parts.length - 1; i++ ) {
					curOption[ parts[ i ] ] = curOption[ parts[ i ] ] || {};
					curOption = curOption[ parts[ i ] ];
				}
				key = parts.pop();
				if ( value === undefined ) {
					return curOption[ key ] === undefined ? null : curOption[ key ];
				}
				curOption[ key ] = value;
			} else {
				if ( value === undefined ) {
					return this.options[ key ] === undefined ? null : this.options[ key ];
				}
				options[ key ] = value;
			}
		}

		this._setOptions( options );

		return this;
	},
	_setOptions: function( options ) {
		var key;

		for ( key in options ) {
			this._setOption( key, options[ key ] );
		}

		return this;
	},
	_setOption: function( key, value ) {
		this.options[ key ] = value;

		if ( key === "disabled" ) {
			this.widget()
				.toggleClass( this.widgetFullName + "-disabled ui-state-disabled", !!value )
				.attr( "aria-disabled", value );
			this.hoverable.removeClass( "ui-state-hover" );
			this.focusable.removeClass( "ui-state-focus" );
		}

		return this;
	},

	enable: function() {
		return this._setOption( "disabled", false );
	},
	disable: function() {
		return this._setOption( "disabled", true );
	},

	_on: function( element, handlers ) {
		// no element argument, shuffle and use this.element
		if ( !handlers ) {
			handlers = element;
			element = this.element;
		} else {
			// accept selectors, DOM elements
			element = $( element );
			this.bindings = this.bindings.add( element );
		}

		var instance = this;
		$.each( handlers, function( event, handler ) {
			function handlerProxy() {
				// allow widgets to customize the disabled handling
				// - disabled as an array instead of boolean
				// - disabled class as method for disabling individual parts
				if ( instance.options.disabled === true ||
						$( this ).hasClass( "ui-state-disabled" ) ) {
					return;
				}
				return ( typeof handler === "string" ? instance[ handler ] : handler )
					.apply( instance, arguments );
			}

			// copy the guid so direct unbinding works
			if ( typeof handler !== "string" ) {
				handlerProxy.guid = handler.guid =
					handler.guid || handlerProxy.guid || $.guid++;
			}

			var match = event.match( /^(\w+)\s*(.*)$/ ),
				eventName = match[1] + instance.eventNamespace,
				selector = match[2];
			if ( selector ) {
				instance.widget().delegate( selector, eventName, handlerProxy );
			} else {
				element.bind( eventName, handlerProxy );
			}
		});
	},

	_off: function( element, eventName ) {
		eventName = (eventName || "").split( " " ).join( this.eventNamespace + " " ) + this.eventNamespace;
		element.unbind( eventName ).undelegate( eventName );
	},

	_delay: function( handler, delay ) {
		function handlerProxy() {
			return ( typeof handler === "string" ? instance[ handler ] : handler )
				.apply( instance, arguments );
		}
		var instance = this;
		return setTimeout( handlerProxy, delay || 0 );
	},

	_hoverable: function( element ) {
		this.hoverable = this.hoverable.add( element );
		this._on( element, {
			mouseenter: function( event ) {
				$( event.currentTarget ).addClass( "ui-state-hover" );
			},
			mouseleave: function( event ) {
				$( event.currentTarget ).removeClass( "ui-state-hover" );
			}
		});
	},

	_focusable: function( element ) {
		this.focusable = this.focusable.add( element );
		this._on( element, {
			focusin: function( event ) {
				$( event.currentTarget ).addClass( "ui-state-focus" );
			},
			focusout: function( event ) {
				$( event.currentTarget ).removeClass( "ui-state-focus" );
			}
		});
	},

	_trigger: function( type, event, data ) {
		var prop, orig,
			callback = this.options[ type ];

		data = data || {};
		event = $.Event( event );
		event.type = ( type === this.widgetEventPrefix ?
			type :
			this.widgetEventPrefix + type ).toLowerCase();
		// the original event may come from any element
		// so we need to reset the target on the new event
		event.target = this.element[ 0 ];

		// copy original event properties over to the new event
		orig = event.originalEvent;
		if ( orig ) {
			for ( prop in orig ) {
				if ( !( prop in event ) ) {
					event[ prop ] = orig[ prop ];
				}
			}
		}

		this.element.trigger( event, data );
		return !( $.isFunction( callback ) &&
			callback.apply( this.element[0], [ event ].concat( data ) ) === false ||
			event.isDefaultPrevented() );
	}
};

$.each( { show: "fadeIn", hide: "fadeOut" }, function( method, defaultEffect ) {
	$.Widget.prototype[ "_" + method ] = function( element, options, callback ) {
		if ( typeof options === "string" ) {
			options = { effect: options };
		}
		var hasOptions,
			effectName = !options ?
				method :
				options === true || typeof options === "number" ?
					defaultEffect :
					options.effect || defaultEffect;
		options = options || {};
		if ( typeof options === "number" ) {
			options = { duration: options };
		}
		hasOptions = !$.isEmptyObject( options );
		options.complete = callback;
		if ( options.delay ) {
			element.delay( options.delay );
		}
		if ( hasOptions && $.effects && ( $.effects.effect[ effectName ] || $.uiBackCompat !== false && $.effects[ effectName ] ) ) {
			element[ method ]( options );
		} else if ( effectName !== method && element[ effectName ] ) {
			element[ effectName ]( options.duration, options.easing, callback );
		} else {
			element.queue(function( next ) {
				$( this )[ method ]();
				if ( callback ) {
					callback.call( element[ 0 ] );
				}
				next();
			});
		}
	};
});

// DEPRECATED
if ( $.uiBackCompat !== false ) {
	$.Widget.prototype._getCreateOptions = function() {
		return $.metadata && $.metadata.get( this.element[0] )[ this.widgetName ];
	};
}

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.widget", {
	// decorate the parent _createWidget to trigger `widgetinit` for users
	// who wish to do post post `widgetcreate` alterations/additions
	//
	// TODO create a pull request for jquery ui to trigger this event
	// in the original _createWidget
	_createWidget: function() {
		$.Widget.prototype._createWidget.apply( this, arguments );
		this._trigger( 'init' );
	},

	_getCreateOptions: function() {

		var elem = this.element,
			options = {};

		$.each( this.options, function( option ) {

			var value = elem.jqmData( option.replace( /[A-Z]/g, function( c ) {
							return "-" + c.toLowerCase();
						})
					);

			if ( value !== undefined ) {
				options[ option ] = value;
			}
		});

		return options;
	},

	enhanceWithin: function( target, useKeepNative ) {
		this.enhance( $( this.options.initSelector, $( target )), useKeepNative );
	},

	enhance: function( targets, useKeepNative ) {
		var page, keepNative, $widgetElements = $( targets ), self = this;

		// if ignoreContentEnabled is set to true the framework should
		// only enhance the selected elements when they do NOT have a
		// parent with the data-namespace-ignore attribute
		$widgetElements = $.mobile.enhanceable( $widgetElements );

		if ( useKeepNative && $widgetElements.length ) {
			// TODO remove dependency on the page widget for the keepNative.
			// Currently the keepNative value is defined on the page prototype so
			// the method is as well
			page = $.mobile.closestPageData( $widgetElements );
			keepNative = ( page && page.keepNativeSelector()) || "";

			$widgetElements = $widgetElements.not( keepNative );
		}

		$widgetElements[ this.widgetName ]();
	},

	raise: function( msg ) {
		throw "Widget [" + this.widgetName + "]: " + msg;
	}
});

})( jQuery );


(function( $, window ) {
	// DEPRECATED
	// NOTE global mobile object settings
	$.extend( $.mobile, {
		// DEPRECATED Should the text be visble in the loading message?
		loadingMessageTextVisible: undefined,

		// DEPRECATED When the text is visible, what theme does the loading box use?
		loadingMessageTheme: undefined,

		// DEPRECATED default message setting
		loadingMessage: undefined,

		// DEPRECATED
		// Turn on/off page loading message. Theme doubles as an object argument
		// with the following shape: { theme: '', text: '', html: '', textVisible: '' }
		// NOTE that the $.mobile.loading* settings and params past the first are deprecated
		showPageLoadingMsg: function( theme, msgText, textonly ) {
			$.mobile.loading( 'show', theme, msgText, textonly );
		},

		// DEPRECATED
		hidePageLoadingMsg: function() {
			$.mobile.loading( 'hide' );
		},

		loading: function() {
			this.loaderWidget.loader.apply( this.loaderWidget, arguments );
		}
	});

	// TODO move loader class down into the widget settings
	var loaderClass = "ui-loader", $html = $( "html" ), $window = $( window );

	$.widget( "mobile.loader", {
		// NOTE if the global config settings are defined they will override these
		//      options
		options: {
			// the theme for the loading message
			theme: "a",

			// whether the text in the loading message is shown
			textVisible: false,

			// custom html for the inner content of the loading message
			html: "",

			// the text to be displayed when the popup is shown
			text: "loading"
		},

		defaultHtml: "<div class='" + loaderClass + "'>" +
			"<span class='ui-icon ui-icon-loading'></span>" +
			"<h1></h1>" +
			"</div>",

		// For non-fixed supportin browsers. Position at y center (if scrollTop supported), above the activeBtn (if defined), or just 100px from top
		fakeFixLoader: function() {
			var activeBtn = $( "." + $.mobile.activeBtnClass ).first();

			this.element
				.css({
					top: $.support.scrollTop && $window.scrollTop() + $window.height() / 2 ||
						activeBtn.length && activeBtn.offset().top || 100
				});
		},

		// check position of loader to see if it appears to be "fixed" to center
		// if not, use abs positioning
		checkLoaderPosition: function() {
			var offset = this.element.offset(),
				scrollTop = $window.scrollTop(),
				screenHeight = $.mobile.getScreenHeight();

			if ( offset.top < scrollTop || ( offset.top - scrollTop ) > screenHeight ) {
				this.element.addClass( "ui-loader-fakefix" );
				this.fakeFixLoader();
				$window
					.unbind( "scroll", this.checkLoaderPosition )
					.bind( "scroll", this.fakeFixLoader );
			}
		},

		resetHtml: function() {
			this.element.html( $( this.defaultHtml ).html() );
		},

		// Turn on/off page loading message. Theme doubles as an object argument
		// with the following shape: { theme: '', text: '', html: '', textVisible: '' }
		// NOTE that the $.mobile.loading* settings and params past the first are deprecated
		// TODO sweet jesus we need to break some of this out
		show: function( theme, msgText, textonly ) {
			var textVisible, message, $header, loadSettings;

			this.resetHtml();

			// use the prototype options so that people can set them globally at
			// mobile init. Consistency, it's what's for dinner
			if ( $.type(theme) === "object" ) {
				loadSettings = $.extend( {}, this.options, theme );

				// prefer object property from the param then the old theme setting
				theme = loadSettings.theme || $.mobile.loadingMessageTheme;
			} else {
				loadSettings = this.options;

				// here we prefer the them value passed as a string argument, then
				// we prefer the global option because we can't use undefined default
				// prototype options, then the prototype option
				theme = theme || $.mobile.loadingMessageTheme || loadSettings.theme;
			}

			// set the message text, prefer the param, then the settings object
			// then loading message
			message = msgText || $.mobile.loadingMessage || loadSettings.text;

			// prepare the dom
			$html.addClass( "ui-loading" );

			if ( $.mobile.loadingMessage !== false || loadSettings.html ) {
				// boolean values require a bit more work :P, supports object properties
				// and old settings
				if ( $.mobile.loadingMessageTextVisible !== undefined ) {
					textVisible = $.mobile.loadingMessageTextVisible;
				} else {
					textVisible = loadSettings.textVisible;
				}

				// add the proper css given the options (theme, text, etc)
				// Force text visibility if the second argument was supplied, or
				// if the text was explicitly set in the object args
				this.element.attr("class", loaderClass +
					" ui-corner-all ui-body-" + theme +
					" ui-loader-" + ( textVisible || msgText || theme.text ? "verbose" : "default" ) +
					( loadSettings.textonly || textonly ? " ui-loader-textonly" : "" ) );

				// TODO verify that jquery.fn.html is ok to use in both cases here
				//      this might be overly defensive in preventing unknowing xss
				// if the html attribute is defined on the loading settings, use that
				// otherwise use the fallbacks from above
				if ( loadSettings.html ) {
					this.element.html( loadSettings.html );
				} else {
					this.element.find( "h1" ).text( message );
				}

				// attach the loader to the DOM
				this.element.appendTo( $.mobile.pageContainer );

				// check that the loader is visible
				this.checkLoaderPosition();

				// on scroll check the loader position
				$window.bind( "scroll", $.proxy( this.checkLoaderPosition, this ) );
			}
		},

		hide: function() {
			$html.removeClass( "ui-loading" );

			if ( $.mobile.loadingMessage ) {
				this.element.removeClass( "ui-loader-fakefix" );
			}

			$( window ).unbind( "scroll", $.proxy( this.fakeFixLoader, this) );
			$( window ).unbind( "scroll", $.proxy( this.checkLoaderPosition, this ) );
		}
	});

	$window.bind( 'pagecontainercreate', function() {
		$.mobile.loaderWidget = $.mobile.loaderWidget || $( $.mobile.loader.prototype.defaultHtml ).loader();
	});
})(jQuery, this);



// This plugin is an experiment for abstracting away the touch and mouse
// events so that developers don't have to worry about which method of input
// the device their document is loaded on supports.
//
// The idea here is to allow the developer to register listeners for the
// basic mouse events, such as mousedown, mousemove, mouseup, and click,
// and the plugin will take care of registering the correct listeners
// behind the scenes to invoke the listener at the fastest possible time
// for that device, while still retaining the order of event firing in
// the traditional mouse environment, should multiple handlers be registered
// on the same element for different events.
//
// The current version exposes the following virtual events to jQuery bind methods:
// "vmouseover vmousedown vmousemove vmouseup vclick vmouseout vmousecancel"

(function( $, window, document, undefined ) {

var dataPropertyName = "virtualMouseBindings",
	touchTargetPropertyName = "virtualTouchID",
	virtualEventNames = "vmouseover vmousedown vmousemove vmouseup vclick vmouseout vmousecancel".split( " " ),
	touchEventProps = "clientX clientY pageX pageY screenX screenY".split( " " ),
	mouseHookProps = $.event.mouseHooks ? $.event.mouseHooks.props : [],
	mouseEventProps = $.event.props.concat( mouseHookProps ),
	activeDocHandlers = {},
	resetTimerID = 0,
	startX = 0,
	startY = 0,
	didScroll = false,
	clickBlockList = [],
	blockMouseTriggers = false,
	blockTouchTriggers = false,
	eventCaptureSupported = "addEventListener" in document,
	$document = $( document ),
	nextTouchID = 1,
	lastTouchID = 0, threshold;

$.vmouse = {
	moveDistanceThreshold: 10,
	clickDistanceThreshold: 10,
	resetTimerDuration: 1500
};

function getNativeEvent( event ) {

	while ( event && typeof event.originalEvent !== "undefined" ) {
		event = event.originalEvent;
	}
	return event;
}

function createVirtualEvent( event, eventType ) {

	var t = event.type,
		oe, props, ne, prop, ct, touch, i, j, len;

	event = $.Event( event );
	event.type = eventType;

	oe = event.originalEvent;
	props = $.event.props;

	// addresses separation of $.event.props in to $.event.mouseHook.props and Issue 3280
	// https://github.com/jquery/jquery-mobile/issues/3280
	if ( t.search( /^(mouse|click)/ ) > -1 ) {
		props = mouseEventProps;
	}

	// copy original event properties over to the new event
	// this would happen if we could call $.event.fix instead of $.Event
	// but we don't have a way to force an event to be fixed multiple times
	if ( oe ) {
		for ( i = props.length, prop; i; ) {
			prop = props[ --i ];
			event[ prop ] = oe[ prop ];
		}
	}

	// make sure that if the mouse and click virtual events are generated
	// without a .which one is defined
	if ( t.search(/mouse(down|up)|click/) > -1 && !event.which ) {
		event.which = 1;
	}

	if ( t.search(/^touch/) !== -1 ) {
		ne = getNativeEvent( oe );
		t = ne.touches;
		ct = ne.changedTouches;
		touch = ( t && t.length ) ? t[0] : ( ( ct && ct.length ) ? ct[ 0 ] : undefined );

		if ( touch ) {
			for ( j = 0, len = touchEventProps.length; j < len; j++) {
				prop = touchEventProps[ j ];
				event[ prop ] = touch[ prop ];
			}
		}
	}

	return event;
}

function getVirtualBindingFlags( element ) {

	var flags = {},
		b, k;

	while ( element ) {

		b = $.data( element, dataPropertyName );

		for (  k in b ) {
			if ( b[ k ] ) {
				flags[ k ] = flags.hasVirtualBinding = true;
			}
		}
		element = element.parentNode;
	}
	return flags;
}

function getClosestElementWithVirtualBinding( element, eventType ) {
	var b;
	while ( element ) {

		b = $.data( element, dataPropertyName );

		if ( b && ( !eventType || b[ eventType ] ) ) {
			return element;
		}
		element = element.parentNode;
	}
	return null;
}

function enableTouchBindings() {
	blockTouchTriggers = false;
}

function disableTouchBindings() {
	blockTouchTriggers = true;
}

function enableMouseBindings() {
	lastTouchID = 0;
	clickBlockList.length = 0;
	blockMouseTriggers = false;

	// When mouse bindings are enabled, our
	// touch bindings are disabled.
	disableTouchBindings();
}

function disableMouseBindings() {
	// When mouse bindings are disabled, our
	// touch bindings are enabled.
	enableTouchBindings();
}

function startResetTimer() {
	clearResetTimer();
	resetTimerID = setTimeout( function() {
		resetTimerID = 0;
		enableMouseBindings();
	}, $.vmouse.resetTimerDuration );
}

function clearResetTimer() {
	if ( resetTimerID ) {
		clearTimeout( resetTimerID );
		resetTimerID = 0;
	}
}

function triggerVirtualEvent( eventType, event, flags ) {
	var ve;

	if ( ( flags && flags[ eventType ] ) ||
				( !flags && getClosestElementWithVirtualBinding( event.target, eventType ) ) ) {

		ve = createVirtualEvent( event, eventType );

		$( event.target).trigger( ve );
	}

	return ve;
}

function mouseEventCallback( event ) {
	var touchID = $.data( event.target, touchTargetPropertyName );

	if ( !blockMouseTriggers && ( !lastTouchID || lastTouchID !== touchID ) ) {
		var ve = triggerVirtualEvent( "v" + event.type, event );
		if ( ve ) {
			if ( ve.isDefaultPrevented() ) {
				event.preventDefault();
			}
			if ( ve.isPropagationStopped() ) {
				event.stopPropagation();
			}
			if ( ve.isImmediatePropagationStopped() ) {
				event.stopImmediatePropagation();
			}
		}
	}
}

function handleTouchStart( event ) {

	var touches = getNativeEvent( event ).touches,
		target, flags;

	if ( touches && touches.length === 1 ) {

		target = event.target;
		flags = getVirtualBindingFlags( target );

		if ( flags.hasVirtualBinding ) {

			lastTouchID = nextTouchID++;
			$.data( target, touchTargetPropertyName, lastTouchID );

			clearResetTimer();

			disableMouseBindings();
			didScroll = false;

			var t = getNativeEvent( event ).touches[ 0 ];
			startX = t.pageX;
			startY = t.pageY;

			triggerVirtualEvent( "vmouseover", event, flags );
			triggerVirtualEvent( "vmousedown", event, flags );
		}
	}
}

function handleScroll( event ) {
	if ( blockTouchTriggers ) {
		return;
	}

	if ( !didScroll ) {
		triggerVirtualEvent( "vmousecancel", event, getVirtualBindingFlags( event.target ) );
	}

	didScroll = true;
	startResetTimer();
}

function handleTouchMove( event ) {
	if ( blockTouchTriggers ) {
		return;
	}

	var t = getNativeEvent( event ).touches[ 0 ],
		didCancel = didScroll,
		moveThreshold = $.vmouse.moveDistanceThreshold,
		flags = getVirtualBindingFlags( event.target );

		didScroll = didScroll ||
			( Math.abs( t.pageX - startX ) > moveThreshold ||
				Math.abs( t.pageY - startY ) > moveThreshold );


	if ( didScroll && !didCancel ) {
		triggerVirtualEvent( "vmousecancel", event, flags );
	}

	triggerVirtualEvent( "vmousemove", event, flags );
	startResetTimer();
}

function handleTouchEnd( event ) {
	if ( blockTouchTriggers ) {
		return;
	}

	disableTouchBindings();

	var flags = getVirtualBindingFlags( event.target ),
		t;
	triggerVirtualEvent( "vmouseup", event, flags );

	if ( !didScroll ) {
		var ve = triggerVirtualEvent( "vclick", event, flags );
		if ( ve && ve.isDefaultPrevented() ) {
			// The target of the mouse events that follow the touchend
			// event don't necessarily match the target used during the
			// touch. This means we need to rely on coordinates for blocking
			// any click that is generated.
			t = getNativeEvent( event ).changedTouches[ 0 ];
			clickBlockList.push({
				touchID: lastTouchID,
				x: t.clientX,
				y: t.clientY
			});

			// Prevent any mouse events that follow from triggering
			// virtual event notifications.
			blockMouseTriggers = true;
		}
	}
	triggerVirtualEvent( "vmouseout", event, flags);
	didScroll = false;

	startResetTimer();
}

function hasVirtualBindings( ele ) {
	var bindings = $.data( ele, dataPropertyName ),
		k;

	if ( bindings ) {
		for ( k in bindings ) {
			if ( bindings[ k ] ) {
				return true;
			}
		}
	}
	return false;
}

function dummyMouseHandler() {}

function getSpecialEventObject( eventType ) {
	var realType = eventType.substr( 1 );

	return {
		setup: function( data, namespace ) {
			// If this is the first virtual mouse binding for this element,
			// add a bindings object to its data.

			if ( !hasVirtualBindings( this ) ) {
				$.data( this, dataPropertyName, {} );
			}

			// If setup is called, we know it is the first binding for this
			// eventType, so initialize the count for the eventType to zero.
			var bindings = $.data( this, dataPropertyName );
			bindings[ eventType ] = true;

			// If this is the first virtual mouse event for this type,
			// register a global handler on the document.

			activeDocHandlers[ eventType ] = ( activeDocHandlers[ eventType ] || 0 ) + 1;

			if ( activeDocHandlers[ eventType ] === 1 ) {
				$document.bind( realType, mouseEventCallback );
			}

			// Some browsers, like Opera Mini, won't dispatch mouse/click events
			// for elements unless they actually have handlers registered on them.
			// To get around this, we register dummy handlers on the elements.

			$( this ).bind( realType, dummyMouseHandler );

			// For now, if event capture is not supported, we rely on mouse handlers.
			if ( eventCaptureSupported ) {
				// If this is the first virtual mouse binding for the document,
				// register our touchstart handler on the document.

				activeDocHandlers[ "touchstart" ] = ( activeDocHandlers[ "touchstart" ] || 0) + 1;

				if ( activeDocHandlers[ "touchstart" ] === 1 ) {
					$document.bind( "touchstart", handleTouchStart )
						.bind( "touchend", handleTouchEnd )

						// On touch platforms, touching the screen and then dragging your finger
						// causes the window content to scroll after some distance threshold is
						// exceeded. On these platforms, a scroll prevents a click event from being
						// dispatched, and on some platforms, even the touchend is suppressed. To
						// mimic the suppression of the click event, we need to watch for a scroll
						// event. Unfortunately, some platforms like iOS don't dispatch scroll
						// events until *AFTER* the user lifts their finger (touchend). This means
						// we need to watch both scroll and touchmove events to figure out whether
						// or not a scroll happenens before the touchend event is fired.

						.bind( "touchmove", handleTouchMove )
						.bind( "scroll", handleScroll );
				}
			}
		},

		teardown: function( data, namespace ) {
			// If this is the last virtual binding for this eventType,
			// remove its global handler from the document.

			--activeDocHandlers[ eventType ];

			if ( !activeDocHandlers[ eventType ] ) {
				$document.unbind( realType, mouseEventCallback );
			}

			if ( eventCaptureSupported ) {
				// If this is the last virtual mouse binding in existence,
				// remove our document touchstart listener.

				--activeDocHandlers[ "touchstart" ];

				if ( !activeDocHandlers[ "touchstart" ] ) {
					$document.unbind( "touchstart", handleTouchStart )
						.unbind( "touchmove", handleTouchMove )
						.unbind( "touchend", handleTouchEnd )
						.unbind( "scroll", handleScroll );
				}
			}

			var $this = $( this ),
				bindings = $.data( this, dataPropertyName );

			// teardown may be called when an element was
			// removed from the DOM. If this is the case,
			// jQuery core may have already stripped the element
			// of any data bindings so we need to check it before
			// using it.
			if ( bindings ) {
				bindings[ eventType ] = false;
			}

			// Unregister the dummy event handler.

			$this.unbind( realType, dummyMouseHandler );

			// If this is the last virtual mouse binding on the
			// element, remove the binding data from the element.

			if ( !hasVirtualBindings( this ) ) {
				$this.removeData( dataPropertyName );
			}
		}
	};
}

// Expose our custom events to the jQuery bind/unbind mechanism.

for ( var i = 0; i < virtualEventNames.length; i++ ) {
	$.event.special[ virtualEventNames[ i ] ] = getSpecialEventObject( virtualEventNames[ i ] );
}

// Add a capture click handler to block clicks.
// Note that we require event capture support for this so if the device
// doesn't support it, we punt for now and rely solely on mouse events.
if ( eventCaptureSupported ) {
	document.addEventListener( "click", function( e ) {
		var cnt = clickBlockList.length,
			target = e.target,
			x, y, ele, i, o, touchID;

		if ( cnt ) {
			x = e.clientX;
			y = e.clientY;
			threshold = $.vmouse.clickDistanceThreshold;

			// The idea here is to run through the clickBlockList to see if
			// the current click event is in the proximity of one of our
			// vclick events that had preventDefault() called on it. If we find
			// one, then we block the click.
			//
			// Why do we have to rely on proximity?
			//
			// Because the target of the touch event that triggered the vclick
			// can be different from the target of the click event synthesized
			// by the browser. The target of a mouse/click event that is syntehsized
			// from a touch event seems to be implementation specific. For example,
			// some browsers will fire mouse/click events for a link that is near
			// a touch event, even though the target of the touchstart/touchend event
			// says the user touched outside the link. Also, it seems that with most
			// browsers, the target of the mouse/click event is not calculated until the
			// time it is dispatched, so if you replace an element that you touched
			// with another element, the target of the mouse/click will be the new
			// element underneath that point.
			//
			// Aside from proximity, we also check to see if the target and any
			// of its ancestors were the ones that blocked a click. This is necessary
			// because of the strange mouse/click target calculation done in the
			// Android 2.1 browser, where if you click on an element, and there is a
			// mouse/click handler on one of its ancestors, the target will be the
			// innermost child of the touched element, even if that child is no where
			// near the point of touch.

			ele = target;

			while ( ele ) {
				for ( i = 0; i < cnt; i++ ) {
					o = clickBlockList[ i ];
					touchID = 0;

					if ( ( ele === target && Math.abs( o.x - x ) < threshold && Math.abs( o.y - y ) < threshold ) ||
								$.data( ele, touchTargetPropertyName ) === o.touchID ) {
						// XXX: We may want to consider removing matches from the block list
						//      instead of waiting for the reset timer to fire.
						e.preventDefault();
						e.stopPropagation();
						return;
					}
				}
				ele = ele.parentNode;
			}
		}
	}, true);
}
})( jQuery, window, document );

	(function( $, undefined ) {
		var support = {
			touch: "ontouchend" in document
		};

		$.mobile = $.mobile || {};
		$.mobile.support = $.mobile.support || {};
		$.extend( $.support, support );
		$.extend( $.mobile.support, support );
	}( jQuery ));


(function( $, window, undefined ) {
	// add new event shortcuts
	$.each( ( "touchstart touchmove touchend " +
		"tap taphold " +
		"swipe swipeleft swiperight " +
		"scrollstart scrollstop" ).split( " " ), function( i, name ) {

		$.fn[ name ] = function( fn ) {
			return fn ? this.bind( name, fn ) : this.trigger( name );
		};

		// jQuery < 1.8
		if ( $.attrFn ) {
			$.attrFn[ name ] = true;
		}
	});

	var supportTouch = $.mobile.support.touch,
		scrollEvent = "touchmove scroll",
		touchStartEvent = supportTouch ? "touchstart" : "mousedown",
		touchStopEvent = supportTouch ? "touchend" : "mouseup",
		touchMoveEvent = supportTouch ? "touchmove" : "mousemove";

	function triggerCustomEvent( obj, eventType, event ) {
		var originalType = event.type;
		event.type = eventType;
		$.event.handle.call( obj, event );
		event.type = originalType;
	}

	// also handles scrollstop
	$.event.special.scrollstart = {

		enabled: true,

		setup: function() {

			var thisObject = this,
				$this = $( thisObject ),
				scrolling,
				timer;

			function trigger( event, state ) {
				scrolling = state;
				triggerCustomEvent( thisObject, scrolling ? "scrollstart" : "scrollstop", event );
			}

			// iPhone triggers scroll after a small delay; use touchmove instead
			$this.bind( scrollEvent, function( event ) {

				if ( !$.event.special.scrollstart.enabled ) {
					return;
				}

				if ( !scrolling ) {
					trigger( event, true );
				}

				clearTimeout( timer );
				timer = setTimeout( function() {
					trigger( event, false );
				}, 50 );
			});
		}
	};

	// also handles taphold
	$.event.special.tap = {
		tapholdThreshold: 750,

		setup: function() {
			var thisObject = this,
				$this = $( thisObject );

			$this.bind( "vmousedown", function( event ) {

				if ( event.which && event.which !== 1 ) {
					return false;
				}

				var origTarget = event.target,
					origEvent = event.originalEvent,
					timer;

				function clearTapTimer() {
					clearTimeout( timer );
				}

				function clearTapHandlers() {
					clearTapTimer();

					$this.unbind( "vclick", clickHandler )
						.unbind( "vmouseup", clearTapTimer );
					$( document ).unbind( "vmousecancel", clearTapHandlers );
				}

				function clickHandler( event ) {
					clearTapHandlers();

					// ONLY trigger a 'tap' event if the start target is
					// the same as the stop target.
					if ( origTarget === event.target ) {
						triggerCustomEvent( thisObject, "tap", event );
					}
				}

				$this.bind( "vmouseup", clearTapTimer )
					.bind( "vclick", clickHandler );
				$( document ).bind( "vmousecancel", clearTapHandlers );

				timer = setTimeout( function() {
					triggerCustomEvent( thisObject, "taphold", $.Event( "taphold", { target: origTarget } ) );
				}, $.event.special.tap.tapholdThreshold );
			});
		}
	};

	// also handles swipeleft, swiperight
	$.event.special.swipe = {
		scrollSupressionThreshold: 30, // More than this horizontal displacement, and we will suppress scrolling.

		durationThreshold: 1000, // More time than this, and it isn't a swipe.

		horizontalDistanceThreshold: 30,  // Swipe horizontal displacement must be more than this.

		verticalDistanceThreshold: 75,  // Swipe vertical displacement must be less than this.

		setup: function() {
			var thisObject = this,
				$this = $( thisObject );

			$this.bind( touchStartEvent, function( event ) {
				var data = event.originalEvent.touches ?
						event.originalEvent.touches[ 0 ] : event,
					start = {
						time: ( new Date() ).getTime(),
						coords: [ data.pageX, data.pageY ],
						origin: $( event.target )
					},
					stop;

				function moveHandler( event ) {

					if ( !start ) {
						return;
					}

					var data = event.originalEvent.touches ?
						event.originalEvent.touches[ 0 ] : event;

					stop = {
						time: ( new Date() ).getTime(),
						coords: [ data.pageX, data.pageY ]
					};

					// prevent scrolling
					if ( Math.abs( start.coords[ 0 ] - stop.coords[ 0 ] ) > $.event.special.swipe.scrollSupressionThreshold ) {
						event.preventDefault();
					}
				}

				$this.bind( touchMoveEvent, moveHandler )
					.one( touchStopEvent, function( event ) {
						$this.unbind( touchMoveEvent, moveHandler );

						if ( start && stop ) {
							if ( stop.time - start.time < $.event.special.swipe.durationThreshold &&
								Math.abs( start.coords[ 0 ] - stop.coords[ 0 ] ) > $.event.special.swipe.horizontalDistanceThreshold &&
								Math.abs( start.coords[ 1 ] - stop.coords[ 1 ] ) < $.event.special.swipe.verticalDistanceThreshold ) {

								start.origin.trigger( "swipe" )
									.trigger( start.coords[0] > stop.coords[ 0 ] ? "swipeleft" : "swiperight" );
							}
						}
						start = stop = undefined;
					});
			});
		}
	};
	$.each({
		scrollstop: "scrollstart",
		taphold: "tap",
		swipeleft: "swipe",
		swiperight: "swipe"
	}, function( event, sourceEvent ) {

		$.event.special[ event ] = {
			setup: function() {
				$( this ).bind( sourceEvent, $.noop );
			}
		};
	});

})( jQuery, this );

	(function( $, undefined ) {
		$.extend( $.support, {
			orientation: "orientation" in window && "onorientationchange" in window
		});
	}( jQuery ));


	// throttled resize event
	(function( $ ) {
		$.event.special.throttledresize = {
			setup: function() {
				$( this ).bind( "resize", handler );
			},
			teardown: function() {
				$( this ).unbind( "resize", handler );
			}
		};

		var throttle = 250,
			handler = function() {
				curr = ( new Date() ).getTime();
				diff = curr - lastCall;

				if ( diff >= throttle ) {

					lastCall = curr;
					$( this ).trigger( "throttledresize" );

				} else {

					if ( heldCall ) {
						clearTimeout( heldCall );
					}

					// Promise a held call will still execute
					heldCall = setTimeout( handler, throttle - diff );
				}
			},
			lastCall = 0,
			heldCall,
			curr,
			diff;
	})( jQuery );

(function( $, window ) {
	var win = $( window ),
		event_name = "orientationchange",
		special_event,
		get_orientation,
		last_orientation,
		initial_orientation_is_landscape,
		initial_orientation_is_default,
		portrait_map = { "0": true, "180": true };

	// It seems that some device/browser vendors use window.orientation values 0 and 180 to
	// denote the "default" orientation. For iOS devices, and most other smart-phones tested,
	// the default orientation is always "portrait", but in some Android and RIM based tablets,
	// the default orientation is "landscape". The following code attempts to use the window
	// dimensions to figure out what the current orientation is, and then makes adjustments
	// to the to the portrait_map if necessary, so that we can properly decode the
	// window.orientation value whenever get_orientation() is called.
	//
	// Note that we used to use a media query to figure out what the orientation the browser
	// thinks it is in:
	//
	//     initial_orientation_is_landscape = $.mobile.media("all and (orientation: landscape)");
	//
	// but there was an iPhone/iPod Touch bug beginning with iOS 4.2, up through iOS 5.1,
	// where the browser *ALWAYS* applied the landscape media query. This bug does not
	// happen on iPad.

	if ( $.support.orientation ) {

		// Check the window width and height to figure out what the current orientation
		// of the device is at this moment. Note that we've initialized the portrait map
		// values to 0 and 180, *AND* we purposely check for landscape so that if we guess
		// wrong, , we default to the assumption that portrait is the default orientation.
		// We use a threshold check below because on some platforms like iOS, the iPhone
		// form-factor can report a larger width than height if the user turns on the
		// developer console. The actual threshold value is somewhat arbitrary, we just
		// need to make sure it is large enough to exclude the developer console case.

		var ww = window.innerWidth || $( window ).width(),
			wh = window.innerHeight || $( window ).height(),
			landscape_threshold = 50;

		initial_orientation_is_landscape = ww > wh && ( ww - wh ) > landscape_threshold;


		// Now check to see if the current window.orientation is 0 or 180.
		initial_orientation_is_default = portrait_map[ window.orientation ];

		// If the initial orientation is landscape, but window.orientation reports 0 or 180, *OR*
		// if the initial orientation is portrait, but window.orientation reports 90 or -90, we
		// need to flip our portrait_map values because landscape is the default orientation for
		// this device/browser.
		if ( ( initial_orientation_is_landscape && initial_orientation_is_default ) || ( !initial_orientation_is_landscape && !initial_orientation_is_default ) ) {
			portrait_map = { "-90": true, "90": true };
		}
	}

	$.event.special.orientationchange = $.extend( {}, $.event.special.orientationchange, {
		setup: function() {
			// If the event is supported natively, return false so that jQuery
			// will bind to the event using DOM methods.
			if ( $.support.orientation && !$.event.special.orientationchange.disabled ) {
				return false;
			}

			// Get the current orientation to avoid initial double-triggering.
			last_orientation = get_orientation();

			// Because the orientationchange event doesn't exist, simulate the
			// event by testing window dimensions on resize.
			win.bind( "throttledresize", handler );
		},
		teardown: function() {
			// If the event is not supported natively, return false so that
			// jQuery will unbind the event using DOM methods.
			if ( $.support.orientation && !$.event.special.orientationchange.disabled ) {
				return false;
			}

			// Because the orientationchange event doesn't exist, unbind the
			// resize event handler.
			win.unbind( "throttledresize", handler );
		},
		add: function( handleObj ) {
			// Save a reference to the bound event handler.
			var old_handler = handleObj.handler;


			handleObj.handler = function( event ) {
				// Modify event object, adding the .orientation property.
				event.orientation = get_orientation();

				// Call the originally-bound event handler and return its result.
				return old_handler.apply( this, arguments );
			};
		}
	});

	// If the event is not supported natively, this handler will be bound to
	// the window resize event to simulate the orientationchange event.
	function handler() {
		// Get the current orientation.
		var orientation = get_orientation();

		if ( orientation !== last_orientation ) {
			// The orientation has changed, so trigger the orientationchange event.
			last_orientation = orientation;
			win.trigger( event_name );
		}
	}

	// Get the current page orientation. This method is exposed publicly, should it
	// be needed, as jQuery.event.special.orientationchange.orientation()
	$.event.special.orientationchange.orientation = get_orientation = function() {
		var isPortrait = true, elem = document.documentElement;

		// prefer window orientation to the calculation based on screensize as
		// the actual screen resize takes place before or after the orientation change event
		// has been fired depending on implementation (eg android 2.3 is before, iphone after).
		// More testing is required to determine if a more reliable method of determining the new screensize
		// is possible when orientationchange is fired. (eg, use media queries + element + opacity)
		if ( $.support.orientation ) {
			// if the window orientation registers as 0 or 180 degrees report
			// portrait, otherwise landscape
			isPortrait = portrait_map[ window.orientation ];
		} else {
			isPortrait = elem && elem.clientWidth / elem.clientHeight < 1.1;
		}

		return isPortrait ? "portrait" : "landscape";
	};

	$.fn[ event_name ] = function( fn ) {
		return fn ? this.bind( event_name, fn ) : this.trigger( event_name );
	};

	// jQuery < 1.8
	if ( $.attrFn ) {
		$.attrFn[ event_name ] = true;
	}

}( jQuery, this ));


(function( $, undefined ) {

var $window = $( window ),
	$html = $( "html" );

/* $.mobile.media method: pass a CSS media type or query and get a bool return
	note: this feature relies on actual media query support for media queries, though types will work most anywhere
	examples:
		$.mobile.media('screen') // tests for screen media type
		$.mobile.media('screen and (min-width: 480px)') // tests for screen media type with window width > 480px
		$.mobile.media('@media screen and (-webkit-min-device-pixel-ratio: 2)') // tests for webkit 2x pixel ratio (iPhone 4)
*/
$.mobile.media = (function() {
	// TODO: use window.matchMedia once at least one UA implements it
	var cache = {},
		testDiv = $( "<div id='jquery-mediatest'></div>" ),
		fakeBody = $( "<body>" ).append( testDiv );

	return function( query ) {
		if ( !( query in cache ) ) {
			var styleBlock = document.createElement( "style" ),
				cssrule = "@media " + query + " { #jquery-mediatest { position:absolute; } }";

			//must set type for IE!
			styleBlock.type = "text/css";

			if ( styleBlock.styleSheet ) {
				styleBlock.styleSheet.cssText = cssrule;
			} else {
				styleBlock.appendChild( document.createTextNode(cssrule) );
			}

			$html.prepend( fakeBody ).prepend( styleBlock );
			cache[ query ] = testDiv.css( "position" ) === "absolute";
			fakeBody.add( styleBlock ).remove();
		}
		return cache[ query ];
	};
})();

})(jQuery);

(function( $, undefined ) {

// thx Modernizr
function propExists( prop ) {
	var uc_prop = prop.charAt( 0 ).toUpperCase() + prop.substr( 1 ),
		props = ( prop + " " + vendors.join( uc_prop + " " ) + uc_prop ).split( " " );

	for ( var v in props ) {
		if ( fbCSS[ props[ v ] ] !== undefined ) {
			return true;
		}
	}
}

var fakeBody = $( "<body>" ).prependTo( "html" ),
	fbCSS = fakeBody[ 0 ].style,
	vendors = [ "Webkit", "Moz", "O" ],
	webos = "palmGetResource" in window, //only used to rule out scrollTop
	opera = window.opera,
	operamini = window.operamini && ({}).toString.call( window.operamini ) === "[object OperaMini]",
	bb = window.blackberry && !propExists( "-webkit-transform" ); //only used to rule out box shadow, as it's filled opaque on BB 5 and lower


function validStyle( prop, value, check_vend ) {
	var div = document.createElement( 'div' ),
		uc = function( txt ) {
			return txt.charAt( 0 ).toUpperCase() + txt.substr( 1 );
		},
		vend_pref = function( vend ) {
			return  "-" + vend.charAt( 0 ).toLowerCase() + vend.substr( 1 ) + "-";
		},
		check_style = function( vend ) {
			var vend_prop = vend_pref( vend ) + prop + ": " + value + ";",
				uc_vend = uc( vend ),
				propStyle = uc_vend + uc( prop );

			div.setAttribute( "style", vend_prop );

			if ( !!div.style[ propStyle ] ) {
				ret = true;
			}
		},
		check_vends = check_vend ? [ check_vend ] : vendors,
		ret;

	for( var i = 0; i < check_vends.length; i++ ) {
		check_style( check_vends[i] );
	}
	return !!ret;
}

// Thanks to Modernizr src for this test idea. `perspective` check is limited to Moz to prevent a false positive for 3D transforms on Android.
function transform3dTest() {
	var prop = "transform-3d";
	return validStyle( 'perspective', '10px', 'moz' ) || $.mobile.media( "(-" + vendors.join( "-" + prop + "),(-" ) + "-" + prop + "),(" + prop + ")" );
}

// Test for dynamic-updating base tag support ( allows us to avoid href,src attr rewriting )
function baseTagTest() {
	var fauxBase = location.protocol + "//" + location.host + location.pathname + "ui-dir/",
		base = $( "head base" ),
		fauxEle = null,
		href = "",
		link, rebase;

	if ( !base.length ) {
		base = fauxEle = $( "<base>", { "href": fauxBase }).appendTo( "head" );
	} else {
		href = base.attr( "href" );
	}

	link = $( "<a href='testurl' />" ).prependTo( fakeBody );
	rebase = link[ 0 ].href;
	base[ 0 ].href = href || location.pathname;

	if ( fauxEle ) {
		fauxEle.remove();
	}
	return rebase.indexOf( fauxBase ) === 0;
}

// Thanks Modernizr
function cssPointerEventsTest() {
	var element = document.createElement( 'x' ),
		documentElement = document.documentElement,
		getComputedStyle = window.getComputedStyle,
		supports;

	if ( !( 'pointerEvents' in element.style ) ) {
		return false;
	}

	element.style.pointerEvents = 'auto';
	element.style.pointerEvents = 'x';
	documentElement.appendChild( element );
	supports = getComputedStyle &&
	getComputedStyle( element, '' ).pointerEvents === 'auto';
	documentElement.removeChild( element );
	return !!supports;
}

function boundingRect() {
	var div = document.createElement( "div" );
	return typeof div.getBoundingClientRect !== "undefined";
}

// non-UA-based IE version check by James Padolsey, modified by jdalton - from http://gist.github.com/527683
// allows for inclusion of IE 6+, including Windows Mobile 7
$.extend( $.mobile, { browser: {} } );
$.mobile.browser.ie = (function() {
	var v = 3,
		div = document.createElement( "div" ),
		a = div.all || [];

	do {
		div.innerHTML = "<!--[if gt IE " + ( ++v ) + "]><br><![endif]-->";
	} while( a[0] );

	return v > 4 ? v : !v;
})();


$.extend( $.support, {
	cssTransitions: "WebKitTransitionEvent" in window || validStyle( 'transition', 'height 100ms linear' ) && !opera,
	pushState: "pushState" in history && "replaceState" in history,
	mediaquery: $.mobile.media( "only all" ),
	cssPseudoElement: !!propExists( "content" ),
	touchOverflow: !!propExists( "overflowScrolling" ),
	cssTransform3d: transform3dTest(),
	boxShadow: !!propExists( "boxShadow" ) && !bb,
	scrollTop: ( "pageXOffset" in window || "scrollTop" in document.documentElement || "scrollTop" in fakeBody[ 0 ] ) && !webos && !operamini,
	dynamicBaseTag: baseTagTest(),
	cssPointerEvents: cssPointerEventsTest(),
	boundingRect: boundingRect()
});

fakeBody.remove();


// $.mobile.ajaxBlacklist is used to override ajaxEnabled on platforms that have known conflicts with hash history updates (BB5, Symbian)
// or that generally work better browsing in regular http for full page refreshes (Opera Mini)
// Note: This detection below is used as a last resort.
// We recommend only using these detection methods when all other more reliable/forward-looking approaches are not possible
var nokiaLTE7_3 = (function() {

	var ua = window.navigator.userAgent;

	//The following is an attempt to match Nokia browsers that are running Symbian/s60, with webkit, version 7.3 or older
	return ua.indexOf( "Nokia" ) > -1 &&
			( ua.indexOf( "Symbian/3" ) > -1 || ua.indexOf( "Series60/5" ) > -1 ) &&
			ua.indexOf( "AppleWebKit" ) > -1 &&
			ua.match( /(BrowserNG|NokiaBrowser)\/7\.[0-3]/ );
})();

// Support conditions that must be met in order to proceed
// default enhanced qualifications are media query support OR IE 7+

$.mobile.gradeA = function() {
	return ( $.support.mediaquery || $.mobile.browser.ie && $.mobile.browser.ie >= 7 ) && ( $.support.boundingRect || $.fn.jquery.match(/1\.[0-7+]\.[0-9+]?/) !== null );
};

$.mobile.ajaxBlacklist =
			// BlackBerry browsers, pre-webkit
			window.blackberry && !window.WebKitPoint ||
			// Opera Mini
			operamini ||
			// Symbian webkits pre 7.3
			nokiaLTE7_3;

// Lastly, this workaround is the only way we've found so far to get pre 7.3 Symbian webkit devices
// to render the stylesheets when they're referenced before this script, as we'd recommend doing.
// This simply reappends the CSS in place, which for some reason makes it apply
if ( nokiaLTE7_3 ) {
	$(function() {
		$( "head link[rel='stylesheet']" ).attr( "rel", "alternate stylesheet" ).attr( "rel", "stylesheet" );
	});
}

// For ruling out shadows via css
if ( !$.support.boxShadow ) {
	$( "html" ).addClass( "ui-mobile-nosupport-boxshadow" );
}

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.page", $.mobile.widget, {
	options: {
		theme: "c",
		domCache: false,
		keepNativeDefault: ":jqmData(role='none'), :jqmData(role='nojs')"
	},

	_create: function() {
		
		var self = this;
		
		// if false is returned by the callbacks do not create the page
		if ( self._trigger( "beforecreate" ) === false ) {
			return false;
		}

		self.element
			.attr( "tabindex", "0" )
			.addClass( "ui-page ui-body-" + self.options.theme )
			.bind( "pagebeforehide", function() {
				self.removeContainerBackground();
			} )
			.bind( "pagebeforeshow", function() {
				self.setContainerBackground();
			} );

	},
	
	removeContainerBackground: function() {
		$.mobile.pageContainer.removeClass( "ui-overlay-" + $.mobile.getInheritedTheme( this.element.parent() ) );
	},
	
	// set the page container background to the page theme
	setContainerBackground: function( theme ) {
		if ( this.options.theme ) {
			$.mobile.pageContainer.addClass( "ui-overlay-" + ( theme || this.options.theme ) );
		}
	},

	keepNativeSelector: function() {
		var options = this.options,
			keepNativeDefined = options.keepNative && $.trim( options.keepNative );

		if ( keepNativeDefined && options.keepNative !== options.keepNativeDefault ) {
			return [options.keepNative, options.keepNativeDefault].join( ", " );
		}

		return options.keepNativeDefault;
	}
});
})( jQuery );

// Script: jQuery hashchange event
// 
// *Version: 1.3, Last updated: 7/21/2010*
// 
// Project Home - http://benalman.com/projects/jquery-hashchange-plugin/
// GitHub       - http://github.com/cowboy/jquery-hashchange/
// Source       - http://github.com/cowboy/jquery-hashchange/raw/master/jquery.ba-hashchange.js
// (Minified)   - http://github.com/cowboy/jquery-hashchange/raw/master/jquery.ba-hashchange.min.js (0.8kb gzipped)
// 
// About: License
// 
// Copyright (c) 2010 "Cowboy" Ben Alman,
// Dual licensed under the MIT and GPL licenses.
// http://benalman.com/about/license/
// 
// About: Examples
// 
// These working examples, complete with fully commented code, illustrate a few
// ways in which this plugin can be used.
// 
// hashchange event - http://benalman.com/code/projects/jquery-hashchange/examples/hashchange/
// document.domain - http://benalman.com/code/projects/jquery-hashchange/examples/document_domain/
// 
// About: Support and Testing
// 
// Information about what version or versions of jQuery this plugin has been
// tested with, what browsers it has been tested in, and where the unit tests
// reside (so you can test it yourself).
// 
// jQuery Versions - 1.2.6, 1.3.2, 1.4.1, 1.4.2
// Browsers Tested - Internet Explorer 6-8, Firefox 2-4, Chrome 5-6, Safari 3.2-5,
//                   Opera 9.6-10.60, iPhone 3.1, Android 1.6-2.2, BlackBerry 4.6-5.
// Unit Tests      - http://benalman.com/code/projects/jquery-hashchange/unit/
// 
// About: Known issues
// 
// While this jQuery hashchange event implementation is quite stable and
// robust, there are a few unfortunate browser bugs surrounding expected
// hashchange event-based behaviors, independent of any JavaScript
// window.onhashchange abstraction. See the following examples for more
// information:
// 
// Chrome: Back Button - http://benalman.com/code/projects/jquery-hashchange/examples/bug-chrome-back-button/
// Firefox: Remote XMLHttpRequest - http://benalman.com/code/projects/jquery-hashchange/examples/bug-firefox-remote-xhr/
// WebKit: Back Button in an Iframe - http://benalman.com/code/projects/jquery-hashchange/examples/bug-webkit-hash-iframe/
// Safari: Back Button from a different domain - http://benalman.com/code/projects/jquery-hashchange/examples/bug-safari-back-from-diff-domain/
// 
// Also note that should a browser natively support the window.onhashchange 
// event, but not report that it does, the fallback polling loop will be used.
// 
// About: Release History
// 
// 1.3   - (7/21/2010) Reorganized IE6/7 Iframe code to make it more
//         "removable" for mobile-only development. Added IE6/7 document.title
//         support. Attempted to make Iframe as hidden as possible by using
//         techniques from http://www.paciellogroup.com/blog/?p=604. Added 
//         support for the "shortcut" format $(window).hashchange( fn ) and
//         $(window).hashchange() like jQuery provides for built-in events.
//         Renamed jQuery.hashchangeDelay to <jQuery.fn.hashchange.delay> and
//         lowered its default value to 50. Added <jQuery.fn.hashchange.domain>
//         and <jQuery.fn.hashchange.src> properties plus document-domain.html
//         file to address access denied issues when setting document.domain in
//         IE6/7.
// 1.2   - (2/11/2010) Fixed a bug where coming back to a page using this plugin
//         from a page on another domain would cause an error in Safari 4. Also,
//         IE6/7 Iframe is now inserted after the body (this actually works),
//         which prevents the page from scrolling when the event is first bound.
//         Event can also now be bound before DOM ready, but it won't be usable
//         before then in IE6/7.
// 1.1   - (1/21/2010) Incorporated document.documentMode test to fix IE8 bug
//         where browser version is incorrectly reported as 8.0, despite
//         inclusion of the X-UA-Compatible IE=EmulateIE7 meta tag.
// 1.0   - (1/9/2010) Initial Release. Broke out the jQuery BBQ event.special
//         window.onhashchange functionality into a separate plugin for users
//         who want just the basic event & back button support, without all the
//         extra awesomeness that BBQ provides. This plugin will be included as
//         part of jQuery BBQ, but also be available separately.

(function( $, window, undefined ) {
  // Reused string.
  var str_hashchange = 'hashchange',
    
    // Method / object references.
    doc = document,
    fake_onhashchange,
    special = $.event.special,
    
    // Does the browser support window.onhashchange? Note that IE8 running in
    // IE7 compatibility mode reports true for 'onhashchange' in window, even
    // though the event isn't supported, so also test document.documentMode.
    doc_mode = doc.documentMode,
    supports_onhashchange = 'on' + str_hashchange in window && ( doc_mode === undefined || doc_mode > 7 );
  
  // Get location.hash (or what you'd expect location.hash to be) sans any
  // leading #. Thanks for making this necessary, Firefox!
  function get_fragment( url ) {
    url = url || location.href;
    return '#' + url.replace( /^[^#]*#?(.*)$/, '$1' );
  };
  
  // Method: jQuery.fn.hashchange
  // 
  // Bind a handler to the window.onhashchange event or trigger all bound
  // window.onhashchange event handlers. This behavior is consistent with
  // jQuery's built-in event handlers.
  // 
  // Usage:
  // 
  // > jQuery(window).hashchange( [ handler ] );
  // 
  // Arguments:
  // 
  //  handler - (Function) Optional handler to be bound to the hashchange
  //    event. This is a "shortcut" for the more verbose form:
  //    jQuery(window).bind( 'hashchange', handler ). If handler is omitted,
  //    all bound window.onhashchange event handlers will be triggered. This
  //    is a shortcut for the more verbose
  //    jQuery(window).trigger( 'hashchange' ). These forms are described in
  //    the <hashchange event> section.
  // 
  // Returns:
  // 
  //  (jQuery) The initial jQuery collection of elements.
  
  // Allow the "shortcut" format $(elem).hashchange( fn ) for binding and
  // $(elem).hashchange() for triggering, like jQuery does for built-in events.
  $.fn[ str_hashchange ] = function( fn ) {
    return fn ? this.bind( str_hashchange, fn ) : this.trigger( str_hashchange );
  };
  
  // Property: jQuery.fn.hashchange.delay
  // 
  // The numeric interval (in milliseconds) at which the <hashchange event>
  // polling loop executes. Defaults to 50.
  
  // Property: jQuery.fn.hashchange.domain
  // 
  // If you're setting document.domain in your JavaScript, and you want hash
  // history to work in IE6/7, not only must this property be set, but you must
  // also set document.domain BEFORE jQuery is loaded into the page. This
  // property is only applicable if you are supporting IE6/7 (or IE8 operating
  // in "IE7 compatibility" mode).
  // 
  // In addition, the <jQuery.fn.hashchange.src> property must be set to the
  // path of the included "document-domain.html" file, which can be renamed or
  // modified if necessary (note that the document.domain specified must be the
  // same in both your main JavaScript as well as in this file).
  // 
  // Usage:
  // 
  // jQuery.fn.hashchange.domain = document.domain;
  
  // Property: jQuery.fn.hashchange.src
  // 
  // If, for some reason, you need to specify an Iframe src file (for example,
  // when setting document.domain as in <jQuery.fn.hashchange.domain>), you can
  // do so using this property. Note that when using this property, history
  // won't be recorded in IE6/7 until the Iframe src file loads. This property
  // is only applicable if you are supporting IE6/7 (or IE8 operating in "IE7
  // compatibility" mode).
  // 
  // Usage:
  // 
  // jQuery.fn.hashchange.src = 'path/to/file.html';
  
  $.fn[ str_hashchange ].delay = 50;
  /*
  $.fn[ str_hashchange ].domain = null;
  $.fn[ str_hashchange ].src = null;
  */
  
  // Event: hashchange event
  // 
  // Fired when location.hash changes. In browsers that support it, the native
  // HTML5 window.onhashchange event is used, otherwise a polling loop is
  // initialized, running every <jQuery.fn.hashchange.delay> milliseconds to
  // see if the hash has changed. In IE6/7 (and IE8 operating in "IE7
  // compatibility" mode), a hidden Iframe is created to allow the back button
  // and hash-based history to work.
  // 
  // Usage as described in <jQuery.fn.hashchange>:
  // 
  // > // Bind an event handler.
  // > jQuery(window).hashchange( function(e) {
  // >   var hash = location.hash;
  // >   ...
  // > });
  // > 
  // > // Manually trigger the event handler.
  // > jQuery(window).hashchange();
  // 
  // A more verbose usage that allows for event namespacing:
  // 
  // > // Bind an event handler.
  // > jQuery(window).bind( 'hashchange', function(e) {
  // >   var hash = location.hash;
  // >   ...
  // > });
  // > 
  // > // Manually trigger the event handler.
  // > jQuery(window).trigger( 'hashchange' );
  // 
  // Additional Notes:
  // 
  // * The polling loop and Iframe are not created until at least one handler
  //   is actually bound to the 'hashchange' event.
  // * If you need the bound handler(s) to execute immediately, in cases where
  //   a location.hash exists on page load, via bookmark or page refresh for
  //   example, use jQuery(window).hashchange() or the more verbose 
  //   jQuery(window).trigger( 'hashchange' ).
  // * The event can be bound before DOM ready, but since it won't be usable
  //   before then in IE6/7 (due to the necessary Iframe), recommended usage is
  //   to bind it inside a DOM ready handler.
  
  // Override existing $.event.special.hashchange methods (allowing this plugin
  // to be defined after jQuery BBQ in BBQ's source code).
  special[ str_hashchange ] = $.extend( special[ str_hashchange ], {
    
    // Called only when the first 'hashchange' event is bound to window.
    setup: function() {
      // If window.onhashchange is supported natively, there's nothing to do..
      if ( supports_onhashchange ) { return false; }
      
      // Otherwise, we need to create our own. And we don't want to call this
      // until the user binds to the event, just in case they never do, since it
      // will create a polling loop and possibly even a hidden Iframe.
      $( fake_onhashchange.start );
    },
    
    // Called only when the last 'hashchange' event is unbound from window.
    teardown: function() {
      // If window.onhashchange is supported natively, there's nothing to do..
      if ( supports_onhashchange ) { return false; }
      
      // Otherwise, we need to stop ours (if possible).
      $( fake_onhashchange.stop );
    }
    
  });
  
  // fake_onhashchange does all the work of triggering the window.onhashchange
  // event for browsers that don't natively support it, including creating a
  // polling loop to watch for hash changes and in IE 6/7 creating a hidden
  // Iframe to enable back and forward.
  fake_onhashchange = (function() {
    var self = {},
      timeout_id,
      
      // Remember the initial hash so it doesn't get triggered immediately.
      last_hash = get_fragment(),
      
      fn_retval = function( val ) { return val; },
      history_set = fn_retval,
      history_get = fn_retval;
    
    // Start the polling loop.
    self.start = function() {
      timeout_id || poll();
    };
    
    // Stop the polling loop.
    self.stop = function() {
      timeout_id && clearTimeout( timeout_id );
      timeout_id = undefined;
    };
    
    // This polling loop checks every $.fn.hashchange.delay milliseconds to see
    // if location.hash has changed, and triggers the 'hashchange' event on
    // window when necessary.
    function poll() {
      var hash = get_fragment(),
        history_hash = history_get( last_hash );
      
      if ( hash !== last_hash ) {
        history_set( last_hash = hash, history_hash );
        
        $(window).trigger( str_hashchange );
        
      } else if ( history_hash !== last_hash ) {
        location.href = location.href.replace( /#.*/, '' ) + history_hash;
      }
      
      timeout_id = setTimeout( poll, $.fn[ str_hashchange ].delay );
    };
    
    // vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv
    // vvvvvvvvvvvvvvvvvvv REMOVE IF NOT SUPPORTING IE6/7/8 vvvvvvvvvvvvvvvvvvv
    // vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv
    $.browser.msie && !supports_onhashchange && (function() {
      // Not only do IE6/7 need the "magical" Iframe treatment, but so does IE8
      // when running in "IE7 compatibility" mode.
      
      var iframe,
        iframe_src;
      
      // When the event is bound and polling starts in IE 6/7, create a hidden
      // Iframe for history handling.
      self.start = function() {
        if ( !iframe ) {
          iframe_src = $.fn[ str_hashchange ].src;
          iframe_src = iframe_src && iframe_src + get_fragment();
          
          // Create hidden Iframe. Attempt to make Iframe as hidden as possible
          // by using techniques from http://www.paciellogroup.com/blog/?p=604.
          iframe = $('<iframe tabindex="-1" title="empty"/>').hide()
            
            // When Iframe has completely loaded, initialize the history and
            // start polling.
            .one( 'load', function() {
              iframe_src || history_set( get_fragment() );
              poll();
            })
            
            // Load Iframe src if specified, otherwise nothing.
            .attr( 'src', iframe_src || 'javascript:0' )
            
            // Append Iframe after the end of the body to prevent unnecessary
            // initial page scrolling (yes, this works).
            .insertAfter( 'body' )[0].contentWindow;
          
          // Whenever `document.title` changes, update the Iframe's title to
          // prettify the back/next history menu entries. Since IE sometimes
          // errors with "Unspecified error" the very first time this is set
          // (yes, very useful) wrap this with a try/catch block.
          doc.onpropertychange = function() {
            try {
              if ( event.propertyName === 'title' ) {
                iframe.document.title = doc.title;
              }
            } catch(e) {}
          };
          
        }
      };
      
      // Override the "stop" method since an IE6/7 Iframe was created. Even
      // if there are no longer any bound event handlers, the polling loop
      // is still necessary for back/next to work at all!
      self.stop = fn_retval;
      
      // Get history by looking at the hidden Iframe's location.hash.
      history_get = function() {
        return get_fragment( iframe.location.href );
      };
      
      // Set a new history item by opening and then closing the Iframe
      // document, *then* setting its location.hash. If document.domain has
      // been set, update that as well.
      history_set = function( hash, history_hash ) {
        var iframe_doc = iframe.document,
          domain = $.fn[ str_hashchange ].domain;
        
        if ( hash !== history_hash ) {
          // Update Iframe with any initial `document.title` that might be set.
          iframe_doc.title = doc.title;
          
          // Opening the Iframe's document after it has been closed is what
          // actually adds a history entry.
          iframe_doc.open();
          
          // Set document.domain for the Iframe document as well, if necessary.
          domain && iframe_doc.write( '<script>document.domain="' + domain + '"</script>' );
          
          iframe_doc.close();
          
          // Update the Iframe's hash, for great justice.
          iframe.location.hash = hash;
        }
      };
      
    })();
    // ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    // ^^^^^^^^^^^^^^^^^^^ REMOVE IF NOT SUPPORTING IE6/7/8 ^^^^^^^^^^^^^^^^^^^
    // ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    
    return self;
  })();
  
})(jQuery,this);


(function( $, window, undefined ) {

var createHandler = function( sequential ) {

	// Default to sequential
	if ( sequential === undefined ) {
		sequential = true;
	}

	return function( name, reverse, $to, $from ) {

		var deferred = new $.Deferred(),
			reverseClass = reverse ? " reverse" : "",
			active	= $.mobile.urlHistory.getActive(),
			toScroll = active.lastScroll || $.mobile.defaultHomeScroll,
			screenHeight = $.mobile.getScreenHeight(),
			maxTransitionOverride = $.mobile.maxTransitionWidth !== false && $( window ).width() > $.mobile.maxTransitionWidth,
			none = !$.support.cssTransitions || maxTransitionOverride || !name || name === "none" || Math.max( $( window ).scrollTop(), toScroll ) > $.mobile.getMaxScrollForTransition(),
			toPreClass = " ui-page-pre-in",
			toggleViewportClass = function() {
				$.mobile.pageContainer.toggleClass( "ui-mobile-viewport-transitioning viewport-" + name );
			},
			scrollPage = function() {
				// By using scrollTo instead of silentScroll, we can keep things better in order
				// Just to be precautios, disable scrollstart listening like silentScroll would
				$.event.special.scrollstart.enabled = false;

				window.scrollTo( 0, toScroll );

				// reenable scrollstart listening like silentScroll would
				setTimeout( function() {
					$.event.special.scrollstart.enabled = true;
				}, 150 );
			},
			cleanFrom = function() {
				$from
					.removeClass( $.mobile.activePageClass + " out in reverse " + name )
					.height( "" );
			},
			startOut = function() {
				// if it's not sequential, call the doneOut transition to start the TO page animating in simultaneously
				if ( !sequential ) {
					doneOut();
				}
				else {
					$from.animationComplete( doneOut );
				}

				// Set the from page's height and start it transitioning out
				// Note: setting an explicit height helps eliminate tiling in the transitions
				$from
					.height( screenHeight + $( window ).scrollTop() )
					.addClass( name + " out" + reverseClass );
			},

			doneOut = function() {

				if ( $from && sequential ) {
					cleanFrom();
				}

				startIn();
			},

			startIn = function() {

				// Prevent flickering in phonegap container: see comments at #4024 regarding iOS
				$to.css( "z-index", -10 );

				$to.addClass( $.mobile.activePageClass + toPreClass );

				// Send focus to page as it is now display: block
				$.mobile.focusPage( $to );

				// Set to page height
				$to.height( screenHeight + toScroll );

				scrollPage();

				// Restores visibility of the new page: added together with $to.css( "z-index", -10 );
				$to.css( "z-index", "" );

				if ( !none ) {
					$to.animationComplete( doneIn );
				}

				$to
					.removeClass( toPreClass )
					.addClass( name + " in" + reverseClass );

				if ( none ) {
					doneIn();
				}

			},

			doneIn = function() {

				if ( !sequential ) {

					if ( $from ) {
						cleanFrom();
					}
				}

				$to
					.removeClass( "out in reverse " + name )
					.height( "" );

				toggleViewportClass();

				// In some browsers (iOS5), 3D transitions block the ability to scroll to the desired location during transition
				// This ensures we jump to that spot after the fact, if we aren't there already.
				if ( $( window ).scrollTop() !== toScroll ) {
					scrollPage();
				}

				deferred.resolve( name, reverse, $to, $from, true );
			};

		toggleViewportClass();

		if ( $from && !none ) {
			startOut();
		}
		else {
			doneOut();
		}

		return deferred.promise();
	};
};

// generate the handlers from the above
var sequentialHandler = createHandler(),
	simultaneousHandler = createHandler( false ),
	defaultGetMaxScrollForTransition = function() {
		return $.mobile.getScreenHeight() * 3;
	};

// Make our transition handler the public default.
$.mobile.defaultTransitionHandler = sequentialHandler;

//transition handler dictionary for 3rd party transitions
$.mobile.transitionHandlers = {
	"default": $.mobile.defaultTransitionHandler,
	"sequential": sequentialHandler,
	"simultaneous": simultaneousHandler
};

$.mobile.transitionFallbacks = {};

// If transition is defined, check if css 3D transforms are supported, and if not, if a fallback is specified
$.mobile._maybeDegradeTransition = function( transition ) {
		if ( transition && !$.support.cssTransform3d && $.mobile.transitionFallbacks[ transition ] ) {
			transition = $.mobile.transitionFallbacks[ transition ];
		}

		return transition;
};

// Set the getMaxScrollForTransition to default if no implementation was set by user
$.mobile.getMaxScrollForTransition = $.mobile.getMaxScrollForTransition || defaultGetMaxScrollForTransition;
})( jQuery, this );

(function( $, undefined ) {

	//define vars for interal use
	var $window = $( window ),
		$html = $( 'html' ),
		$head = $( 'head' ),

		//url path helpers for use in relative url management
		path = {

			// This scary looking regular expression parses an absolute URL or its relative
			// variants (protocol, site, document, query, and hash), into the various
			// components (protocol, host, path, query, fragment, etc that make up the
			// URL as well as some other commonly used sub-parts. When used with RegExp.exec()
			// or String.match, it parses the URL into a results array that looks like this:
			//
			//     [0]: http://jblas:password@mycompany.com:8080/mail/inbox?msg=1234&type=unread#msg-content
			//     [1]: http://jblas:password@mycompany.com:8080/mail/inbox?msg=1234&type=unread
			//     [2]: http://jblas:password@mycompany.com:8080/mail/inbox
			//     [3]: http://jblas:password@mycompany.com:8080
			//     [4]: http:
			//     [5]: //
			//     [6]: jblas:password@mycompany.com:8080
			//     [7]: jblas:password
			//     [8]: jblas
			//     [9]: password
			//    [10]: mycompany.com:8080
			//    [11]: mycompany.com
			//    [12]: 8080
			//    [13]: /mail/inbox
			//    [14]: /mail/
			//    [15]: inbox
			//    [16]: ?msg=1234&type=unread
			//    [17]: #msg-content
			//
			urlParseRE: /^(((([^:\/#\?]+:)?(?:(\/\/)((?:(([^:@\/#\?]+)(?:\:([^:@\/#\?]+))?)@)?(([^:\/#\?\]\[]+|\[[^\/\]@#?]+\])(?:\:([0-9]+))?))?)?)?((\/?(?:[^\/\?#]+\/+)*)([^\?#]*)))?(\?[^#]+)?)(#.*)?/,

			// Abstraction to address xss (Issue #4787) by removing the authority in
			// browsers that auto	decode it. All references to location.href should be
			// replaced with a call to this method so that it can be dealt with properly here
			getLocation: function( url ) {
				var uri = url ? this.parseUrl( url ) : location,
					hash = this.parseUrl( url || location.href ).hash;

				// mimic the browser with an empty string when the hash is empty
				hash = hash === "#" ? "" : hash;

				// Make sure to parse the url or the location object for the hash because using location.hash
				// is autodecoded in firefox, the rest of the url should be from the object (location unless
				// we're testing) to avoid the inclusion of the authority
				return uri.protocol + "//" + uri.host + uri.pathname + uri.search + hash;
			},

			parseLocation: function() {
				return this.parseUrl( this.getLocation() );
			},

			//Parse a URL into a structure that allows easy access to
			//all of the URL components by name.
			parseUrl: function( url ) {
				// If we're passed an object, we'll assume that it is
				// a parsed url object and just return it back to the caller.
				if ( $.type( url ) === "object" ) {
					return url;
				}

				var matches = path.urlParseRE.exec( url || "" ) || [];

					// Create an object that allows the caller to access the sub-matches
					// by name. Note that IE returns an empty string instead of undefined,
					// like all other browsers do, so we normalize everything so its consistent
					// no matter what browser we're running on.
					return {
						href:         matches[  0 ] || "",
						hrefNoHash:   matches[  1 ] || "",
						hrefNoSearch: matches[  2 ] || "",
						domain:       matches[  3 ] || "",
						protocol:     matches[  4 ] || "",
						doubleSlash:  matches[  5 ] || "",
						authority:    matches[  6 ] || "",
						username:     matches[  8 ] || "",
						password:     matches[  9 ] || "",
						host:         matches[ 10 ] || "",
						hostname:     matches[ 11 ] || "",
						port:         matches[ 12 ] || "",
						pathname:     matches[ 13 ] || "",
						directory:    matches[ 14 ] || "",
						filename:     matches[ 15 ] || "",
						search:       matches[ 16 ] || "",
						hash:         matches[ 17 ] || ""
					};
			},

			//Turn relPath into an asbolute path. absPath is
			//an optional absolute path which describes what
			//relPath is relative to.
			makePathAbsolute: function( relPath, absPath ) {
				if ( relPath && relPath.charAt( 0 ) === "/" ) {
					return relPath;
				}

				relPath = relPath || "";
				absPath = absPath ? absPath.replace( /^\/|(\/[^\/]*|[^\/]+)$/g, "" ) : "";

				var absStack = absPath ? absPath.split( "/" ) : [],
					relStack = relPath.split( "/" );
				for ( var i = 0; i < relStack.length; i++ ) {
					var d = relStack[ i ];
					switch ( d ) {
						case ".":
							break;
						case "..":
							if ( absStack.length ) {
								absStack.pop();
							}
							break;
						default:
							absStack.push( d );
							break;
					}
				}
				return "/" + absStack.join( "/" );
			},

			//Returns true if both urls have the same domain.
			isSameDomain: function( absUrl1, absUrl2 ) {
				return path.parseUrl( absUrl1 ).domain === path.parseUrl( absUrl2 ).domain;
			},

			//Returns true for any relative variant.
			isRelativeUrl: function( url ) {
				// All relative Url variants have one thing in common, no protocol.
				return path.parseUrl( url ).protocol === "";
			},

			//Returns true for an absolute url.
			isAbsoluteUrl: function( url ) {
				return path.parseUrl( url ).protocol !== "";
			},

			//Turn the specified realtive URL into an absolute one. This function
			//can handle all relative variants (protocol, site, document, query, fragment).
			makeUrlAbsolute: function( relUrl, absUrl ) {
				if ( !path.isRelativeUrl( relUrl ) ) {
					return relUrl;
				}

				if ( absUrl === undefined ) {
					absUrl = documentBase;
				}

				var relObj = path.parseUrl( relUrl ),
					absObj = path.parseUrl( absUrl ),
					protocol = relObj.protocol || absObj.protocol,
					doubleSlash = relObj.protocol ? relObj.doubleSlash : ( relObj.doubleSlash || absObj.doubleSlash ),
					authority = relObj.authority || absObj.authority,
					hasPath = relObj.pathname !== "",
					pathname = path.makePathAbsolute( relObj.pathname || absObj.filename, absObj.pathname ),
					search = relObj.search || ( !hasPath && absObj.search ) || "",
					hash = relObj.hash;

				return protocol + doubleSlash + authority + pathname + search + hash;
			},

			//Add search (aka query) params to the specified url.
			addSearchParams: function( url, params ) {
				var u = path.parseUrl( url ),
					p = ( typeof params === "object" ) ? $.param( params ) : params,
					s = u.search || "?";
				return u.hrefNoSearch + s + ( s.charAt( s.length - 1 ) !== "?" ? "&" : "" ) + p + ( u.hash || "" );
			},

			convertUrlToDataUrl: function( absUrl ) {
				var u = path.parseUrl( absUrl );
				if ( path.isEmbeddedPage( u ) ) {
					// For embedded pages, remove the dialog hash key as in getFilePath(),
					// otherwise the Data Url won't match the id of the embedded Page.
					return u.hash.split( dialogHashKey )[0].replace( /^#/, "" );
				} else if ( path.isSameDomain( u, documentBase ) ) {
					return u.hrefNoHash.replace( documentBase.domain, "" ).split( dialogHashKey )[0];
				}

				return window.decodeURIComponent(absUrl);
			},

			//get path from current hash, or from a file path
			get: function( newPath ) {
				if ( newPath === undefined ) {
					newPath = path.parseLocation().hash;
				}
				return path.stripHash( newPath ).replace( /[^\/]*\.[^\/*]+$/, '' );
			},

			//return the substring of a filepath before the sub-page key, for making a server request
			getFilePath: function( path ) {
				var splitkey = '&' + $.mobile.subPageUrlKey;
				return path && path.split( splitkey )[0].split( dialogHashKey )[0];
			},

			//set location hash to path
			set: function( path ) {
				location.hash = path;
			},

			//test if a given url (string) is a path
			//NOTE might be exceptionally naive
			isPath: function( url ) {
				return ( /\// ).test( url );
			},

			//return a url path with the window's location protocol/hostname/pathname removed
			clean: function( url ) {
				return url.replace( documentBase.domain, "" );
			},

			//just return the url without an initial #
			stripHash: function( url ) {
				return url.replace( /^#/, "" );
			},

			//remove the preceding hash, any query params, and dialog notations
			cleanHash: function( hash ) {
				return path.stripHash( hash.replace( /\?.*$/, "" ).replace( dialogHashKey, "" ) );
			},

			isHashValid: function( hash ) {
				return ( /^#[^#]+$/ ).test( hash );
			},

			//check whether a url is referencing the same domain, or an external domain or different protocol
			//could be mailto, etc
			isExternal: function( url ) {
				var u = path.parseUrl( url );
				return u.protocol && u.domain !== documentUrl.domain ? true : false;
			},

			hasProtocol: function( url ) {
				return ( /^(:?\w+:)/ ).test( url );
			},

			//check if the specified url refers to the first page in the main application document.
			isFirstPageUrl: function( url ) {
				// We only deal with absolute paths.
				var u = path.parseUrl( path.makeUrlAbsolute( url, documentBase ) ),

					// Does the url have the same path as the document?
					samePath = u.hrefNoHash === documentUrl.hrefNoHash || ( documentBaseDiffers && u.hrefNoHash === documentBase.hrefNoHash ),

					// Get the first page element.
					fp = $.mobile.firstPage,

					// Get the id of the first page element if it has one.
					fpId = fp && fp[0] ? fp[0].id : undefined;

					// The url refers to the first page if the path matches the document and
					// it either has no hash value, or the hash is exactly equal to the id of the
					// first page element.
					return samePath && ( !u.hash || u.hash === "#" || ( fpId && u.hash.replace( /^#/, "" ) === fpId ) );
			},

			isEmbeddedPage: function( url ) {
				var u = path.parseUrl( url );

				//if the path is absolute, then we need to compare the url against
				//both the documentUrl and the documentBase. The main reason for this
				//is that links embedded within external documents will refer to the
				//application document, whereas links embedded within the application
				//document will be resolved against the document base.
				if ( u.protocol !== "" ) {
					return ( u.hash && ( u.hrefNoHash === documentUrl.hrefNoHash || ( documentBaseDiffers && u.hrefNoHash === documentBase.hrefNoHash ) ) );
				}
				return ( /^#/ ).test( u.href );
			},


			// Some embedded browsers, like the web view in Phone Gap, allow cross-domain XHR
			// requests if the document doing the request was loaded via the file:// protocol.
			// This is usually to allow the application to "phone home" and fetch app specific
			// data. We normally let the browser handle external/cross-domain urls, but if the
			// allowCrossDomainPages option is true, we will allow cross-domain http/https
			// requests to go through our page loading logic.
			isPermittedCrossDomainRequest: function( docUrl, reqUrl ) {
				return $.mobile.allowCrossDomainPages &&
					docUrl.protocol === "file:" &&
					reqUrl.search( /^https?:/ ) !== -1;
			}
		},

		//will be defined when a link is clicked and given an active class
		$activeClickedLink = null,

		//urlHistory is purely here to make guesses at whether the back or forward button was clicked
		//and provide an appropriate transition
		urlHistory = {
			// Array of pages that are visited during a single page load.
			// Each has a url and optional transition, title, and pageUrl (which represents the file path, in cases where URL is obscured, such as dialogs)
			stack: [],

			//maintain an index number for the active page in the stack
			activeIndex: 0,

			//get active
			getActive: function() {
				return urlHistory.stack[ urlHistory.activeIndex ];
			},

			getPrev: function() {
				return urlHistory.stack[ urlHistory.activeIndex - 1 ];
			},

			getNext: function() {
				return urlHistory.stack[ urlHistory.activeIndex + 1 ];
			},

			// addNew is used whenever a new page is added
			addNew: function( url, transition, title, pageUrl, role ) {
				//if there's forward history, wipe it
				if ( urlHistory.getNext() ) {
					urlHistory.clearForward();
				}

				urlHistory.stack.push( {url : url, transition: transition, title: title, pageUrl: pageUrl, role: role } );

				urlHistory.activeIndex = urlHistory.stack.length - 1;
			},

			//wipe urls ahead of active index
			clearForward: function() {
				urlHistory.stack = urlHistory.stack.slice( 0, urlHistory.activeIndex + 1 );
			},

			directHashChange: function( opts ) {
				var back , forward, newActiveIndex, prev = this.getActive();

				// check if url is in history and if it's ahead or behind current page
				$.each( urlHistory.stack, function( i, historyEntry ) {

					//if the url is in the stack, it's a forward or a back
					if ( decodeURIComponent( opts.currentUrl ) === decodeURIComponent( historyEntry.url ) ) {
						//define back and forward by whether url is older or newer than current page
						back = i < urlHistory.activeIndex;
						forward = !back;
						newActiveIndex = i;
					}
				});

				// save new page index, null check to prevent falsey 0 result
				this.activeIndex = newActiveIndex !== undefined ? newActiveIndex : this.activeIndex;

				if ( back ) {
					( opts.either || opts.isBack )( true );
				} else if ( forward ) {
					( opts.either || opts.isForward )( false );
				}
			},

			//disable hashchange event listener internally to ignore one change
			//toggled internally when location.hash is updated to match the url of a successful page load
			ignoreNextHashChange: false
		},

		//define first selector to receive focus when a page is shown
		focusable = "[tabindex],a,button:visible,select:visible,input",

		//queue to hold simultanious page transitions
		pageTransitionQueue = [],

		//indicates whether or not page is in process of transitioning
		isPageTransitioning = false,

		//nonsense hash change key for dialogs, so they create a history entry
		dialogHashKey = "&ui-state=dialog",

		//existing base tag?
		$base = $head.children( "base" ),

		//tuck away the original document URL minus any fragment.
		documentUrl = path.parseLocation(),

		//if the document has an embedded base tag, documentBase is set to its
		//initial value. If a base tag does not exist, then we default to the documentUrl.
		documentBase = $base.length ? path.parseUrl( path.makeUrlAbsolute( $base.attr( "href" ), documentUrl.href ) ) : documentUrl,

		//cache the comparison once.
		documentBaseDiffers = ( documentUrl.hrefNoHash !== documentBase.hrefNoHash ),

		getScreenHeight = $.mobile.getScreenHeight;

		//base element management, defined depending on dynamic base tag support
		var base = $.support.dynamicBaseTag ? {

			//define base element, for use in routing asset urls that are referenced in Ajax-requested markup
			element: ( $base.length ? $base : $( "<base>", { href: documentBase.hrefNoHash } ).prependTo( $head ) ),

			//set the generated BASE element's href attribute to a new page's base path
			set: function( href ) {
				base.element.attr( "href", path.makeUrlAbsolute( href, documentBase ) );
			},

			//set the generated BASE element's href attribute to a new page's base path
			reset: function() {
				base.element.attr( "href", documentBase.hrefNoHash );
			}

		} : undefined;

	/* internal utility functions */

	// NOTE Issue #4950 Android phonegap doesn't navigate back properly
	//      when a full page refresh has taken place. It appears that hashchange
	//      and replacestate history alterations work fine but we need to support
	//      both forms of history traversal in our code that uses backward history
	//      movement
	$.mobile.back = function() {
		var nav = window.navigator;

		// if the setting is on and the navigator object is
		// available use the phonegap navigation capability
		if( this.phonegapNavigationEnabled &&
			nav &&
			nav.app &&
			nav.app.backHistory ){
			nav.app.backHistory();
		} else {
			window.history.back();
		}
	};

	//direct focus to the page title, or otherwise first focusable element
	$.mobile.focusPage = function ( page ) {
		var autofocus = page.find( "[autofocus]" ),
			pageTitle = page.find( ".ui-title:eq(0)" );

		if ( autofocus.length ) {
			autofocus.focus();
			return;
		}

		if ( pageTitle.length ) {
			pageTitle.focus();
		} else{
			page.focus();
		}
	};

	//remove active classes after page transition or error
	function removeActiveLinkClass( forceRemoval ) {
		if ( !!$activeClickedLink && ( !$activeClickedLink.closest( "." + $.mobile.activePageClass ).length || forceRemoval ) ) {
			$activeClickedLink.removeClass( $.mobile.activeBtnClass );
		}
		$activeClickedLink = null;
	}

	function releasePageTransitionLock() {
		isPageTransitioning = false;
		if ( pageTransitionQueue.length > 0 ) {
			$.mobile.changePage.apply( null, pageTransitionQueue.pop() );
		}
	}

	// Save the last scroll distance per page, before it is hidden
	var setLastScrollEnabled = true,
		setLastScroll, delayedSetLastScroll;

	setLastScroll = function() {
		// this barrier prevents setting the scroll value based on the browser
		// scrolling the window based on a hashchange
		if ( !setLastScrollEnabled ) {
			return;
		}

		var active = $.mobile.urlHistory.getActive();

		if ( active ) {
			var lastScroll = $window.scrollTop();

			// Set active page's lastScroll prop.
			// If the location we're scrolling to is less than minScrollBack, let it go.
			active.lastScroll = lastScroll < $.mobile.minScrollBack ? $.mobile.defaultHomeScroll : lastScroll;
		}
	};

	// bind to scrollstop to gather scroll position. The delay allows for the hashchange
	// event to fire and disable scroll recording in the case where the browser scrolls
	// to the hash targets location (sometimes the top of the page). once pagechange fires
	// getLastScroll is again permitted to operate
	delayedSetLastScroll = function() {
		setTimeout( setLastScroll, 100 );
	};

	// disable an scroll setting when a hashchange has been fired, this only works
	// because the recording of the scroll position is delayed for 100ms after
	// the browser might have changed the position because of the hashchange
	$window.bind( $.support.pushState ? "popstate" : "hashchange", function() {
		setLastScrollEnabled = false;
	});

	// handle initial hashchange from chrome :(
	$window.one( $.support.pushState ? "popstate" : "hashchange", function() {
		setLastScrollEnabled = true;
	});

	// wait until the mobile page container has been determined to bind to pagechange
	$window.one( "pagecontainercreate", function() {
		// once the page has changed, re-enable the scroll recording
		$.mobile.pageContainer.bind( "pagechange", function() {

			setLastScrollEnabled = true;

			// remove any binding that previously existed on the get scroll
			// which may or may not be different than the scroll element determined for
			// this page previously
			$window.unbind( "scrollstop", delayedSetLastScroll );

			// determine and bind to the current scoll element which may be the window
			// or in the case of touch overflow the element with touch overflow
			$window.bind( "scrollstop", delayedSetLastScroll );
		});
	});

	// bind to scrollstop for the first page as "pagechange" won't be fired in that case
	$window.bind( "scrollstop", delayedSetLastScroll );

	// No-op implementation of transition degradation
	$.mobile._maybeDegradeTransition = $.mobile._maybeDegradeTransition || function( transition ) {
		return transition;
	};

	//function for transitioning between two existing pages
	function transitionPages( toPage, fromPage, transition, reverse ) {

		if ( fromPage ) {
			//trigger before show/hide events
			fromPage.data( "page" )._trigger( "beforehide", null, { nextPage: toPage } );
		}

		toPage.data( "page" )._trigger( "beforeshow", null, { prevPage: fromPage || $( "" ) } );

		//clear page loader
		$.mobile.hidePageLoadingMsg();

		transition = $.mobile._maybeDegradeTransition( transition );

		//find the transition handler for the specified transition. If there
		//isn't one in our transitionHandlers dictionary, use the default one.
		//call the handler immediately to kick-off the transition.
		var th = $.mobile.transitionHandlers[ transition || "default" ] || $.mobile.defaultTransitionHandler,
			promise = th( transition, reverse, toPage, fromPage );

		promise.done(function() {

			//trigger show/hide events
			if ( fromPage ) {
				fromPage.data( "page" )._trigger( "hide", null, { nextPage: toPage } );
			}

			//trigger pageshow, define prevPage as either fromPage or empty jQuery obj
			toPage.data( "page" )._trigger( "show", null, { prevPage: fromPage || $( "" ) } );
		});

		return promise;
	}

	//simply set the active page's minimum height to screen height, depending on orientation
	function resetActivePageHeight() {
		var aPage = $( "." + $.mobile.activePageClass ),
			aPagePadT = parseFloat( aPage.css( "padding-top" ) ),
			aPagePadB = parseFloat( aPage.css( "padding-bottom" ) ),
			aPageBorderT = parseFloat( aPage.css( "border-top-width" ) ),
			aPageBorderB = parseFloat( aPage.css( "border-bottom-width" ) );

		aPage.css( "min-height", getScreenHeight() - aPagePadT - aPagePadB - aPageBorderT - aPageBorderB );
	}

	//shared page enhancements
	function enhancePage( $page, role ) {
		// If a role was specified, make sure the data-role attribute
		// on the page element is in sync.
		if ( role ) {
			$page.attr( "data-" + $.mobile.ns + "role", role );
		}

		//run page plugin
		$page.page();
	}

	/* exposed $.mobile methods */

	//animation complete callback
	$.fn.animationComplete = function( callback ) {
		if ( $.support.cssTransitions ) {
			return $( this ).one( 'webkitAnimationEnd animationend', callback );
		}
		else{
			// defer execution for consistency between webkit/non webkit
			setTimeout( callback, 0 );
			return $( this );
		}
	};

	//expose path object on $.mobile
	$.mobile.path = path;

	//expose base object on $.mobile
	$.mobile.base = base;

	//history stack
	$.mobile.urlHistory = urlHistory;

	$.mobile.dialogHashKey = dialogHashKey;



	//enable cross-domain page support
	$.mobile.allowCrossDomainPages = false;

	//return the original document url
	$.mobile.getDocumentUrl = function( asParsedObject ) {
		return asParsedObject ? $.extend( {}, documentUrl ) : documentUrl.href;
	};

	//return the original document base url
	$.mobile.getDocumentBase = function( asParsedObject ) {
		return asParsedObject ? $.extend( {}, documentBase ) : documentBase.href;
	};

	$.mobile._bindPageRemove = function() {
		var page = $( this );

		// when dom caching is not enabled or the page is embedded bind to remove the page on hide
		if ( !page.data( "page" ).options.domCache &&
				page.is( ":jqmData(external-page='true')" ) ) {

			page.bind( 'pagehide.remove', function() {
				var $this = $( this ),
					prEvent = new $.Event( "pageremove" );

				$this.trigger( prEvent );

				if ( !prEvent.isDefaultPrevented() ) {
					$this.removeWithDependents();
				}
			});
		}
	};

	// Load a page into the DOM.
	$.mobile.loadPage = function( url, options ) {
		// This function uses deferred notifications to let callers
		// know when the page is done loading, or if an error has occurred.
		var deferred = $.Deferred(),

			// The default loadPage options with overrides specified by
			// the caller.
			settings = $.extend( {}, $.mobile.loadPage.defaults, options ),

			// The DOM element for the page after it has been loaded.
			page = null,

			// If the reloadPage option is true, and the page is already
			// in the DOM, dupCachedPage will be set to the page element
			// so that it can be removed after the new version of the
			// page is loaded off the network.
			dupCachedPage = null,

			// determine the current base url
			findBaseWithDefault = function() {
				var closestBase = ( $.mobile.activePage && getClosestBaseUrl( $.mobile.activePage ) );
				return closestBase || documentBase.hrefNoHash;
			},

			// The absolute version of the URL passed into the function. This
			// version of the URL may contain dialog/subpage params in it.
			absUrl = path.makeUrlAbsolute( url, findBaseWithDefault() );


		// If the caller provided data, and we're using "get" request,
		// append the data to the URL.
		if ( settings.data && settings.type === "get" ) {
			absUrl = path.addSearchParams( absUrl, settings.data );
			settings.data = undefined;
		}

		// If the caller is using a "post" request, reloadPage must be true
		if ( settings.data && settings.type === "post" ) {
			settings.reloadPage = true;
		}

		// The absolute version of the URL minus any dialog/subpage params.
		// In otherwords the real URL of the page to be loaded.
		var fileUrl = path.getFilePath( absUrl ),

			// The version of the Url actually stored in the data-url attribute of
			// the page. For embedded pages, it is just the id of the page. For pages
			// within the same domain as the document base, it is the site relative
			// path. For cross-domain pages (Phone Gap only) the entire absolute Url
			// used to load the page.
			dataUrl = path.convertUrlToDataUrl( absUrl );

		// Make sure we have a pageContainer to work with.
		settings.pageContainer = settings.pageContainer || $.mobile.pageContainer;

		// Check to see if the page already exists in the DOM.
		// NOTE do _not_ use the :jqmData psuedo selector because parenthesis
		//      are a valid url char and it breaks on the first occurence
		page = settings.pageContainer.children( "[data-" + $.mobile.ns +"url='" + dataUrl + "']" );

		// If we failed to find the page, check to see if the url is a
		// reference to an embedded page. If so, it may have been dynamically
		// injected by a developer, in which case it would be lacking a data-url
		// attribute and in need of enhancement.
		if ( page.length === 0 && dataUrl && !path.isPath( dataUrl ) ) {
			page = settings.pageContainer.children( "#" + dataUrl )
				.attr( "data-" + $.mobile.ns + "url", dataUrl )
				.jqmData( "url", dataUrl );
		}

		// If we failed to find a page in the DOM, check the URL to see if it
		// refers to the first page in the application. If it isn't a reference
		// to the first page and refers to non-existent embedded page, error out.
		if ( page.length === 0 ) {
			if ( $.mobile.firstPage && path.isFirstPageUrl( fileUrl ) ) {
				// Check to make sure our cached-first-page is actually
				// in the DOM. Some user deployed apps are pruning the first
				// page from the DOM for various reasons, we check for this
				// case here because we don't want a first-page with an id
				// falling through to the non-existent embedded page error
				// case. If the first-page is not in the DOM, then we let
				// things fall through to the ajax loading code below so
				// that it gets reloaded.
				if ( $.mobile.firstPage.parent().length ) {
					page = $( $.mobile.firstPage );
				}
			} else if ( path.isEmbeddedPage( fileUrl )  ) {
				deferred.reject( absUrl, options );
				return deferred.promise();
			}
		}

		// If the page we are interested in is already in the DOM,
		// and the caller did not indicate that we should force a
		// reload of the file, we are done. Otherwise, track the
		// existing page as a duplicated.
		if ( page.length ) {
			if ( !settings.reloadPage ) {
				enhancePage( page, settings.role );
				deferred.resolve( absUrl, options, page );
				return deferred.promise();
			}
			dupCachedPage = page;
		}

		var mpc = settings.pageContainer,
			pblEvent = new $.Event( "pagebeforeload" ),
			triggerData = { url: url, absUrl: absUrl, dataUrl: dataUrl, deferred: deferred, options: settings };

		// Let listeners know we're about to load a page.
		mpc.trigger( pblEvent, triggerData );

		// If the default behavior is prevented, stop here!
		if ( pblEvent.isDefaultPrevented() ) {
			return deferred.promise();
		}

		if ( settings.showLoadMsg ) {

			// This configurable timeout allows cached pages a brief delay to load without showing a message
			var loadMsgDelay = setTimeout(function() {
					$.mobile.showPageLoadingMsg();
				}, settings.loadMsgDelay ),

				// Shared logic for clearing timeout and removing message.
				hideMsg = function() {

					// Stop message show timer
					clearTimeout( loadMsgDelay );

					// Hide loading message
					$.mobile.hidePageLoadingMsg();
				};
		}

		// Reset base to the default document base.
		if ( base ) {
			base.reset();
		}

		if ( !( $.mobile.allowCrossDomainPages || path.isSameDomain( documentUrl, absUrl ) ) ) {
			deferred.reject( absUrl, options );
		} else {
			// Load the new page.
			$.ajax({
				url: fileUrl,
				type: settings.type,
				data: settings.data,
				dataType: "html",
				success: function( html, textStatus, xhr ) {
					//pre-parse html to check for a data-url,
					//use it as the new fileUrl, base path, etc
					var all = $( "<div></div>" ),

						//page title regexp
						newPageTitle = html.match( /<title[^>]*>([^<]*)/ ) && RegExp.$1,

						// TODO handle dialogs again
						pageElemRegex = new RegExp( "(<[^>]+\\bdata-" + $.mobile.ns + "role=[\"']?page[\"']?[^>]*>)" ),
						dataUrlRegex = new RegExp( "\\bdata-" + $.mobile.ns + "url=[\"']?([^\"'>]*)[\"']?" );


					// data-url must be provided for the base tag so resource requests can be directed to the
					// correct url. loading into a temprorary element makes these requests immediately
					if ( pageElemRegex.test( html ) &&
							RegExp.$1 &&
							dataUrlRegex.test( RegExp.$1 ) &&
							RegExp.$1 ) {
						url = fileUrl = path.getFilePath( $( "<div>" + RegExp.$1 + "</div>" ).text() );
					}

					if ( base ) {
						base.set( fileUrl );
					}

					//workaround to allow scripts to execute when included in page divs
					all.get( 0 ).innerHTML = html;
					page = all.find( ":jqmData(role='page'), :jqmData(role='dialog')" ).first();

					//if page elem couldn't be found, create one and insert the body element's contents
					if ( !page.length ) {
						page = $( "<div data-" + $.mobile.ns + "role='page'>" + html.split( /<\/?body[^>]*>/gmi )[1] + "</div>" );
					}

					if ( newPageTitle && !page.jqmData( "title" ) ) {
						if ( ~newPageTitle.indexOf( "&" ) ) {
							newPageTitle = $( "<div>" + newPageTitle + "</div>" ).text();
						}
						page.jqmData( "title", newPageTitle );
					}

					//rewrite src and href attrs to use a base url
					if ( !$.support.dynamicBaseTag ) {
						var newPath = path.get( fileUrl );
						page.find( "[src], link[href], a[rel='external'], :jqmData(ajax='false'), a[target]" ).each(function() {
							var thisAttr = $( this ).is( '[href]' ) ? 'href' :
									$( this ).is( '[src]' ) ? 'src' : 'action',
								thisUrl = $( this ).attr( thisAttr );

							// XXX_jblas: We need to fix this so that it removes the document
							//            base URL, and then prepends with the new page URL.
							//if full path exists and is same, chop it - helps IE out
							thisUrl = thisUrl.replace( location.protocol + '//' + location.host + location.pathname, '' );

							if ( !/^(\w+:|#|\/)/.test( thisUrl ) ) {
								$( this ).attr( thisAttr, newPath + thisUrl );
							}
						});
					}

					//append to page and enhance
					// TODO taging a page with external to make sure that embedded pages aren't removed
					//      by the various page handling code is bad. Having page handling code in many
					//      places is bad. Solutions post 1.0
					page
						.attr( "data-" + $.mobile.ns + "url", path.convertUrlToDataUrl( fileUrl ) )
						.attr( "data-" + $.mobile.ns + "external-page", true )
						.appendTo( settings.pageContainer );

					// wait for page creation to leverage options defined on widget
					page.one( 'pagecreate', $.mobile._bindPageRemove );

					enhancePage( page, settings.role );

					// Enhancing the page may result in new dialogs/sub pages being inserted
					// into the DOM. If the original absUrl refers to a sub-page, that is the
					// real page we are interested in.
					if ( absUrl.indexOf( "&" + $.mobile.subPageUrlKey ) > -1 ) {
						page = settings.pageContainer.children( "[data-" + $.mobile.ns +"url='" + dataUrl + "']" );
					}

					//bind pageHide to removePage after it's hidden, if the page options specify to do so

					// Remove loading message.
					if ( settings.showLoadMsg ) {
						hideMsg();
					}

					// Add the page reference and xhr to our triggerData.
					triggerData.xhr = xhr;
					triggerData.textStatus = textStatus;
					triggerData.page = page;

					// Let listeners know the page loaded successfully.
					settings.pageContainer.trigger( "pageload", triggerData );

					deferred.resolve( absUrl, options, page, dupCachedPage );
				},
				error: function( xhr, textStatus, errorThrown ) {
					//set base back to current path
					if ( base ) {
						base.set( path.get() );
					}

					// Add error info to our triggerData.
					triggerData.xhr = xhr;
					triggerData.textStatus = textStatus;
					triggerData.errorThrown = errorThrown;

					var plfEvent = new $.Event( "pageloadfailed" );

					// Let listeners know the page load failed.
					settings.pageContainer.trigger( plfEvent, triggerData );

					// If the default behavior is prevented, stop here!
					// Note that it is the responsibility of the listener/handler
					// that called preventDefault(), to resolve/reject the
					// deferred object within the triggerData.
					if ( plfEvent.isDefaultPrevented() ) {
						return;
					}

					// Remove loading message.
					if ( settings.showLoadMsg ) {

						// Remove loading message.
						hideMsg();

						// show error message
						$.mobile.showPageLoadingMsg( $.mobile.pageLoadErrorMessageTheme, $.mobile.pageLoadErrorMessage, true );

						// hide after delay
						setTimeout( $.mobile.hidePageLoadingMsg, 1500 );
					}

					deferred.reject( absUrl, options );
				}
			});
		}

		return deferred.promise();
	};

	$.mobile.loadPage.defaults = {
		type: "get",
		data: undefined,
		reloadPage: false,
		role: undefined, // By default we rely on the role defined by the @data-role attribute.
		showLoadMsg: false,
		pageContainer: undefined,
		loadMsgDelay: 50 // This delay allows loads that pull from browser cache to occur without showing the loading message.
	};

	// Show a specific page in the page container.
	$.mobile.changePage = function( toPage, options ) {
		// If we are in the midst of a transition, queue the current request.
		// We'll call changePage() once we're done with the current transition to
		// service the request.
		if ( isPageTransitioning ) {
			pageTransitionQueue.unshift( arguments );
			return;
		}

		var settings = $.extend( {}, $.mobile.changePage.defaults, options );

		// Make sure we have a pageContainer to work with.
		settings.pageContainer = settings.pageContainer || $.mobile.pageContainer;

		// Make sure we have a fromPage.
		settings.fromPage = settings.fromPage || $.mobile.activePage;

		var mpc = settings.pageContainer,
			pbcEvent = new $.Event( "pagebeforechange" ),
			triggerData = { toPage: toPage, options: settings };

		// Let listeners know we're about to change the current page.
		mpc.trigger( pbcEvent, triggerData );

		// If the default behavior is prevented, stop here!
		if ( pbcEvent.isDefaultPrevented() ) {
			return;
		}

		// We allow "pagebeforechange" observers to modify the toPage in the trigger
		// data to allow for redirects. Make sure our toPage is updated.

		toPage = triggerData.toPage;

		// Set the isPageTransitioning flag to prevent any requests from
		// entering this method while we are in the midst of loading a page
		// or transitioning.

		isPageTransitioning = true;

		// If the caller passed us a url, call loadPage()
		// to make sure it is loaded into the DOM. We'll listen
		// to the promise object it returns so we know when
		// it is done loading or if an error ocurred.
		if ( typeof toPage === "string" ) {
			$.mobile.loadPage( toPage, settings )
				.done(function( url, options, newPage, dupCachedPage ) {
					isPageTransitioning = false;
					options.duplicateCachedPage = dupCachedPage;
					$.mobile.changePage( newPage, options );
				})
				.fail(function( url, options ) {
					isPageTransitioning = false;

					//clear out the active button state
					removeActiveLinkClass( true );

					//release transition lock so navigation is free again
					releasePageTransitionLock();
					settings.pageContainer.trigger( "pagechangefailed", triggerData );
				});
			return;
		}

		// If we are going to the first-page of the application, we need to make
		// sure settings.dataUrl is set to the application document url. This allows
		// us to avoid generating a document url with an id hash in the case where the
		// first-page of the document has an id attribute specified.
		if ( toPage[ 0 ] === $.mobile.firstPage[ 0 ] && !settings.dataUrl ) {
			settings.dataUrl = documentUrl.hrefNoHash;
		}

		// The caller passed us a real page DOM element. Update our
		// internal state and then trigger a transition to the page.
		var fromPage = settings.fromPage,
			url = ( settings.dataUrl && path.convertUrlToDataUrl( settings.dataUrl ) ) || toPage.jqmData( "url" ),
			// The pageUrl var is usually the same as url, except when url is obscured as a dialog url. pageUrl always contains the file path
			pageUrl = url,
			fileUrl = path.getFilePath( url ),
			active = urlHistory.getActive(),
			activeIsInitialPage = urlHistory.activeIndex === 0,
			historyDir = 0,
			pageTitle = document.title,
			isDialog = settings.role === "dialog" || toPage.jqmData( "role" ) === "dialog";

		// By default, we prevent changePage requests when the fromPage and toPage
		// are the same element, but folks that generate content manually/dynamically
		// and reuse pages want to be able to transition to the same page. To allow
		// this, they will need to change the default value of allowSamePageTransition
		// to true, *OR*, pass it in as an option when they manually call changePage().
		// It should be noted that our default transition animations assume that the
		// formPage and toPage are different elements, so they may behave unexpectedly.
		// It is up to the developer that turns on the allowSamePageTransitiona option
		// to either turn off transition animations, or make sure that an appropriate
		// animation transition is used.
		if ( fromPage && fromPage[0] === toPage[0] && !settings.allowSamePageTransition ) {
			isPageTransitioning = false;
			mpc.trigger( "pagechange", triggerData );

			// Even if there is no page change to be done, we should keep the urlHistory in sync with the hash changes
			if ( settings.fromHashChange ) {
				urlHistory.directHashChange({
					currentUrl:	url,
					isBack:		function() {},
					isForward:	function() {}
				});
			}

			return;
		}

		// We need to make sure the page we are given has already been enhanced.
		enhancePage( toPage, settings.role );

		// If the changePage request was sent from a hashChange event, check to see if the
		// page is already within the urlHistory stack. If so, we'll assume the user hit
		// the forward/back button and will try to match the transition accordingly.
		if ( settings.fromHashChange ) {
			urlHistory.directHashChange({
				currentUrl:	url,
				isBack:		function() { historyDir = -1; },
				isForward:	function() { historyDir = 1; }
			});
		}

		// Kill the keyboard.
		// XXX_jblas: We need to stop crawling the entire document to kill focus. Instead,
		//            we should be tracking focus with a delegate() handler so we already have
		//            the element in hand at this point.
		// Wrap this in a try/catch block since IE9 throw "Unspecified error" if document.activeElement
		// is undefined when we are in an IFrame.
		try {
			if ( document.activeElement && document.activeElement.nodeName.toLowerCase() !== 'body' ) {
				$( document.activeElement ).blur();
			} else {
				$( "input:focus, textarea:focus, select:focus" ).blur();
			}
		} catch( e ) {}

		// Record whether we are at a place in history where a dialog used to be - if so, do not add a new history entry and do not change the hash either
		var alreadyThere = false;

		// If we're displaying the page as a dialog, we don't want the url
		// for the dialog content to be used in the hash. Instead, we want
		// to append the dialogHashKey to the url of the current page.
		if ( isDialog && active ) {
			// on the initial page load active.url is undefined and in that case should
			// be an empty string. Moving the undefined -> empty string back into
			// urlHistory.addNew seemed imprudent given undefined better represents
			// the url state

			// If we are at a place in history that once belonged to a dialog, reuse
			// this state without adding to urlHistory and without modifying the hash.
			// However, if a dialog is already displayed at this point, and we're
			// about to display another dialog, then we must add another hash and
			// history entry on top so that one may navigate back to the original dialog
			if ( active.url.indexOf( dialogHashKey ) > -1 && !$.mobile.activePage.is( ".ui-dialog" ) ) {
				settings.changeHash = false;
				alreadyThere = true;
			}

			// Normally, we tack on a dialog hash key, but if this is the location of a stale dialog,
			// we reuse the URL from the entry
			url = ( active.url || "" ) + ( alreadyThere ? "" : dialogHashKey );

			// tack on another dialogHashKey if this is the same as the initial hash
			// this makes sure that a history entry is created for this dialog
			if ( urlHistory.activeIndex === 0 && url === urlHistory.initialDst ) {
				url += dialogHashKey;
			}
		}

		// Set the location hash.
		if ( settings.changeHash !== false && url ) {
			//disable hash listening temporarily
			urlHistory.ignoreNextHashChange = true;
			//update hash and history
			path.set( url );
		}

		// if title element wasn't found, try the page div data attr too
		// If this is a deep-link or a reload ( active === undefined ) then just use pageTitle
		var newPageTitle = ( !active )? pageTitle : toPage.jqmData( "title" ) || toPage.children( ":jqmData(role='header')" ).find( ".ui-title" ).getEncodedText();
		if ( !!newPageTitle && pageTitle === document.title ) {
			pageTitle = newPageTitle;
		}
		if ( !toPage.jqmData( "title" ) ) {
			toPage.jqmData( "title", pageTitle );
		}

		// Make sure we have a transition defined.
		settings.transition = settings.transition ||
			( ( historyDir && !activeIsInitialPage ) ? active.transition : undefined ) ||
			( isDialog ? $.mobile.defaultDialogTransition : $.mobile.defaultPageTransition );

		//add page to history stack if it's not back or forward
		if ( !historyDir ) {
			// Overwrite the current entry if it's a leftover from a dialog
			if ( alreadyThere ) {
				urlHistory.activeIndex = Math.max( 0, urlHistory.activeIndex - 1 );
			}
			urlHistory.addNew( url, settings.transition, pageTitle, pageUrl, settings.role );
		}

		//set page title
		document.title = urlHistory.getActive().title;

		//set "toPage" as activePage
		$.mobile.activePage = toPage;

		// If we're navigating back in the URL history, set reverse accordingly.
		settings.reverse = settings.reverse || historyDir < 0;

		transitionPages( toPage, fromPage, settings.transition, settings.reverse )
			.done(function( name, reverse, $to, $from, alreadyFocused ) {
				removeActiveLinkClass();

				//if there's a duplicateCachedPage, remove it from the DOM now that it's hidden
				if ( settings.duplicateCachedPage ) {
					settings.duplicateCachedPage.remove();
				}

				// Send focus to the newly shown page. Moved from promise .done binding in transitionPages
				// itself to avoid ie bug that reports offsetWidth as > 0 (core check for visibility)
				// despite visibility: hidden addresses issue #2965
				// https://github.com/jquery/jquery-mobile/issues/2965
				if ( !alreadyFocused ) {
					$.mobile.focusPage( toPage );
				}

				releasePageTransitionLock();

				// Let listeners know we're all done changing the current page.
				mpc.trigger( "pagechange", triggerData );
			});
	};

	$.mobile.changePage.defaults = {
		transition: undefined,
		reverse: false,
		changeHash: true,
		fromHashChange: false,
		role: undefined, // By default we rely on the role defined by the @data-role attribute.
		duplicateCachedPage: undefined,
		pageContainer: undefined,
		showLoadMsg: true, //loading message shows by default when pages are being fetched during changePage
		dataUrl: undefined,
		fromPage: undefined,
		allowSamePageTransition: false
	};

/* Event Bindings - hashchange, submit, and click */
	function findClosestLink( ele )
	{
		while ( ele ) {
			// Look for the closest element with a nodeName of "a".
			// Note that we are checking if we have a valid nodeName
			// before attempting to access it. This is because the
			// node we get called with could have originated from within
			// an embedded SVG document where some symbol instance elements
			// don't have nodeName defined on them, or strings are of type
			// SVGAnimatedString.
			if ( ( typeof ele.nodeName === "string" ) && ele.nodeName.toLowerCase() === "a" ) {
				break;
			}
			ele = ele.parentNode;
		}
		return ele;
	}

	// The base URL for any given element depends on the page it resides in.
	function getClosestBaseUrl( ele )
	{
		// Find the closest page and extract out its url.
		var url = $( ele ).closest( ".ui-page" ).jqmData( "url" ),
			base = documentBase.hrefNoHash;

		if ( !url || !path.isPath( url ) ) {
			url = base;
		}

		return path.makeUrlAbsolute( url, base);
	}

	//The following event bindings should be bound after mobileinit has been triggered
	//the following deferred is resolved in the init file
	$.mobile.navreadyDeferred = $.Deferred();
	$.mobile.navreadyDeferred.done(function() {
		//bind to form submit events, handle with Ajax
		$( document ).delegate( "form", "submit", function( event ) {
			var $this = $( this );

			if ( !$.mobile.ajaxEnabled ||
					// test that the form is, itself, ajax false
					$this.is( ":jqmData(ajax='false')" ) ||
					// test that $.mobile.ignoreContentEnabled is set and
					// the form or one of it's parents is ajax=false
					!$this.jqmHijackable().length ) {
				return;
			}

			var type = $this.attr( "method" ),
				target = $this.attr( "target" ),
				url = $this.attr( "action" );

			// If no action is specified, browsers default to using the
			// URL of the document containing the form. Since we dynamically
			// pull in pages from external documents, the form should submit
			// to the URL for the source document of the page containing
			// the form.
			if ( !url ) {
				// Get the @data-url for the page containing the form.
				url = getClosestBaseUrl( $this );
				if ( url === documentBase.hrefNoHash ) {
					// The url we got back matches the document base,
					// which means the page must be an internal/embedded page,
					// so default to using the actual document url as a browser
					// would.
					url = documentUrl.hrefNoSearch;
				}
			}

			url = path.makeUrlAbsolute(  url, getClosestBaseUrl( $this ) );

			if ( ( path.isExternal( url ) && !path.isPermittedCrossDomainRequest( documentUrl, url ) ) || target ) {
				return;
			}

			$.mobile.changePage(
				url,
				{
					type:		type && type.length && type.toLowerCase() || "get",
					data:		$this.serialize(),
					transition:	$this.jqmData( "transition" ),
					reverse:	$this.jqmData( "direction" ) === "reverse",
					reloadPage:	true
				}
			);
			event.preventDefault();
		});

		//add active state on vclick
		$( document ).bind( "vclick", function( event ) {
			// if this isn't a left click we don't care. Its important to note
			// that when the virtual event is generated it will create the which attr
			if ( event.which > 1 || !$.mobile.linkBindingEnabled ) {
				return;
			}

			var link = findClosestLink( event.target );

			// split from the previous return logic to avoid find closest where possible
			// TODO teach $.mobile.hijackable to operate on raw dom elements so the link wrapping
			// can be avoided
			if ( !$( link ).jqmHijackable().length ) {
				return;
			}

			if ( link ) {
				if ( path.parseUrl( link.getAttribute( "href" ) || "#" ).hash !== "#" ) {
					removeActiveLinkClass( true );
					$activeClickedLink = $( link ).closest( ".ui-btn" ).not( ".ui-disabled" );
					$activeClickedLink.addClass( $.mobile.activeBtnClass );
				}
			}
		});

		// click routing - direct to HTTP or Ajax, accordingly
		$( document ).bind( "click", function( event ) {
			if ( !$.mobile.linkBindingEnabled ) {
				return;
			}

			var link = findClosestLink( event.target ), $link = $( link ), httpCleanup;

			// If there is no link associated with the click or its not a left
			// click we want to ignore the click
			// TODO teach $.mobile.hijackable to operate on raw dom elements so the link wrapping
			// can be avoided
			if ( !link || event.which > 1 || !$link.jqmHijackable().length ) {
				return;
			}

			//remove active link class if external (then it won't be there if you come back)
			httpCleanup = function() {
				window.setTimeout(function() { removeActiveLinkClass( true ); }, 200 );
			};

			//if there's a data-rel=back attr, go back in history
			if ( $link.is( ":jqmData(rel='back')" ) ) {
				$.mobile.back();
				return false;
			}

			var baseUrl = getClosestBaseUrl( $link ),

				//get href, if defined, otherwise default to empty hash
				href = path.makeUrlAbsolute( $link.attr( "href" ) || "#", baseUrl );

			//if ajax is disabled, exit early
			if ( !$.mobile.ajaxEnabled && !path.isEmbeddedPage( href ) ) {
				httpCleanup();
				//use default click handling
				return;
			}

			// XXX_jblas: Ideally links to application pages should be specified as
			//            an url to the application document with a hash that is either
			//            the site relative path or id to the page. But some of the
			//            internal code that dynamically generates sub-pages for nested
			//            lists and select dialogs, just write a hash in the link they
			//            create. This means the actual URL path is based on whatever
			//            the current value of the base tag is at the time this code
			//            is called. For now we are just assuming that any url with a
			//            hash in it is an application page reference.
			if ( href.search( "#" ) !== -1 ) {
				href = href.replace( /[^#]*#/, "" );
				if ( !href ) {
					//link was an empty hash meant purely
					//for interaction, so we ignore it.
					event.preventDefault();
					return;
				} else if ( path.isPath( href ) ) {
					//we have apath so make it the href we want to load.
					href = path.makeUrlAbsolute( href, baseUrl );
				} else {
					//we have a simple id so use the documentUrl as its base.
					href = path.makeUrlAbsolute( "#" + href, documentUrl.hrefNoHash );
				}
			}

				// Should we handle this link, or let the browser deal with it?
			var useDefaultUrlHandling = $link.is( "[rel='external']" ) || $link.is( ":jqmData(ajax='false')" ) || $link.is( "[target]" ),

				// Some embedded browsers, like the web view in Phone Gap, allow cross-domain XHR
				// requests if the document doing the request was loaded via the file:// protocol.
				// This is usually to allow the application to "phone home" and fetch app specific
				// data. We normally let the browser handle external/cross-domain urls, but if the
				// allowCrossDomainPages option is true, we will allow cross-domain http/https
				// requests to go through our page loading logic.

				//check for protocol or rel and its not an embedded page
				//TODO overlap in logic from isExternal, rel=external check should be
				//     moved into more comprehensive isExternalLink
				isExternal = useDefaultUrlHandling || ( path.isExternal( href ) && !path.isPermittedCrossDomainRequest( documentUrl, href ) );

			if ( isExternal ) {
				httpCleanup();
				//use default click handling
				return;
			}

			//use ajax
			var transition = $link.jqmData( "transition" ),
				reverse = $link.jqmData( "direction" ) === "reverse" ||
							// deprecated - remove by 1.0
							$link.jqmData( "back" ),

				//this may need to be more specific as we use data-rel more
				role = $link.attr( "data-" + $.mobile.ns + "rel" ) || undefined;

			$.mobile.changePage( href, { transition: transition, reverse: reverse, role: role, link: $link } );
			event.preventDefault();
		});

		//prefetch pages when anchors with data-prefetch are encountered
		$( document ).delegate( ".ui-page", "pageshow.prefetch", function() {
			var urls = [];
			$( this ).find( "a:jqmData(prefetch)" ).each(function() {
				var $link = $( this ),
					url = $link.attr( "href" );

				if ( url && $.inArray( url, urls ) === -1 ) {
					urls.push( url );

					$.mobile.loadPage( url, { role: $link.attr( "data-" + $.mobile.ns + "rel" ) } );
				}
			});
		});

		$.mobile._handleHashChange = function( hash ) {
			//find first page via hash
			var to = path.stripHash( hash ),
				//transition is false if it's the first page, undefined otherwise (and may be overridden by default)
				transition = $.mobile.urlHistory.stack.length === 0 ? "none" : undefined,

				// "navigate" event fired to allow others to take advantage of the more robust hashchange handling
				navEvent = new $.Event( "navigate" ),

				// default options for the changPage calls made after examining the current state
				// of the page and the hash
				changePageOptions = {
					transition: transition,
					changeHash: false,
					fromHashChange: true
				};

			if ( 0 === urlHistory.stack.length ) {
				urlHistory.initialDst = to;
			}

			// We should probably fire the "navigate" event from those places that make calls to _handleHashChange,
			// and have _handleHashChange hook into the "navigate" event instead of triggering it here
			$.mobile.pageContainer.trigger( navEvent );
			if ( navEvent.isDefaultPrevented() ) {
				return;
			}

			//if listening is disabled (either globally or temporarily), or it's a dialog hash
			if ( !$.mobile.hashListeningEnabled || urlHistory.ignoreNextHashChange ) {
				urlHistory.ignoreNextHashChange = false;
				return;
			}

			// special case for dialogs
			if ( urlHistory.stack.length > 1 && to.indexOf( dialogHashKey ) > -1 && urlHistory.initialDst !== to ) {

				// If current active page is not a dialog skip the dialog and continue
				// in the same direction
				if ( !$.mobile.activePage.is( ".ui-dialog" ) ) {
					//determine if we're heading forward or backward and continue accordingly past
					//the current dialog
					urlHistory.directHashChange({
						currentUrl: to,
						isBack: function() { $.mobile.back(); },
						isForward: function() { window.history.forward(); }
					});

					// prevent changePage()
					return;
				} else {
					// if the current active page is a dialog and we're navigating
					// to a dialog use the dialog objected saved in the stack
					urlHistory.directHashChange({
						currentUrl: to,

						// regardless of the direction of the history change
						// do the following
						either: function( isBack ) {
							var active = $.mobile.urlHistory.getActive();

							to = active.pageUrl;

							// make sure to set the role, transition and reversal
							// as most of this is lost by the domCache cleaning
							$.extend( changePageOptions, {
								role: active.role,
								transition: active.transition,
								reverse: isBack
							});
						}
					});
				}
			}

			//if to is defined, load it
			if ( to ) {
				// At this point, 'to' can be one of 3 things, a cached page element from
				// a history stack entry, an id, or site-relative/absolute URL. If 'to' is
				// an id, we need to resolve it against the documentBase, not the location.href,
				// since the hashchange could've been the result of a forward/backward navigation
				// that crosses from an external page/dialog to an internal page/dialog.
				to = ( typeof to === "string" && !path.isPath( to ) ) ? ( path.makeUrlAbsolute( '#' + to, documentBase ) ) : to;

				// If we're about to go to an initial URL that contains a reference to a non-existent
				// internal page, go to the first page instead. We know that the initial hash refers to a
				// non-existent page, because the initial hash did not end up in the initial urlHistory entry
				if ( to === path.makeUrlAbsolute( '#' + urlHistory.initialDst, documentBase ) &&
					urlHistory.stack.length && urlHistory.stack[0].url !== urlHistory.initialDst.replace( dialogHashKey, "" ) ) {
					to = $.mobile.firstPage;
				}
				$.mobile.changePage( to, changePageOptions );
			}	else {
				//there's no hash, go to the first page in the dom
				$.mobile.changePage( $.mobile.firstPage, changePageOptions );
			}
		};

		//hashchange event handler
		$window.bind( "hashchange", function( e, triggered ) {
			// Firefox auto-escapes the location.hash as for v13 but
			// leaves the href untouched
			$.mobile._handleHashChange( path.parseLocation().hash );
		});

		//set page min-heights to be device specific
		$( document ).bind( "pageshow", resetActivePageHeight );
		$( window ).bind( "throttledresize", resetActivePageHeight );

	});//navreadyDeferred done callback

})( jQuery );

(function( $, window ) {
	// For now, let's Monkeypatch this onto the end of $.mobile._registerInternalEvents
	// Scope self to pushStateHandler so we can reference it sanely within the
	// methods handed off as event handlers
	var	pushStateHandler = {},
		self = pushStateHandler,
		$win = $( window ),
		url = $.mobile.path.parseLocation(),
		mobileinitDeferred = $.Deferred(),
		domreadyDeferred = $.Deferred();

	$( document ).ready( $.proxy( domreadyDeferred, "resolve" ) );

	$( document ).one( "mobileinit", $.proxy( mobileinitDeferred, "resolve" ) );

	$.extend( pushStateHandler, {
		// TODO move to a path helper, this is rather common functionality
		initialFilePath: (function() {
			return url.pathname + url.search;
		})(),

		hashChangeTimeout: 200,

		hashChangeEnableTimer: undefined,

		initialHref: url.hrefNoHash,

		state: function() {
			return {
				// firefox auto decodes the url when using location.hash but not href
				hash: $.mobile.path.parseLocation().hash || "#" + self.initialFilePath,
				title: document.title,

				// persist across refresh
				initialHref: self.initialHref
			};
		},

		resetUIKeys: function( url ) {
			var dialog = $.mobile.dialogHashKey,
				subkey = "&" + $.mobile.subPageUrlKey,
				dialogIndex = url.indexOf( dialog );

			if ( dialogIndex > -1 ) {
				url = url.slice( 0, dialogIndex ) + "#" + url.slice( dialogIndex );
			} else if ( url.indexOf( subkey ) > -1 ) {
				url = url.split( subkey ).join( "#" + subkey );
			}

			return url;
		},

		// TODO sort out a single barrier to hashchange functionality
		nextHashChangePrevented: function( value ) {
			$.mobile.urlHistory.ignoreNextHashChange = value;
			self.onHashChangeDisabled = value;
		},

		// on hash change we want to clean up the url
		// NOTE this takes place *after* the vanilla navigation hash change
		// handling has taken place and set the state of the DOM
		onHashChange: function( e ) {
			// disable this hash change
			if ( self.onHashChangeDisabled ) {
				return;
			}

			var href, state,
				// firefox auto decodes the url when using location.hash but not href
				hash = $.mobile.path.parseLocation().hash,
				isPath = $.mobile.path.isPath( hash ),
				resolutionUrl = isPath ? $.mobile.path.getLocation() : $.mobile.getDocumentUrl();

			hash = isPath ? hash.replace( "#", "" ) : hash;


			// propulate the hash when its not available
			state = self.state();

			// make the hash abolute with the current href
			href = $.mobile.path.makeUrlAbsolute( hash, resolutionUrl );

			if ( isPath ) {
				href = self.resetUIKeys( href );
			}

			// replace the current url with the new href and store the state
			// Note that in some cases we might be replacing an url with the
			// same url. We do this anyways because we need to make sure that
			// all of our history entries have a state object associated with
			// them. This allows us to work around the case where $.mobile.back()
			// is called to transition from an external page to an embedded page.
			// In that particular case, a hashchange event is *NOT* generated by the browser.
			// Ensuring each history entry has a state object means that onPopState()
			// will always trigger our hashchange callback even when a hashchange event
			// is not fired.
			history.replaceState( state, document.title, href );
		},

		// on popstate (ie back or forward) we need to replace the hash that was there previously
		// cleaned up by the additional hash handling
		onPopState: function( e ) {
			var poppedState = e.originalEvent.state,
				fromHash, toHash, hashChanged;

			// if there's no state its not a popstate we care about, eg chrome's initial popstate
			if ( poppedState ) {
				// if we get two pop states in under this.hashChangeTimeout
				// make sure to clear any timer set for the previous change
				clearTimeout( self.hashChangeEnableTimer );

				// make sure to enable hash handling for the the _handleHashChange call
				self.nextHashChangePrevented( false );

				// change the page based on the hash in the popped state
				$.mobile._handleHashChange( poppedState.hash );

				// prevent any hashchange in the next self.hashChangeTimeout
				self.nextHashChangePrevented( true );

				// re-enable hash change handling after swallowing a possible hash
				// change event that comes on all popstates courtesy of browsers like Android
				self.hashChangeEnableTimer = setTimeout( function() {
					self.nextHashChangePrevented( false );
				}, self.hashChangeTimeout );
			}
		},

		init: function() {
			$win.bind( "hashchange", self.onHashChange );

			// Handle popstate events the occur through history changes
			$win.bind( "popstate", self.onPopState );

			// if there's no hash, we need to replacestate for returning to home
			if ( location.hash === "" ) {
				history.replaceState( self.state(), document.title, $.mobile.path.getLocation() );
			}
		}
	});

	// We need to init when "mobileinit", "domready", and "navready" have all happened
	$.when( domreadyDeferred, mobileinitDeferred, $.mobile.navreadyDeferred ).done(function() {
		if ( $.mobile.pushStateEnabled && $.support.pushState ) {
			pushStateHandler.init();
		}
	});
})( jQuery, this );

/*
* fallback transition for flip in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.flip = "fade";

})( jQuery, this );
/*
* fallback transition for flow in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.flow = "fade";

})( jQuery, this );
/*
* fallback transition for pop in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.pop = "fade";

})( jQuery, this );
/*
* fallback transition for slide in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

// Use the simultaneous transitions handler for slide transitions
$.mobile.transitionHandlers.slide = $.mobile.transitionHandlers.simultaneous;

// Set the slide transitions's fallback to "fade"
$.mobile.transitionFallbacks.slide = "fade";

})( jQuery, this );
/*
* fallback transition for slidedown in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.slidedown = "fade";

})( jQuery, this );
/*
* fallback transition for slidefade in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

// Set the slide transitions's fallback to "fade"
$.mobile.transitionFallbacks.slidefade = "fade";

})( jQuery, this );
/*
* fallback transition for slideup in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.slideup = "fade";

})( jQuery, this );
/*
* fallback transition for turn in non-3D supporting browsers (which tend to handle complex transitions poorly in general
*/

(function( $, window, undefined ) {

$.mobile.transitionFallbacks.turn = "fade";

})( jQuery, this );

(function( $, undefined ) {

$.mobile.page.prototype.options.degradeInputs = {
	color: false,
	date: false,
	datetime: false,
	"datetime-local": false,
	email: false,
	month: false,
	number: false,
	range: "number",
	search: "text",
	tel: false,
	time: false,
	url: false,
	week: false
};


//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {

	var page = $.mobile.closestPageData( $( e.target ) ), options;

	if ( !page ) {
		return;
	}

	options = page.options;

	// degrade inputs to avoid poorly implemented native functionality
	$( e.target ).find( "input" ).not( page.keepNativeSelector() ).each(function() {
		var $this = $( this ),
			type = this.getAttribute( "type" ),
			optType = options.degradeInputs[ type ] || "text";

		if ( options.degradeInputs[ type ] ) {
			var html = $( "<div>" ).html( $this.clone() ).html(),
				// In IE browsers, the type sometimes doesn't exist in the cloned markup, so we replace the closing tag instead
				hasType = html.indexOf( " type=" ) > -1,
				findstr = hasType ? /\s+type=["']?\w+['"]?/ : /\/?>/,
				repstr = " type=\"" + optType + "\" data-" + $.mobile.ns + "type=\"" + type + "\"" + ( hasType ? "" : ">" );

			$this.replaceWith( html.replace( findstr, repstr ) );
		}
	});

});

})( jQuery );

(function( $, window, undefined ) {

$.widget( "mobile.dialog", $.mobile.widget, {
	options: {
		closeBtnText: "Close",
		overlayTheme: "a",
		initSelector: ":jqmData(role='dialog')"
	},
	_create: function() {
		var self = this,
			$el = this.element,
			headerCloseButton = $( "<a href='#' data-" + $.mobile.ns + "icon='delete' data-" + $.mobile.ns + "iconpos='notext'>"+ this.options.closeBtnText + "</a>" ),
			dialogWrap = $( "<div/>", {
					"role" : "dialog",
					"class" : "ui-dialog-contain ui-corner-all ui-overlay-shadow"
				});

		$el.addClass( "ui-dialog ui-overlay-" + this.options.overlayTheme );

		// Class the markup for dialog styling
		// Set aria role
		$el
			.wrapInner( dialogWrap )
			.children()
				.find( ":jqmData(role='header')" )
					.prepend( headerCloseButton )
				.end()
				.children( ':first-child')
					.addClass( "ui-corner-top" )
				.end()
				.children( ":last-child" )
					.addClass( "ui-corner-bottom" );

		// this must be an anonymous function so that select menu dialogs can replace
		// the close method. This is a change from previously just defining data-rel=back
		// on the button and letting nav handle it
		//
		// Use click rather than vclick in order to prevent the possibility of unintentionally
		// reopening the dialog if the dialog opening item was directly under the close button.
		headerCloseButton.bind( "click", function() {
			self.close();
		});

		/* bind events
			- clicks and submits should use the closing transition that the dialog opened with
				unless a data-transition is specified on the link/form
			- if the click was on the close button, or the link has a data-rel="back" it'll go back in history naturally
		*/
		$el.bind( "vclick submit", function( event ) {
			var $target = $( event.target ).closest( event.type === "vclick" ? "a" : "form" ),
				active;

			if ( $target.length && !$target.jqmData( "transition" ) ) {

				active = $.mobile.urlHistory.getActive() || {};

				$target.attr( "data-" + $.mobile.ns + "transition", ( active.transition || $.mobile.defaultDialogTransition ) )
					.attr( "data-" + $.mobile.ns + "direction", "reverse" );
			}
		})
		.bind( "pagehide", function( e, ui ) {
			$( this ).find( "." + $.mobile.activeBtnClass ).not( ".ui-slider-bg" ).removeClass( $.mobile.activeBtnClass );
		})
		// Override the theme set by the page plugin on pageshow
		.bind( "pagebeforeshow", function() {
			self._isCloseable = true;
			if ( self.options.overlayTheme ) {
				self.element
					.page( "removeContainerBackground" )
					.page( "setContainerBackground", self.options.overlayTheme );
			}
		});
	},

	// Close method goes back in history
	close: function() {
		var dst;

		if ( this._isCloseable ) {
			this._isCloseable = false;
			if ( $.mobile.hashListeningEnabled ) {
				$.mobile.back();
			} else {
				dst = $.mobile.urlHistory.getPrev().url;
				if ( !$.mobile.path.isPath( dst ) ) {
					dst = $.mobile.path.makeUrlAbsolute( "#" + dst );
				}

				$.mobile.changePage( dst, { changeHash: false, fromHashChange: true } );
			}
		}
	}
});

//auto self-init widgets
$( document ).delegate( $.mobile.dialog.prototype.options.initSelector, "pagecreate", function() {
	$.mobile.dialog.prototype.enhance( this );
});

})( jQuery, this );

(function( $, undefined ) {

$.mobile.page.prototype.options.backBtnText  = "Back";
$.mobile.page.prototype.options.addBackBtn   = false;
$.mobile.page.prototype.options.backBtnTheme = null;
$.mobile.page.prototype.options.headerTheme  = "a";
$.mobile.page.prototype.options.footerTheme  = "a";
$.mobile.page.prototype.options.contentTheme = null;

// NOTE bind used to force this binding to run before the buttonMarkup binding
//      which expects .ui-footer top be applied in its gigantic selector
// TODO remove the buttonMarkup giant selector and move it to the various modules
//      on which it depends
$( document ).bind( "pagecreate", function( e ) {
	var $page = $( e.target ),
		o = $page.data( "page" ).options,
		pageRole = $page.jqmData( "role" ),
		pageTheme = o.theme;

	$( ":jqmData(role='header'), :jqmData(role='footer'), :jqmData(role='content')", $page )
		.jqmEnhanceable()
		.each(function() {

		var $this = $( this ),
			role = $this.jqmData( "role" ),
			theme = $this.jqmData( "theme" ),
			contentTheme = theme || o.contentTheme || ( pageRole === "dialog" && pageTheme ),
			$headeranchors,
			leftbtn,
			rightbtn,
			backBtn;

		$this.addClass( "ui-" + role );

		//apply theming and markup modifications to page,header,content,footer
		if ( role === "header" || role === "footer" ) {

			var thisTheme = theme || ( role === "header" ? o.headerTheme : o.footerTheme ) || pageTheme;

			$this
				//add theme class
				.addClass( "ui-bar-" + thisTheme )
				// Add ARIA role
				.attr( "role", role === "header" ? "banner" : "contentinfo" );

			if ( role === "header") {
				// Right,left buttons
				$headeranchors	= $this.children( "a, button" );
				leftbtn	= $headeranchors.hasClass( "ui-btn-left" );
				rightbtn = $headeranchors.hasClass( "ui-btn-right" );

				leftbtn = leftbtn || $headeranchors.eq( 0 ).not( ".ui-btn-right" ).addClass( "ui-btn-left" ).length;

				rightbtn = rightbtn || $headeranchors.eq( 1 ).addClass( "ui-btn-right" ).length;
			}

			// Auto-add back btn on pages beyond first view
			if ( o.addBackBtn &&
				role === "header" &&
				$( ".ui-page" ).length > 1 &&
				$page.jqmData( "url" ) !== $.mobile.path.stripHash( location.hash ) &&
				!leftbtn ) {

				backBtn = $( "<a href='javascript:void(0);' class='ui-btn-left' data-"+ $.mobile.ns +"rel='back' data-"+ $.mobile.ns +"icon='arrow-l'>"+ o.backBtnText +"</a>" )
					// If theme is provided, override default inheritance
					.attr( "data-"+ $.mobile.ns +"theme", o.backBtnTheme || thisTheme )
					.prependTo( $this );
			}

			// Page title
			$this.children( "h1, h2, h3, h4, h5, h6" )
				.addClass( "ui-title" )
				// Regardless of h element number in src, it becomes h1 for the enhanced page
				.attr({
					"role": "heading",
					"aria-level": "1"
				});

		} else if ( role === "content" ) {
			if ( contentTheme ) {
				$this.addClass( "ui-body-" + ( contentTheme ) );
			}

			// Add ARIA role
			$this.attr( "role", "main" );
		}
	});
});

})( jQuery );

(function( $, undefined ) {

// filter function removes whitespace between label and form element so we can use inline-block (nodeType 3 = text)
$.fn.fieldcontain = function( options ) {
	return this
		.addClass( "ui-field-contain ui-body ui-br" )
		.contents().filter( function() {
			return ( this.nodeType === 3 && !/\S/.test( this.nodeValue ) );
		}).remove();
};

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$( ":jqmData(role='fieldcontain')", e.target ).jqmEnhanceable().fieldcontain();
});

})( jQuery );

(function( $, undefined ) {

$.fn.grid = function( options ) {
	return this.each(function() {

		var $this = $( this ),
			o = $.extend({
				grid: null
			}, options ),
			$kids = $this.children(),
			gridCols = { solo:1, a:2, b:3, c:4, d:5 },
			grid = o.grid,
			iterator;

			if ( !grid ) {
				if ( $kids.length <= 5 ) {
					for ( var letter in gridCols ) {
						if ( gridCols[ letter ] === $kids.length ) {
							grid = letter;
						}
					}
				} else {
					grid = "a";
					$this.addClass( "ui-grid-duo" );
				}
			}
			iterator = gridCols[grid];

		$this.addClass( "ui-grid-" + grid );

		$kids.filter( ":nth-child(" + iterator + "n+1)" ).addClass( "ui-block-a" );

		if ( iterator > 1 ) {
			$kids.filter( ":nth-child(" + iterator + "n+2)" ).addClass( "ui-block-b" );
		}
		if ( iterator > 2 ) {
			$kids.filter( ":nth-child(" + iterator + "n+3)" ).addClass( "ui-block-c" );
		}
		if ( iterator > 3 ) {
			$kids.filter( ":nth-child(" + iterator + "n+4)" ).addClass( "ui-block-d" );
		}
		if ( iterator > 4 ) {
			$kids.filter( ":nth-child(" + iterator + "n+5)" ).addClass( "ui-block-e" );
		}
	});
};
})( jQuery );

(function( $, undefined ) {

$( document ).bind( "pagecreate create", function( e ) {
	$( ":jqmData(role='nojs')", e.target ).addClass( "ui-nojs" );
	
});

})( jQuery );

(function( $, undefined ) {

$.fn.buttonMarkup = function( options ) {
	var $workingSet = this,
		mapToDataAttr = function( key, value ) {
			e.setAttribute( "data-" + $.mobile.ns + key, value );
			el.jqmData( key, value );
		};

	// Enforce options to be of type string
	options = ( options && ( $.type( options ) === "object" ) )? options : {};
	for ( var i = 0; i < $workingSet.length; i++ ) {
		var el = $workingSet.eq( i ),
			e = el[ 0 ],
			o = $.extend( {}, $.fn.buttonMarkup.defaults, {
				icon:       options.icon       !== undefined ? options.icon       : el.jqmData( "icon" ),
				iconpos:    options.iconpos    !== undefined ? options.iconpos    : el.jqmData( "iconpos" ),
				theme:      options.theme      !== undefined ? options.theme      : el.jqmData( "theme" ) || $.mobile.getInheritedTheme( el, "c" ),
				inline:     options.inline     !== undefined ? options.inline     : el.jqmData( "inline" ),
				shadow:     options.shadow     !== undefined ? options.shadow     : el.jqmData( "shadow" ),
				corners:    options.corners    !== undefined ? options.corners    : el.jqmData( "corners" ),
				iconshadow: options.iconshadow !== undefined ? options.iconshadow : el.jqmData( "iconshadow" ),
				mini:       options.mini       !== undefined ? options.mini       : el.jqmData( "mini" )
			}, options ),

			// Classes Defined
			innerClass = "ui-btn-inner",
			textClass = "ui-btn-text",
			buttonClass, iconClass,
			// Button inner markup
			buttonInner,
			buttonText,
			buttonIcon,
			buttonElements;

		$.each( o, mapToDataAttr );

		if ( el.jqmData( "rel" ) === "popup" && el.attr( "href" ) ) {
			e.setAttribute( "aria-haspopup", true );
			e.setAttribute( "aria-owns", e.getAttribute( "href" ) );
		}

		// Check if this element is already enhanced
		buttonElements = $.data( ( ( e.tagName === "INPUT" || e.tagName === "BUTTON" ) ? e.parentNode : e ), "buttonElements" );

		if ( buttonElements ) {
			e = buttonElements.outer;
			el = $( e );
			buttonInner = buttonElements.inner;
			buttonText = buttonElements.text;
			// We will recreate this icon below
			$( buttonElements.icon ).remove();
			buttonElements.icon = null;
		}
		else {
			buttonInner = document.createElement( o.wrapperEls );
			buttonText = document.createElement( o.wrapperEls );
		}
		buttonIcon = o.icon ? document.createElement( "span" ) : null;

		if ( attachEvents && !buttonElements ) {
			attachEvents();
		}

		// if not, try to find closest theme container
		if ( !o.theme ) {
			o.theme = $.mobile.getInheritedTheme( el, "c" );
		}

		buttonClass = "ui-btn ui-btn-up-" + o.theme;
		buttonClass += o.shadow ? " ui-shadow" : "";
		buttonClass += o.corners ? " ui-btn-corner-all" : "";

		if ( o.mini !== undefined ) {
			// Used to control styling in headers/footers, where buttons default to `mini` style.
			buttonClass += o.mini === true ? " ui-mini" : " ui-fullsize";
		}

		if ( o.inline !== undefined ) {
			// Used to control styling in headers/footers, where buttons default to `inline` style.
			buttonClass += o.inline === true ? " ui-btn-inline" : " ui-btn-block";
		}

		if ( o.icon ) {
			o.icon = "ui-icon-" + o.icon;
			o.iconpos = o.iconpos || "left";

			iconClass = "ui-icon " + o.icon;

			if ( o.iconshadow ) {
				iconClass += " ui-icon-shadow";
			}
		}

		if ( o.iconpos ) {
			buttonClass += " ui-btn-icon-" + o.iconpos;

			if ( o.iconpos === "notext" && !el.attr( "title" ) ) {
				el.attr( "title", el.getEncodedText() );
			}
		}

		innerClass += o.corners ? " ui-btn-corner-all" : "";

		if ( o.iconpos && o.iconpos === "notext" && !el.attr( "title" ) ) {
			el.attr( "title", el.getEncodedText() );
		}

		if ( buttonElements ) {
			el.removeClass( buttonElements.bcls || "" );
		}
		el.removeClass( "ui-link" ).addClass( buttonClass );

		buttonInner.className = innerClass;

		buttonText.className = textClass;
		if ( !buttonElements ) {
			buttonInner.appendChild( buttonText );
		}
		if ( buttonIcon ) {
			buttonIcon.className = iconClass;
			if ( !( buttonElements && buttonElements.icon ) ) {
				buttonIcon.innerHTML = "&#160;";
				buttonInner.appendChild( buttonIcon );
			}
		}

		while ( e.firstChild && !buttonElements ) {
			buttonText.appendChild( e.firstChild );
		}

		if ( !buttonElements ) {
			e.appendChild( buttonInner );
		}

		// Assign a structure containing the elements of this button to the elements of this button. This
		// will allow us to recognize this as an already-enhanced button in future calls to buttonMarkup().
		buttonElements = {
			bcls  : buttonClass,
			outer : e,
			inner : buttonInner,
			text  : buttonText,
			icon  : buttonIcon
		};

		$.data( e,           'buttonElements', buttonElements );
		$.data( buttonInner, 'buttonElements', buttonElements );
		$.data( buttonText,  'buttonElements', buttonElements );
		if ( buttonIcon ) {
			$.data( buttonIcon, 'buttonElements', buttonElements );
		}
	}

	return this;
};

$.fn.buttonMarkup.defaults = {
	corners: true,
	shadow: true,
	iconshadow: true,
	wrapperEls: "span"
};

function closestEnabledButton( element ) {
    var cname;

    while ( element ) {
		// Note that we check for typeof className below because the element we
		// handed could be in an SVG DOM where className on SVG elements is defined to
		// be of a different type (SVGAnimatedString). We only operate on HTML DOM
		// elements, so we look for plain "string".
        cname = ( typeof element.className === 'string' ) && ( element.className + ' ' );
        if ( cname && cname.indexOf( "ui-btn " ) > -1 && cname.indexOf( "ui-disabled " ) < 0 ) {
            break;
        }

        element = element.parentNode;
    }

    return element;
}

var attachEvents = function() {
	var hoverDelay = $.mobile.buttonMarkup.hoverDelay, hov, foc;

	$( document ).bind( {
		"vmousedown vmousecancel vmouseup vmouseover vmouseout focus blur scrollstart": function( event ) {
			var theme,
				$btn = $( closestEnabledButton( event.target ) ),
				isTouchEvent = event.originalEvent && /^touch/.test( event.originalEvent.type ),
				evt = event.type;

			if ( $btn.length ) {
				theme = $btn.attr( "data-" + $.mobile.ns + "theme" );

				if ( evt === "vmousedown" ) {
					if ( isTouchEvent ) {
						// Use a short delay to determine if the user is scrolling before highlighting
						hov = setTimeout( function() {
							$btn.removeClass( "ui-btn-up-" + theme ).addClass( "ui-btn-down-" + theme );
						}, hoverDelay );
					} else {
						$btn.removeClass( "ui-btn-up-" + theme ).addClass( "ui-btn-down-" + theme );
					}
				} else if ( evt === "vmousecancel" || evt === "vmouseup" ) {
					$btn.removeClass( "ui-btn-down-" + theme ).addClass( "ui-btn-up-" + theme );
				} else if ( evt === "vmouseover" || evt === "focus" ) {
					if ( isTouchEvent ) {
						// Use a short delay to determine if the user is scrolling before highlighting
						foc = setTimeout( function() {
							$btn.removeClass( "ui-btn-up-" + theme ).addClass( "ui-btn-hover-" + theme );
						}, hoverDelay );
					} else {
						$btn.removeClass( "ui-btn-up-" + theme ).addClass( "ui-btn-hover-" + theme );
					}
				} else if ( evt === "vmouseout" || evt === "blur" || evt === "scrollstart" ) {
					$btn.removeClass( "ui-btn-hover-" + theme  + " ui-btn-down-" + theme ).addClass( "ui-btn-up-" + theme );
					if ( hov ) {
						clearTimeout( hov );
					}
					if ( foc ) {
						clearTimeout( foc );
					}
				}
			}
		},
		"focusin focus": function( event ) {
			$( closestEnabledButton( event.target ) ).addClass( $.mobile.focusClass );
		},
		"focusout blur": function( event ) {
			$( closestEnabledButton( event.target ) ).removeClass( $.mobile.focusClass );
		}
	});

	attachEvents = null;
};

//links in bars, or those with  data-role become buttons
//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {

	$( ":jqmData(role='button'), .ui-bar > a, .ui-header > a, .ui-footer > a, .ui-bar > :jqmData(role='controlgroup') > a", e.target )
		.jqmEnhanceable()
		.not( "button, input, .ui-btn, :jqmData(role='none'), :jqmData(role='nojs')" )
		.buttonMarkup();
});

})( jQuery );


(function( $, undefined ) {

$.widget( "mobile.collapsible", $.mobile.widget, {
	options: {
		expandCueText: " click to expand contents",
		collapseCueText: " click to collapse contents",
		collapsed: true,
		heading: "h1,h2,h3,h4,h5,h6,legend",
		theme: null,
		contentTheme: null,
		inset: true,
		mini: false,
		initSelector: ":jqmData(role='collapsible')"
	},
	_create: function() {

		var $el = this.element,
			o = this.options,
			collapsible = $el.addClass( "ui-collapsible" ),
			collapsibleHeading = $el.children( o.heading ).first(),
			collapsedIcon = $el.jqmData( "collapsed-icon" ) || o.collapsedIcon,
			expandedIcon = $el.jqmData( "expanded-icon" ) || o.expandedIcon,
			collapsibleContent = collapsible.wrapInner( "<div class='ui-collapsible-content'></div>" ).children( ".ui-collapsible-content" ),
			collapsibleSet = $el.closest( ":jqmData(role='collapsible-set')" ).addClass( "ui-collapsible-set" );

		// Replace collapsibleHeading if it's a legend
		if ( collapsibleHeading.is( "legend" ) ) {
			collapsibleHeading = $( "<div role='heading'>"+ collapsibleHeading.html() +"</div>" ).insertBefore( collapsibleHeading );
			collapsibleHeading.next().remove();
		}

		// If we are in a collapsible set
		if ( collapsibleSet.length ) {
			// Inherit the theme from collapsible-set
			if ( !o.theme ) {
				o.theme = collapsibleSet.jqmData( "theme" ) || $.mobile.getInheritedTheme( collapsibleSet, "c" );
			}
			// Inherit the content-theme from collapsible-set
			if ( !o.contentTheme ) {
				o.contentTheme = collapsibleSet.jqmData( "content-theme" );
			}

			// Get the preference for collapsed icon in the set
			if ( !o.collapsedIcon ) {
				o.collapsedIcon = collapsibleSet.jqmData( "collapsed-icon" );
			}
			// Get the preference for expanded icon in the set
			if ( !o.expandedIcon ) {
				o.expandedIcon = collapsibleSet.jqmData( "expanded-icon" );
			}
			// Gets the preference icon position in the set
			if ( !o.iconPos ) {
				o.iconPos = collapsibleSet.jqmData( "iconpos" );
			}
			// Inherit the preference for inset from collapsible-set or set the default value to ensure equalty within a set
			if ( collapsibleSet.jqmData( "inset" ) !== undefined ) {
				o.inset = collapsibleSet.jqmData( "inset" );
			} else {
				o.inset = true;
			}
			// Gets the preference for mini in the set
			if ( !o.mini ) {
				o.mini = collapsibleSet.jqmData( "mini" );
			}
		} else {
			// get inherited theme if not a set and no theme has been set
			if ( !o.theme ) {
				o.theme = $.mobile.getInheritedTheme( $el, "c" );
			}
		}
		
		if ( !!o.inset ) {
			collapsible.addClass( "ui-collapsible-inset" );
		}
		
		collapsibleContent.addClass( ( o.contentTheme ) ? ( "ui-body-" + o.contentTheme ) : "");

		collapsedIcon = $el.jqmData( "collapsed-icon" ) || o.collapsedIcon || "plus";
		expandedIcon = $el.jqmData( "expanded-icon" ) || o.expandedIcon || "minus";

		collapsibleHeading
			//drop heading in before content
			.insertBefore( collapsibleContent )
			//modify markup & attributes
			.addClass( "ui-collapsible-heading" )
			.append( "<span class='ui-collapsible-heading-status'></span>" )
			.wrapInner( "<a href='#' class='ui-collapsible-heading-toggle'></a>" )
			.find( "a" )
				.first()
				.buttonMarkup({
					shadow: false,
					corners: false,
					iconpos: $el.jqmData( "iconpos" ) || o.iconPos || "left",
					icon: collapsedIcon,
					mini: o.mini,
					theme: o.theme
				});

		if ( !!o.inset ) {				
			collapsibleHeading
				.find( "a" ).first().add( ".ui-btn-inner", $el )
					.addClass( "ui-corner-top ui-corner-bottom" );
		}

		//events
		collapsible
			.bind( "expand collapse", function( event ) {
				if ( !event.isDefaultPrevented() ) {
					var $this = $( this ),
						isCollapse = ( event.type === "collapse" ),
						contentTheme = o.contentTheme;

					event.preventDefault();

					collapsibleHeading
						.toggleClass( "ui-collapsible-heading-collapsed", isCollapse )
						.find( ".ui-collapsible-heading-status" )
							.text( isCollapse ? o.expandCueText : o.collapseCueText )
						.end()
						.find( ".ui-icon" )
							.toggleClass( "ui-icon-" + expandedIcon, !isCollapse )
							// logic or cause same icon for expanded/collapsed state would remove the ui-icon-class
							.toggleClass( "ui-icon-" + collapsedIcon, ( isCollapse || expandedIcon === collapsedIcon ) )
						.end()
						.find( "a" ).first().removeClass( $.mobile.activeBtnClass );

					$this.toggleClass( "ui-collapsible-collapsed", isCollapse );
					collapsibleContent.toggleClass( "ui-collapsible-content-collapsed", isCollapse ).attr( "aria-hidden", isCollapse );

					if ( contentTheme && !!o.inset && ( !collapsibleSet.length || collapsible.jqmData( "collapsible-last" ) ) ) {
						collapsibleHeading
							.find( "a" ).first().add( collapsibleHeading.find( ".ui-btn-inner" ) )
							.toggleClass( "ui-corner-bottom", isCollapse );
						collapsibleContent.toggleClass( "ui-corner-bottom", !isCollapse );
					}
					collapsibleContent.trigger( "updatelayout" );
				}
			})
			.trigger( o.collapsed ? "collapse" : "expand" );

		collapsibleHeading
			.bind( "tap", function( event ) {
				collapsibleHeading.find( "a" ).first().addClass( $.mobile.activeBtnClass );
			})
			.bind( "click", function( event ) {

				var type = collapsibleHeading.is( ".ui-collapsible-heading-collapsed" ) ? "expand" : "collapse";

				collapsible.trigger( type );

				event.preventDefault();
				event.stopPropagation();
			});
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.collapsible.prototype.enhanceWithin( e.target );
});

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.collapsibleset", $.mobile.widget, {
	options: {
		initSelector: ":jqmData(role='collapsible-set')"
	},
	_create: function() {
		var $el = this.element.addClass( "ui-collapsible-set" ),
			o = this.options;

		// Inherit the theme from collapsible-set
		if ( !o.theme ) {
			o.theme = $.mobile.getInheritedTheme( $el, "c" );
		}
		// Inherit the content-theme from collapsible-set
		if ( !o.contentTheme ) {
			o.contentTheme = $el.jqmData( "content-theme" );
		}

		if ( $el.jqmData( "inset" ) !== undefined ) {
			o.inset = $el.jqmData( "inset" );
		}
		o.inset = o.inset !== undefined ? o.inset : true;

		// Initialize the collapsible set if it's not already initialized
		if ( !$el.jqmData( "collapsiblebound" ) ) {
			$el
				.jqmData( "collapsiblebound", true )
				.bind( "expand collapse", function( event ) {
					var isCollapse = ( event.type === "collapse" ),
						collapsible = $( event.target ).closest( ".ui-collapsible" ),
						widget = collapsible.data( "collapsible" );
					if ( collapsible.jqmData( "collapsible-last" ) && !!o.inset ) {
						collapsible.find( ".ui-collapsible-heading" ).first()
							.find( "a" ).first()
							.toggleClass( "ui-corner-bottom", isCollapse )
							.find( ".ui-btn-inner" )
							.toggleClass( "ui-corner-bottom", isCollapse );
						collapsible.find( ".ui-collapsible-content" ).toggleClass( "ui-corner-bottom", !isCollapse );
					}
				})
				.bind( "expand", function( event ) {
					var closestCollapsible = $( event.target )
						.closest( ".ui-collapsible" );
					if ( closestCollapsible.parent().is( ":jqmData(role='collapsible-set')" ) ) {
						closestCollapsible
							.siblings( ".ui-collapsible" )
							.trigger( "collapse" );
					}
				});
		}
	},

	_init: function() {
		var $el = this.element,
			collapsiblesInSet = $el.children( ":jqmData(role='collapsible')" ),
			expanded = collapsiblesInSet.filter( ":jqmData(collapsed='false')" );
		this.refresh();

		// Because the corners are handled by the collapsible itself and the default state is collapsed
		// That was causing https://github.com/jquery/jquery-mobile/issues/4116
		expanded.trigger( "expand" );
	},

	refresh: function() {
		var $el = this.element,
			o = this.options,
			collapsiblesInSet = $el.children( ":jqmData(role='collapsible')" );

		$.mobile.collapsible.prototype.enhance( collapsiblesInSet.not( ".ui-collapsible" ) );

		// clean up borders
		if ( !!o.inset ) {
			collapsiblesInSet.each(function() {
				$( this ).jqmRemoveData( "collapsible-last" )
					.find( ".ui-collapsible-heading" )
					.find( "a" ).first()
					.removeClass( "ui-corner-top ui-corner-bottom" )
					.find( ".ui-btn-inner" )
					.removeClass( "ui-corner-top ui-corner-bottom" );
			});

			collapsiblesInSet.first()
				.find( "a" )
					.first()
					.addClass( "ui-corner-top" )
					.find( ".ui-btn-inner" )
						.addClass( "ui-corner-top" );
	
			collapsiblesInSet.last()
				.jqmData( "collapsible-last", true )
				.find( "a" )
					.first()
					.addClass( "ui-corner-bottom" )
					.find( ".ui-btn-inner" )
						.addClass( "ui-corner-bottom" );
		}
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.collapsibleset.prototype.enhanceWithin( e.target );
});

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.navbar", $.mobile.widget, {
	options: {
		iconpos: "top",
		grid: null,
		initSelector: ":jqmData(role='navbar')"
	},

	_create: function() {

		var $navbar = this.element,
			$navbtns = $navbar.find( "a" ),
			iconpos = $navbtns.filter( ":jqmData(icon)" ).length ?
									this.options.iconpos : undefined;

		$navbar.addClass( "ui-navbar ui-mini" )
			.attr( "role", "navigation" )
			.find( "ul" )
			.jqmEnhanceable()
			.grid({ grid: this.options.grid });

		$navbtns.buttonMarkup({
			corners:	false,
			shadow:		false,
			inline:     true,
			iconpos:	iconpos
		});

		$navbar.delegate( "a", "vclick", function( event ) {
			if ( !$(event.target).hasClass( "ui-disabled" ) ) {
				$navbtns.removeClass( $.mobile.activeBtnClass );
				$( this ).addClass( $.mobile.activeBtnClass );
			}
		});

		// Buttons in the navbar with ui-state-persist class should regain their active state before page show
		$navbar.closest( ".ui-page" ).bind( "pagebeforeshow", function() {
			$navbtns.filter( ".ui-state-persist" ).addClass( $.mobile.activeBtnClass );
		});
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.navbar.prototype.enhanceWithin( e.target );
});

})( jQuery );

(function( $, undefined ) {

//Keeps track of the number of lists per page UID
//This allows support for multiple nested list in the same page
//https://github.com/jquery/jquery-mobile/issues/1617
var listCountPerPage = {};

$.widget( "mobile.listview", $.mobile.widget, {

	options: {
		theme: null,
		countTheme: "c",
		headerTheme: "b",
		dividerTheme: "b",
		splitIcon: "arrow-r",
		splitTheme: "b",
		inset: false,
		initSelector: ":jqmData(role='listview')"
	},

	_create: function() {
		var t = this,
			listviewClasses = "";

		listviewClasses += t.options.inset ? " ui-listview-inset ui-corner-all ui-shadow " : "";

		// create listview markup
		t.element.addClass(function( i, orig ) {
			return orig + " ui-listview " + listviewClasses;
		});

		t.refresh( true );
	},

	_removeCorners: function( li, which ) {
		var top = "ui-corner-top ui-corner-tr ui-corner-tl",
			bot = "ui-corner-bottom ui-corner-br ui-corner-bl";

		li = li.add( li.find( ".ui-btn-inner, .ui-li-link-alt, .ui-li-thumb" ) );

		if ( which === "top" ) {
			li.removeClass( top );
		} else if ( which === "bottom" ) {
			li.removeClass( bot );
		} else {
			li.removeClass( top + " " + bot );
		}
	},

	_refreshCorners: function( create ) {
		var $li,
			$visibleli,
			$topli,
			$bottomli;

		$li = this.element.children( "li" );
		// At create time and when autodividers calls refresh the li are not visible yet so we need to rely on .ui-screen-hidden
		$visibleli = create || $li.filter( ":visible" ).length === 0 ? $li.not( ".ui-screen-hidden" ) : $li.filter( ":visible" );

		// ui-li-last is used for setting border-bottom on the last li		
		$li.filter( ".ui-li-last" ).removeClass( "ui-li-last" );
					
		if ( this.options.inset ) {
			this._removeCorners( $li );

			// Select the first visible li element
			$topli = $visibleli.first()
				.addClass( "ui-corner-top" );

			$topli.add( $topli.find( ".ui-btn-inner" )
				.not( ".ui-li-link-alt span:first-child" ) )
					.addClass( "ui-corner-top" )
				.end()
				.find( ".ui-li-link-alt, .ui-li-link-alt span:first-child" )
					.addClass( "ui-corner-tr" )
				.end()
				.find( ".ui-li-thumb" )
					.not( ".ui-li-icon" )
					.addClass( "ui-corner-tl" );

			// Select the last visible li element
			$bottomli = $visibleli.last()
				.addClass( "ui-corner-bottom ui-li-last" );

			$bottomli.add( $bottomli.find( ".ui-btn-inner" ) )
				.find( ".ui-li-link-alt" )
					.addClass( "ui-corner-br" )
				.end()
				.find( ".ui-li-thumb" )
					.not( ".ui-li-icon" )
					.addClass( "ui-corner-bl" );
		} else {
			$visibleli.last().addClass( "ui-li-last" );
		}
		if ( !create ) {
			this.element.trigger( "updatelayout" );
		}
	},

	// This is a generic utility method for finding the first
	// node with a given nodeName. It uses basic DOM traversal
	// to be fast and is meant to be a substitute for simple
	// $.fn.closest() and $.fn.children() calls on a single
	// element. Note that callers must pass both the lowerCase
	// and upperCase version of the nodeName they are looking for.
	// The main reason for this is that this function will be
	// called many times and we want to avoid having to lowercase
	// the nodeName from the element every time to ensure we have
	// a match. Note that this function lives here for now, but may
	// be moved into $.mobile if other components need a similar method.
	_findFirstElementByTagName: function( ele, nextProp, lcName, ucName ) {
		var dict = {};
		dict[ lcName ] = dict[ ucName ] = true;
		while ( ele ) {
			if ( dict[ ele.nodeName ] ) {
				return ele;
			}
			ele = ele[ nextProp ];
		}
		return null;
	},
	_getChildrenByTagName: function( ele, lcName, ucName ) {
		var results = [],
			dict = {};
		dict[ lcName ] = dict[ ucName ] = true;
		ele = ele.firstChild;
		while ( ele ) {
			if ( dict[ ele.nodeName ] ) {
				results.push( ele );
			}
			ele = ele.nextSibling;
		}
		return $( results );
	},

	_addThumbClasses: function( containers ) {
		var i, img, len = containers.length;
		for ( i = 0; i < len; i++ ) {
			img = $( this._findFirstElementByTagName( containers[ i ].firstChild, "nextSibling", "img", "IMG" ) );
			if ( img.length ) {
				img.addClass( "ui-li-thumb" );
				$( this._findFirstElementByTagName( img[ 0 ].parentNode, "parentNode", "li", "LI" ) ).addClass( img.is( ".ui-li-icon" ) ? "ui-li-has-icon" : "ui-li-has-thumb" );
			}
		}
	},

	refresh: function( create ) {
		this.parentPage = this.element.closest( ".ui-page" );
		this._createSubPages();

		var o = this.options,
			$list = this.element,
			self = this,
			dividertheme = $list.jqmData( "dividertheme" ) || o.dividerTheme,
			listsplittheme = $list.jqmData( "splittheme" ),
			listspliticon = $list.jqmData( "spliticon" ),
			li = this._getChildrenByTagName( $list[ 0 ], "li", "LI" ),
			ol = !!$.nodeName( $list[ 0 ], "ol" ),
			jsCount = !$.support.cssPseudoElement,
			start = $list.attr( "start" ),
			itemClassDict = {},
			item, itemClass, itemTheme,
			a, last, splittheme, counter, startCount, newStartCount, countParent, icon, imgParents, img, linkIcon;

		if ( ol && jsCount ) {
			$list.find( ".ui-li-dec" ).remove();
		}

		if ( ol ) {	
			// Check if a start attribute has been set while taking a value of 0 into account
			if ( start || start === 0 ) {
				if ( !jsCount ) {
					startCount = parseFloat( start ) - 1;
					$list.css( "counter-reset", "listnumbering " + startCount );
				} else {
					counter = parseFloat( start );
				}
			} else if ( jsCount ) {
					counter = 1;
			}	
		}

		if ( !o.theme ) {
			o.theme = $.mobile.getInheritedTheme( this.element, "c" );
		}

		for ( var pos = 0, numli = li.length; pos < numli; pos++ ) {
			item = li.eq( pos );
			itemClass = "ui-li";

			// If we're creating the element, we update it regardless
			if ( create || !item.hasClass( "ui-li" ) ) {
				itemTheme = item.jqmData( "theme" ) || o.theme;
				a = this._getChildrenByTagName( item[ 0 ], "a", "A" );
				var isDivider = ( item.jqmData( "role" ) === "list-divider" );

				if ( a.length && !isDivider ) {
					icon = item.jqmData( "icon" );

					item.buttonMarkup({
						wrapperEls: "div",
						shadow: false,
						corners: false,
						iconpos: "right",
						icon: a.length > 1 || icon === false ? false : icon || "arrow-r",
						theme: itemTheme
					});

					if ( ( icon !== false ) && ( a.length === 1 ) ) {
						item.addClass( "ui-li-has-arrow" );
					}

					a.first().removeClass( "ui-link" ).addClass( "ui-link-inherit" );

					if ( a.length > 1 ) {
						itemClass += " ui-li-has-alt";

						last = a.last();
						splittheme = listsplittheme || last.jqmData( "theme" ) || o.splitTheme;
						linkIcon = last.jqmData( "icon" );

						last.appendTo( item )
							.attr( "title", last.getEncodedText() )
							.addClass( "ui-li-link-alt" )
							.empty()
							.buttonMarkup({
								shadow: false,
								corners: false,
								theme: itemTheme,
								icon: false,
								iconpos: "notext"
							})
							.find( ".ui-btn-inner" )
								.append(
									$( document.createElement( "span" ) ).buttonMarkup({
										shadow: true,
										corners: true,
										theme: splittheme,
										iconpos: "notext",
										// link icon overrides list item icon overrides ul element overrides options
										icon: linkIcon || icon || listspliticon || o.splitIcon
									})
								);
					}
				} else if ( isDivider ) {

					itemClass += " ui-li-divider ui-bar-" + dividertheme;
					item.attr( "role", "heading" );

					if ( ol ) {	
						//reset counter when a divider heading is encountered
						if ( start || start === 0 ) {
							if ( !jsCount ) {
								newStartCount = parseFloat( start ) - 1;
								item.css( "counter-reset", "listnumbering " + newStartCount );
							} else {
								counter = parseFloat( start );
							}
						} else if ( jsCount ) {
								counter = 1;
						}	
					}
				
				} else {
					itemClass += " ui-li-static ui-btn-up-" + itemTheme;
				}
			}

			if ( ol && jsCount && itemClass.indexOf( "ui-li-divider" ) < 0 ) {
				countParent = itemClass.indexOf( "ui-li-static" ) > 0 ? item : item.find( ".ui-link-inherit" );

				countParent.addClass( "ui-li-jsnumbering" )
					.prepend( "<span class='ui-li-dec'>" + ( counter++ ) + ". </span>" );
			}

			// Instead of setting item class directly on the list item and its
			// btn-inner at this point in time, push the item into a dictionary
			// that tells us what class to set on it so we can do this after this
			// processing loop is finished.

			if ( !itemClassDict[ itemClass ] ) {
				itemClassDict[ itemClass ] = [];
			}

			itemClassDict[ itemClass ].push( item[ 0 ] );
		}

		// Set the appropriate listview item classes on each list item
		// and their btn-inner elements. The main reason we didn't do this
		// in the for-loop above is because we can eliminate per-item function overhead
		// by calling addClass() and children() once or twice afterwards. This
		// can give us a significant boost on platforms like WP7.5.

		for ( itemClass in itemClassDict ) {
			$( itemClassDict[ itemClass ] ).addClass( itemClass ).children( ".ui-btn-inner" ).addClass( itemClass );
		}

		$list.find( "h1, h2, h3, h4, h5, h6" ).addClass( "ui-li-heading" )
			.end()

			.find( "p, dl" ).addClass( "ui-li-desc" )
			.end()

			.find( ".ui-li-aside" ).each(function() {
					var $this = $( this );
					$this.prependTo( $this.parent() ); //shift aside to front for css float
				})
			.end()

			.find( ".ui-li-count" ).each(function() {
					$( this ).closest( "li" ).addClass( "ui-li-has-count" );
				}).addClass( "ui-btn-up-" + ( $list.jqmData( "counttheme" ) || this.options.countTheme) + " ui-btn-corner-all" );

		// The idea here is to look at the first image in the list item
		// itself, and any .ui-link-inherit element it may contain, so we
		// can place the appropriate classes on the image and list item.
		// Note that we used to use something like:
		//
		//    li.find(">img:eq(0), .ui-link-inherit>img:eq(0)").each( ... );
		//
		// But executing a find() like that on Windows Phone 7.5 took a
		// really long time. Walking things manually with the code below
		// allows the 400 listview item page to load in about 3 seconds as
		// opposed to 30 seconds.

		this._addThumbClasses( li );
		this._addThumbClasses( $list.find( ".ui-link-inherit" ) );

		this._refreshCorners( create );

    // autodividers binds to this to redraw dividers after the listview refresh
		this._trigger( "afterrefresh" );
	},

	//create a string for ID/subpage url creation
	_idStringEscape: function( str ) {
		return str.replace(/[^a-zA-Z0-9]/g, '-');
	},

	_createSubPages: function() {
		var parentList = this.element,
			parentPage = parentList.closest( ".ui-page" ),
			parentUrl = parentPage.jqmData( "url" ),
			parentId = parentUrl || parentPage[ 0 ][ $.expando ],
			parentListId = parentList.attr( "id" ),
			o = this.options,
			dns = "data-" + $.mobile.ns,
			self = this,
			persistentFooterID = parentPage.find( ":jqmData(role='footer')" ).jqmData( "id" ),
			hasSubPages;

		if ( typeof listCountPerPage[ parentId ] === "undefined" ) {
			listCountPerPage[ parentId ] = -1;
		}

		parentListId = parentListId || ++listCountPerPage[ parentId ];

		$( parentList.find( "li>ul, li>ol" ).toArray().reverse() ).each(function( i ) {
			var self = this,
				list = $( this ),
				listId = list.attr( "id" ) || parentListId + "-" + i,
				parent = list.parent(),
				nodeElsFull = $( list.prevAll().toArray().reverse() ),
				nodeEls = nodeElsFull.length ? nodeElsFull : $( "<span>" + $.trim(parent.contents()[ 0 ].nodeValue) + "</span>" ),
				title = nodeEls.first().getEncodedText(),//url limits to first 30 chars of text
				id = ( parentUrl || "" ) + "&" + $.mobile.subPageUrlKey + "=" + listId,
				theme = list.jqmData( "theme" ) || o.theme,
				countTheme = list.jqmData( "counttheme" ) || parentList.jqmData( "counttheme" ) || o.countTheme,
				newPage, anchor;

			//define hasSubPages for use in later removal
			hasSubPages = true;

			newPage = list.detach()
						.wrap( "<div " + dns + "role='page' " + dns + "url='" + id + "' " + dns + "theme='" + theme + "' " + dns + "count-theme='" + countTheme + "'><div " + dns + "role='content'></div></div>" )
						.parent()
							.before( "<div " + dns + "role='header' " + dns + "theme='" + o.headerTheme + "'><div class='ui-title'>" + title + "</div></div>" )
							.after( persistentFooterID ? $( "<div " + dns + "role='footer' " + dns + "id='"+ persistentFooterID +"'>" ) : "" )
							.parent()
								.appendTo( $.mobile.pageContainer );

			newPage.page();

			anchor = parent.find( 'a:first' );

			if ( !anchor.length ) {
				anchor = $( "<a/>" ).html( nodeEls || title ).prependTo( parent.empty() );
			}

			anchor.attr( "href", "#" + id );

		}).listview();

		// on pagehide, remove any nested pages along with the parent page, as long as they aren't active
		// and aren't embedded
		if ( hasSubPages &&
			parentPage.is( ":jqmData(external-page='true')" ) &&
			parentPage.data( "page" ).options.domCache === false ) {

			var newRemove = function( e, ui ) {
				var nextPage = ui.nextPage, npURL,
					prEvent = new $.Event( "pageremove" );

				if ( ui.nextPage ) {
					npURL = nextPage.jqmData( "url" );
					if ( npURL.indexOf( parentUrl + "&" + $.mobile.subPageUrlKey ) !== 0 ) {
						self.childPages().remove();
						parentPage.trigger( prEvent );
						if ( !prEvent.isDefaultPrevented() ) {
							parentPage.removeWithDependents();
						}
					}
				}
			};

			// unbind the original page remove and replace with our specialized version
			parentPage
				.unbind( "pagehide.remove" )
				.bind( "pagehide.remove", newRemove);
		}
	},

	// TODO sort out a better way to track sub pages of the listview this is brittle
	childPages: function() {
		var parentUrl = this.parentPage.jqmData( "url" );

		return $( ":jqmData(url^='"+  parentUrl + "&" + $.mobile.subPageUrlKey + "')" );
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.listview.prototype.enhanceWithin( e.target );
});

})( jQuery );

(function( $, undefined ) {

$.mobile.listview.prototype.options.autodividers = false;
$.mobile.listview.prototype.options.autodividersSelector = function( elt ) {
	// look for the text in the given element
	var text = elt.text() || null;

	if ( !text ) {
		return null;
	}

	// create the text for the divider (first uppercased letter)
	text = text.slice( 0, 1 ).toUpperCase();

	return text;
};

$( document ).delegate( "ul,ol", "listviewcreate", function() {

	var list = $( this ),
			listview = list.data( "listview" );

	if ( !listview || !listview.options.autodividers ) {
		return;
	}

	var replaceDividers = function () {
		list.find( "li:jqmData(role='list-divider')" ).remove();

		var lis = list.find( 'li' ),
			lastDividerText = null, li, dividerText;

		for ( var i = 0; i < lis.length ; i++ ) {
			li = lis[i];
			dividerText = listview.options.autodividersSelector( $( li ) );

			if ( dividerText && lastDividerText !== dividerText ) {
				var divider = document.createElement( 'li' );
				divider.appendChild( document.createTextNode( dividerText ) );
				divider.setAttribute( 'data-' + $.mobile.ns + 'role', 'list-divider' );
				li.parentNode.insertBefore( divider, li );
			}

			lastDividerText = dividerText;
		}
	};

	var afterListviewRefresh = function () {
		list.unbind( 'listviewafterrefresh', afterListviewRefresh );
		replaceDividers();
		listview.refresh();
		list.bind( 'listviewafterrefresh', afterListviewRefresh );
	};

	afterListviewRefresh();
});

})( jQuery );

/*
* "checkboxradio" plugin
*/

(function( $, undefined ) {

$.widget( "mobile.checkboxradio", $.mobile.widget, {
	options: {
		theme: null,
		initSelector: "input[type='checkbox'],input[type='radio']"
	},
	_create: function() {
		var self = this,
			input = this.element,
			inheritAttr = function( input, dataAttr ) {
				return input.jqmData( dataAttr ) || input.closest( "form, fieldset" ).jqmData( dataAttr );
			},
			// NOTE: Windows Phone could not find the label through a selector
			// filter works though.
			parentLabel = $( input ).closest( "label" ),
			label = parentLabel.length ? parentLabel : $( input ).closest( "form, fieldset, :jqmData(role='page'), :jqmData(role='dialog')" ).find( "label" ).filter( "[for='" + input[0].id + "']" ).first(),
			inputtype = input[0].type,
			mini = inheritAttr( input, "mini" ),
			checkedState = inputtype + "-on",
			uncheckedState = inputtype + "-off",
			icon = input.parents( ":jqmData(type='horizontal')" ).length ? undefined : uncheckedState,
			iconpos = inheritAttr( input, "iconpos" ),
			activeBtn = icon ? "" : " " + $.mobile.activeBtnClass,
			checkedClass = "ui-" + checkedState + activeBtn,
			uncheckedClass = "ui-" + uncheckedState,
			checkedicon = "ui-icon-" + checkedState,
			uncheckedicon = "ui-icon-" + uncheckedState;

		if ( inputtype !== "checkbox" && inputtype !== "radio" ) {
			return;
		}

		// Expose for other methods
		$.extend( this, {
			label: label,
			inputtype: inputtype,
			checkedClass: checkedClass,
			uncheckedClass: uncheckedClass,
			checkedicon: checkedicon,
			uncheckedicon: uncheckedicon
		});

		// If there's no selected theme check the data attr
		if ( !this.options.theme ) {
			this.options.theme = $.mobile.getInheritedTheme( this.element, "c" );
		}

		label.buttonMarkup({
			theme: this.options.theme,
			icon: icon,
			shadow: false,
			mini: mini,
			iconpos: iconpos
		});

		// Wrap the input + label in a div
		var wrapper = document.createElement('div');
		wrapper.className = 'ui-' + inputtype;

		input.add( label ).wrapAll( wrapper );

		label.bind({
			vmouseover: function( event ) {
				if ( $( this ).parent().is( ".ui-disabled" ) ) {
					event.stopPropagation();
				}
			},

			vclick: function( event ) {
				if ( input.is( ":disabled" ) ) {
					event.preventDefault();
					return;
				}

				self._cacheVals();

				input.prop( "checked", inputtype === "radio" && true || !input.prop( "checked" ) );

				// trigger click handler's bound directly to the input as a substitute for
				// how label clicks behave normally in the browsers
				// TODO: it would be nice to let the browser's handle the clicks and pass them
				//       through to the associate input. we can swallow that click at the parent
				//       wrapper element level
				input.triggerHandler( 'click' );

				// Input set for common radio buttons will contain all the radio
				// buttons, but will not for checkboxes. clearing the checked status
				// of other radios ensures the active button state is applied properly
				self._getInputSet().not( input ).prop( "checked", false );

				self._updateAll();
				return false;
			}
		});

		input
			.bind({
				vmousedown: function() {
					self._cacheVals();
				},

				vclick: function() {
					var $this = $( this );

					// Adds checked attribute to checked input when keyboard is used
					if ( $this.is( ":checked" ) ) {

						$this.prop( "checked", true);
						self._getInputSet().not( $this ).prop( "checked", false );
					} else {

						$this.prop( "checked", false );
					}

					self._updateAll();
				},

				focus: function() {
					label.addClass( $.mobile.focusClass );
				},

				blur: function() {
					label.removeClass( $.mobile.focusClass );
				}
			});

		this.refresh();
	},

	_cacheVals: function() {
		this._getInputSet().each(function() {
			$( this ).jqmData( "cacheVal", this.checked );
		});
	},

	//returns either a set of radios with the same name attribute, or a single checkbox
	_getInputSet: function() {
		if ( this.inputtype === "checkbox" ) {
			return this.element;
		}

		return this.element.closest( "form, fieldset, :jqmData(role='page'), :jqmData(role='dialog')" )
			.find( "input[name='" + this.element[0].name + "'][type='" + this.inputtype + "']" );
	},

	_updateAll: function() {
		var self = this;

		this._getInputSet().each(function() {
			var $this = $( this );

			if ( this.checked || self.inputtype === "checkbox" ) {
				$this.trigger( "change" );
			}
		})
		.checkboxradio( "refresh" );
	},

	refresh: function() {
		var input = this.element[0],
			label = this.label,
			icon = label.find( ".ui-icon" );

		if ( input.checked ) {
			label.addClass( this.checkedClass ).removeClass( this.uncheckedClass );
			icon.addClass( this.checkedicon ).removeClass( this.uncheckedicon );
		} else {
			label.removeClass( this.checkedClass ).addClass( this.uncheckedClass );
			icon.removeClass( this.checkedicon ).addClass( this.uncheckedicon );
		}

		if ( input.disabled ) {
			this.disable();
		} else {
			this.enable();
		}
	},

	disable: function() {
		this.element.prop( "disabled", true ).parent().addClass( "ui-disabled" );
	},

	enable: function() {
		this.element.prop( "disabled", false ).parent().removeClass( "ui-disabled" );
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.checkboxradio.prototype.enhanceWithin( e.target, true );
});

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.button", $.mobile.widget, {
	options: {
		theme: null,
		icon: null,
		iconpos: null,
		corners: true,
		shadow: true,
		iconshadow: true,
		initSelector: "button, [type='button'], [type='submit'], [type='reset']"
	},
	_create: function() {
		var $el = this.element,
			$button,
			o = this.options,
			type,
			name,
			inline = o.inline || $el.jqmData( "inline" ),
			mini = o.mini || $el.jqmData( "mini" ),
			classes = "",
			$buttonPlaceholder;

		// if this is a link, check if it's been enhanced and, if not, use the right function
		if ( $el[ 0 ].tagName === "A" ) {
			if ( !$el.hasClass( "ui-btn" ) ) {
				$el.buttonMarkup();
			}

			return;
		}

		// get the inherited theme
		// TODO centralize for all widgets
		if ( !this.options.theme ) {
			this.options.theme = $.mobile.getInheritedTheme( this.element, "c" );
		}

		// TODO: Post 1.1--once we have time to test thoroughly--any classes manually applied to the original element should be carried over to the enhanced element, with an `-enhanced` suffix. See https://github.com/jquery/jquery-mobile/issues/3577
		/* if ( $el[0].className.length ) {
			classes = $el[0].className;
		} */
		if ( !!~$el[0].className.indexOf( "ui-btn-left" ) ) {
			classes = "ui-btn-left";
		}

		if (  !!~$el[0].className.indexOf( "ui-btn-right" ) ) {
			classes = "ui-btn-right";
		}

		if (  $el.attr( "type" ) === "submit" || $el.attr( "type" ) === "reset" ) {
			classes ? classes += " ui-submit" :  classes = "ui-submit";
		}
		$( "label[for='" + $el.attr( "id" ) + "']" ).addClass( "ui-submit" );

		// Add ARIA role
		this.button = $( "<div></div>" )
			[ $el.html() ? "html" : "text" ]( $el.html() || $el.val() )
			.insertBefore( $el )
			.buttonMarkup({
				theme: o.theme,
				icon: o.icon,
				iconpos: o.iconpos,
				inline: inline,
				corners: o.corners,
				shadow: o.shadow,
				iconshadow: o.iconshadow,
				mini: mini
			})
			.addClass( classes )
			.append( $el.addClass( "ui-btn-hidden" ) );

        $button = this.button;
		type = $el.attr( "type" );
		name = $el.attr( "name" );

		// Add hidden input during submit if input type="submit" has a name.
		if ( type !== "button" && type !== "reset" && name ) {
				$el.bind( "vclick", function() {
					// Add hidden input if it doesn't already exist.
					if ( $buttonPlaceholder === undefined ) {
						$buttonPlaceholder = $( "<input>", {
							type: "hidden",
							name: $el.attr( "name" ),
							value: $el.attr( "value" )
						}).insertBefore( $el );

						// Bind to doc to remove after submit handling
						$( document ).one( "submit", function() {
							$buttonPlaceholder.remove();

							// reset the local var so that the hidden input
							// will be re-added on subsequent clicks
							$buttonPlaceholder = undefined;
						});
					}
				});
		}

		$el.bind({
			focus: function() {
				$button.addClass( $.mobile.focusClass );
			},

			blur: function() {
				$button.removeClass( $.mobile.focusClass );
			}
		});

		this.refresh();
	},

	enable: function() {
		this.element.attr( "disabled", false );
		this.button.removeClass( "ui-disabled" ).attr( "aria-disabled", false );
		return this._setOption( "disabled", false );
	},

	disable: function() {
		this.element.attr( "disabled", true );
		this.button.addClass( "ui-disabled" ).attr( "aria-disabled", true );
		return this._setOption( "disabled", true );
	},

	refresh: function() {
		var $el = this.element;

		if ( $el.prop("disabled") ) {
			this.disable();
		} else {
			this.enable();
		}

		// Grab the button's text element from its implementation-independent data item
		$( this.button.data( 'buttonElements' ).text )[ $el.html() ? "html" : "text" ]( $el.html() || $el.val() );
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.button.prototype.enhanceWithin( e.target, true );
});

})( jQuery );

(function( $, undefined ) {

$.fn.controlgroup = function( options ) {
	function flipClasses( els, flCorners  ) {
		els.removeClass( "ui-btn-corner-all ui-corner-top ui-corner-bottom ui-corner-left ui-corner-right ui-controlgroup-last ui-shadow" )
			.eq( 0 ).addClass( flCorners[ 0 ] )
			.end()
			.last().addClass( flCorners[ 1 ] ).addClass( "ui-controlgroup-last" );
	}

	return this.each(function() {
		var $el = $( this ),
			o = $.extend({
						direction: $el.jqmData( "type" ) || "vertical",
						shadow: false,
						excludeInvisible: true,
						mini: $el.jqmData( "mini" )
					}, options ),
			grouplegend = $el.children( "legend" ),
			groupheading = $el.children( ".ui-controlgroup-label" ),
			groupcontrols = $el.children( ".ui-controlgroup-controls" ),
			flCorners = o.direction === "horizontal" ? [ "ui-corner-left", "ui-corner-right" ] : [ "ui-corner-top", "ui-corner-bottom" ],
			type = $el.find( "input" ).first().attr( "type" );

		// First unwrap the controls if the controlgroup was already enhanced
		if ( groupcontrols.length ) {
			groupcontrols.contents().unwrap();
		}
		$el.wrapInner( "<div class='ui-controlgroup-controls'></div>" );

		if ( grouplegend.length ) {
			// Replace legend with more stylable replacement div
			$( "<div role='heading' class='ui-controlgroup-label'>" + grouplegend.html() + "</div>" ).insertBefore( $el.children( 0 ) );
			grouplegend.remove();
		} else if ( groupheading.length ) {
			// Just move the heading if the controlgroup was already enhanced
			$el.prepend( groupheading );
		}

		$el.addClass( "ui-corner-all ui-controlgroup ui-controlgroup-" + o.direction );

		flipClasses( $el.find( ".ui-btn" + ( o.excludeInvisible ? ":visible" : "" ) ).not( '.ui-slider-handle' ), flCorners );
		flipClasses( $el.find( ".ui-btn-inner" ), flCorners );

		if ( o.shadow ) {
			$el.addClass( "ui-shadow" );
		}

		if ( o.mini ) {
			$el.addClass( "ui-mini" );
		}

	});
};

// The pagecreate handler for controlgroup is in jquery.mobile.init because of the soft-dependency on the wrapped widgets

})(jQuery);

(function( $, undefined ) {

$( document ).bind( "pagecreate create", function( e ) {

	//links within content areas, tests included with page
	$( e.target )
		.find( "a" )
		.jqmEnhanceable()
		.not( ".ui-btn, .ui-link-inherit, :jqmData(role='none'), :jqmData(role='nojs')" )
		.addClass( "ui-link" );

});

})( jQuery );


(function( $, undefined ) {

	function fitSegmentInsideSegment( winSize, segSize, offset, desired ) {
		var ret = desired;

		if ( winSize < segSize ) {
			// Center segment if it's bigger than the window
			ret = offset + ( winSize - segSize ) / 2;
		} else {
			// Otherwise center it at the desired coordinate while keeping it completely inside the window
			ret = Math.min( Math.max( offset, desired - segSize / 2 ), offset + winSize - segSize );
		}

		return ret;
	}

	function windowCoords() {
		var $win = $( window );

		return {
			x: $win.scrollLeft(),
			y: $win.scrollTop(),
			cx: ( window.innerWidth || $win.width() ),
			cy: ( window.innerHeight || $win.height() )
		};
	}

	$.widget( "mobile.popup", $.mobile.widget, {
		options: {
			theme: null,
			overlayTheme: null,
			shadow: true,
			corners: true,
			transition: "none",
			positionTo: "origin",
			tolerance: null,
			initSelector: ":jqmData(role='popup')",
			closeLinkSelector: "a:jqmData(rel='back')",
			closeLinkEvents: "click.popup",
			navigateEvents: "navigate.popup",
			closeEvents: "navigate.popup pagebeforechange.popup",

			// NOTE Windows Phone 7 has a scroll position caching issue that
			//      requires us to disable popup history management by default
			//      https://github.com/jquery/jquery-mobile/issues/4784
			//
			// NOTE this option is modified in _create!
			history: !$.mobile.browser.ie
		},

		_eatEventAndClose: function( e ) {
			e.preventDefault();
			e.stopImmediatePropagation();
			this.close();
			return false;
		},

		// Make sure the screen size is increased beyond the page height if the popup's causes the document to increase in height
		_resizeScreen: function() {
			var popupHeight = this._ui.container.outerHeight( true );

			this._ui.screen.removeAttr( "style" );
			if ( popupHeight > this._ui.screen.height() ) {
				this._ui.screen.height( popupHeight );
			}
		},

		_handleWindowKeyUp: function( e ) {
			if ( this._isOpen && e.keyCode === $.mobile.keyCode.ESCAPE ) {
				return this._eatEventAndClose( e );
			}
		},

		_maybeRefreshTimeout: function() {
			var winCoords = windowCoords();

			if ( this._resizeData ) {
				if ( winCoords.x === this._resizeData.winCoords.x &&
					winCoords.y === this._resizeData.winCoords.y &&
					winCoords.cx === this._resizeData.winCoords.cx &&
					winCoords.cy === this._resizeData.winCoords.cy ) {
					// timeout not refreshed
					return false;
				} else {
					// clear existing timeout - it will be refreshed below
					clearTimeout( this._resizeData.timeoutId );
				}
			}

			this._resizeData = {
				timeoutId: setTimeout( $.proxy( this, "_resizeTimeout" ), 200 ),
				winCoords: winCoords
			};

			return true;
		},

		_resizeTimeout: function() {
			if ( !this._maybeRefreshTimeout() ) {
				// effectively rapid-open the popup while leaving the screen intact
				this._trigger( "beforeposition" );
				this._ui.container
					.removeClass( "ui-selectmenu-hidden" )
					.offset( this._placementCoords( this._desiredCoords( undefined, undefined, "window" ) ) );

				this._resizeScreen();
				this._resizeData = null;
				this._orientationchangeInProgress = false;
			}
		},

		_handleWindowResize: function( e ) {
			if ( this._isOpen ) {
				this._maybeRefreshTimeout();
			}
		},

		_handleWindowOrientationchange: function( e ) {

			if ( !this._orientationchangeInProgress ) {
				// effectively rapid-close the popup while leaving the screen intact
				this._ui.container
					.addClass( "ui-selectmenu-hidden" )
					.removeAttr( "style" );

				this._orientationchangeInProgress = true;
			}
		},

		_create: function() {
			var ui = {
					screen: $( "<div class='ui-screen-hidden ui-popup-screen'></div>" ),
					placeholder: $( "<div style='display: none;'><!-- placeholder --></div>" ),
					container: $( "<div class='ui-popup-container ui-selectmenu-hidden'></div>" )
				},
				thisPage = this.element.closest( ".ui-page" ),
				myId = this.element.attr( "id" ),
				self = this;

			// We need to adjust the history option to be false if there's no AJAX nav.
			// We can't do it in the option declarations because those are run before
			// it is determined whether there shall be AJAX nav.
			this.options.history = this.options.history && $.mobile.ajaxEnabled && $.mobile.hashListeningEnabled;

			if ( thisPage.length === 0 ) {
				thisPage = $( "body" );
			}

			// define the container for navigation event bindings
			// TODO this would be nice at the the mobile widget level
			this.options.container = this.options.container || $.mobile.pageContainer;

			// Apply the proto
			thisPage.append( ui.screen );
			ui.container.insertAfter( ui.screen );
			// Leave a placeholder where the element used to be
			ui.placeholder.insertAfter( this.element );
			if ( myId ) {
				ui.screen.attr( "id", myId + "-screen" );
				ui.container.attr( "id", myId + "-popup" );
				ui.placeholder.html( "<!-- placeholder for " + myId + " -->" );
			}
			ui.container.append( this.element );

			// Add class to popup element
			this.element.addClass( "ui-popup" );

			// Define instance variables
			$.extend( this, {
				_page: thisPage,
				_ui: ui,
				_fallbackTransition: "",
				_currentTransition: false,
				_prereqs: null,
				_isOpen: false,
				_tolerance: null,
				_resizeData: null,
				_orientationchangeInProgress: false,
				_globalHandlers: [
					{
						src: $( window ),
						handler: {
							orientationchange: $.proxy( this, "_handleWindowOrientationchange" ),
							resize: $.proxy( this, "_handleWindowResize" ),
							keyup: $.proxy( this, "_handleWindowKeyUp" )
						}
					}
				]
			});

			$.each( this.options, function( key, value ) {
				// Cause initial options to be applied by their handler by temporarily setting the option to undefined
				// - the handler then sets it to the initial value
				self.options[ key ] = undefined;
				self._setOption( key, value, true );
			});

			ui.screen.bind( "vclick", $.proxy( this, "_eatEventAndClose" ) );

			$.each( this._globalHandlers, function( idx, value ) {
				value.src.bind( value.handler );
			});
		},

		_applyTheme: function( dst, theme, prefix ) {
			var classes = ( dst.attr( "class" ) || "").split( " " ),
				alreadyAdded = true,
				currentTheme = null,
				matches,
				themeStr = String( theme );

			while ( classes.length > 0 ) {
				currentTheme = classes.pop();
				matches = ( new RegExp( "^ui-" + prefix + "-([a-z])$" ) ).exec( currentTheme );
				if ( matches && matches.length > 1 ) {
					currentTheme = matches[ 1 ];
					break;
				} else {
					currentTheme = null;
				}
			}

			if ( theme !== currentTheme ) {
				dst.removeClass( "ui-" + prefix + "-" + currentTheme );
				if ( ! ( theme === null || theme === "none" ) ) {
					dst.addClass( "ui-" + prefix + "-" + themeStr );
				}
			}
		},

		_setTheme: function( value ) {
			this._applyTheme( this.element, value, "body" );
		},

		_setOverlayTheme: function( value ) {
			this._applyTheme( this._ui.screen, value, "overlay" );

			if ( this._isOpen ) {
				this._ui.screen.addClass( "in" );
			}
		},

		_setShadow: function( value ) {
			this.element.toggleClass( "ui-overlay-shadow", value );
		},

		_setCorners: function( value ) {
			this.element.toggleClass( "ui-corner-all", value );
		},

		_applyTransition: function( value ) {
			this._ui.container.removeClass( this._fallbackTransition );
			if ( value && value !== "none" ) {
				this._fallbackTransition = $.mobile._maybeDegradeTransition( value );
				this._ui.container.addClass( this._fallbackTransition );
			}
		},

		_setTransition: function( value ) {
			if ( !this._currentTransition ) {
				this._applyTransition( value );
			}
		},

		_setTolerance: function( value ) {
			var tol = { t: 30, r: 15, b: 30, l: 15 };

			if ( value ) {
				var ar = String( value ).split( "," );

				$.each( ar, function( idx, val ) { ar[ idx ] = parseInt( val, 10 ); } );

				switch( ar.length ) {
					// All values are to be the same
					case 1:
						if ( !isNaN( ar[ 0 ] ) ) {
							tol.t = tol.r = tol.b = tol.l = ar[ 0 ];
						}
						break;

					// The first value denotes top/bottom tolerance, and the second value denotes left/right tolerance
					case 2:
						if ( !isNaN( ar[ 0 ] ) ) {
							tol.t = tol.b = ar[ 0 ];
						}
						if ( !isNaN( ar[ 1 ] ) ) {
							tol.l = tol.r = ar[ 1 ];
						}
						break;

					// The array contains values in the order top, right, bottom, left
					case 4:
						if ( !isNaN( ar[ 0 ] ) ) {
							tol.t = ar[ 0 ];
						}
						if ( !isNaN( ar[ 1 ] ) ) {
							tol.r = ar[ 1 ];
						}
						if ( !isNaN( ar[ 2 ] ) ) {
							tol.b = ar[ 2 ];
						}
						if ( !isNaN( ar[ 3 ] ) ) {
							tol.l = ar[ 3 ];
						}
						break;

					default:
						break;
				}
			}

			this._tolerance = tol;
		},

		_setOption: function( key, value ) {
			var exclusions, setter = "_set" + key.charAt( 0 ).toUpperCase() + key.slice( 1 );

			if ( this[ setter ] !== undefined ) {
				this[ setter ]( value );
			}

			// TODO REMOVE FOR 1.2.1 by moving them out to a default options object
			exclusions = [
				"initSelector",
				"closeLinkSelector",
				"closeLinkEvents",
				"navigateEvents",
				"closeEvents",
				"history",
				"container"
			];

			$.mobile.widget.prototype._setOption.apply( this, arguments );
			if ( $.inArray( key, exclusions ) === -1 ) {
				// Record the option change in the options and in the DOM data-* attributes
				this.element.attr( "data-" + ( $.mobile.ns || "" ) + ( key.replace( /([A-Z])/, "-$1" ).toLowerCase() ), value );
			}
		},

		// Try and center the overlay over the given coordinates
		_placementCoords: function( desired ) {
			// rectangle within which the popup must fit
			var
				winCoords = windowCoords(),
				rc = {
					x: this._tolerance.l,
					y: winCoords.y + this._tolerance.t,
					cx: winCoords.cx - this._tolerance.l - this._tolerance.r,
					cy: winCoords.cy - this._tolerance.t - this._tolerance.b
				},
				menuSize, ret;

			// Clamp the width of the menu before grabbing its size
			this._ui.container.css( "max-width", rc.cx );
			menuSize = {
				cx: this._ui.container.outerWidth( true ),
				cy: this._ui.container.outerHeight( true )
			};

			// Center the menu over the desired coordinates, while not going outside
			// the window tolerances. This will center wrt. the window if the popup is too large.
			ret = {
				x: fitSegmentInsideSegment( rc.cx, menuSize.cx, rc.x, desired.x ),
				y: fitSegmentInsideSegment( rc.cy, menuSize.cy, rc.y, desired.y )
			};

			// Make sure the top of the menu is visible
			ret.y = Math.max( 0, ret.y );

			// If the height of the menu is smaller than the height of the document
			// align the bottom with the bottom of the document

			// fix for $( document ).height() bug in core 1.7.2.
			var docEl = document.documentElement, docBody = document.body,
				docHeight = Math.max( docEl.clientHeight, docBody.scrollHeight, docBody.offsetHeight, docEl.scrollHeight, docEl.offsetHeight );

			ret.y -= Math.min( ret.y, Math.max( 0, ret.y + menuSize.cy - docHeight ) );

			return { left: ret.x, top: ret.y };
		},

		_createPrereqs: function( screenPrereq, containerPrereq, whenDone ) {
			var self = this, prereqs;

			// It is important to maintain both the local variable prereqs and self._prereqs. The local variable remains in
			// the closure of the functions which call the callbacks passed in. The comparison between the local variable and
			// self._prereqs is necessary, because once a function has been passed to .animationComplete() it will be called
			// next time an animation completes, even if that's not the animation whose end the function was supposed to catch
			// (for example, if an abort happens during the opening animation, the .animationComplete handler is not called for
			// that animation anymore, but the handler remains attached, so it is called the next time the popup is opened
			// - making it stale. Comparing the local variable prereqs to the widget-level variable self._prereqs ensures that
			// callbacks triggered by a stale .animationComplete will be ignored.

			prereqs = {
				screen: $.Deferred(),
				container: $.Deferred()
			};

			prereqs.screen.then( function() {
				if ( prereqs === self._prereqs ) {
					screenPrereq();
				}
			});

			prereqs.container.then( function() {
				if ( prereqs === self._prereqs ) {
					containerPrereq();
				}
			});

			$.when( prereqs.screen, prereqs.container ).done( function() {
				if ( prereqs === self._prereqs ) {
					self._prereqs = null;
					whenDone();
				}
			});

			self._prereqs = prereqs;
		},

		_animate: function( args ) {
			// NOTE before removing the default animation of the screen
			//      this had an animate callback that would relove the deferred
			//      now the deferred is resolved immediately
			// TODO remove the dependency on the screen deferred
			this._ui.screen
				.removeClass( args.classToRemove )
				.addClass( args.screenClassToAdd );

			args.prereqs.screen.resolve();

			if ( args.transition && args.transition !== "none" ) {
				if ( args.applyTransition ) {
					this._applyTransition( args.transition );
				}
				this._ui.container
					.animationComplete( $.proxy( args.prereqs.container, "resolve" ) )
					.addClass( args.containerClassToAdd )
					.removeClass( args.classToRemove );
			} else {
				args.prereqs.container.resolve();
			}
		},

		// The desired coordinates passed in will be returned untouched if no reference element can be identified via
		// desiredPosition.positionTo. Nevertheless, this function ensures that its return value always contains valid
		// x and y coordinates by specifying the center middle of the window if the coordinates are absent.
		_desiredCoords: function( x, y, positionTo ) {
			var dst = null, offset, winCoords = windowCoords();

			// Establish which element will serve as the reference
			if ( positionTo && positionTo !== "origin" ) {
				if ( positionTo === "window" ) {
					x = winCoords.cx / 2 + winCoords.x;
					y = winCoords.cy / 2 + winCoords.y;
				} else {
					try {
						dst = $( positionTo );
					} catch( e ) {
						dst = null;
					}
					if ( dst ) {
						dst.filter( ":visible" );
						if ( dst.length === 0 ) {
							dst = null;
						}
					}
				}
			}

			// If an element was found, center over it
			if ( dst ) {
				offset = dst.offset();
				x = offset.left + dst.outerWidth() / 2;
				y = offset.top + dst.outerHeight() / 2;
			}

			// Make sure x and y are valid numbers - center over the window
			if ( $.type( x ) !== "number" || isNaN( x ) ) {
				x = winCoords.cx / 2 + winCoords.x;
			}
			if ( $.type( y ) !== "number" || isNaN( y ) ) {
				y = winCoords.cy / 2 + winCoords.y;
			}

			return { x: x, y: y };
		},

		_openPrereqsComplete: function() {
			var self = this;

			self._ui.container.addClass( "ui-popup-active" );
			self._isOpen = true;
			self._resizeScreen();

			// Android appears to trigger the animation complete before the popup
			// is visible. Allowing the stack to unwind before applying focus prevents
			// the "blue flash" of element focus in android 4.0
			setTimeout(function(){
				self._ui.container.attr( "tabindex", "0" ).focus();
				self._trigger( "afteropen" );
			});
		},

		_open: function( options ) {
			var coords, transition,
				androidBlacklist = ( function() {
					var w = window,
						ua = navigator.userAgent,
						// Rendering engine is Webkit, and capture major version
						wkmatch = ua.match( /AppleWebKit\/([0-9\.]+)/ ),
						wkversion = !!wkmatch && wkmatch[ 1 ],
						androidmatch = ua.match( /Android (\d+(?:\.\d+))/ ),
						andversion = !!androidmatch && androidmatch[ 1 ],
						chromematch = ua.indexOf( "Chrome" ) > -1;

					// Platform is Android, WebKit version is greater than 534.13 ( Android 3.2.1 ) and not Chrome.
					if( androidmatch !== null && andversion === "4.0" && wkversion && wkversion > 534.13 && !chromematch ) {
						return true;
					}
					return false;
				}());

			// Make sure options is defined
			options = ( options || {} );

			// Copy out the transition, because we may be overwriting it later and we don't want to pass that change back to the caller
			transition = options.transition || this.options.transition;

			// Give applications a chance to modify the contents of the container before it appears
			this._trigger( "beforeposition" );

			coords = this._placementCoords( this._desiredCoords( options.x, options.y, options.positionTo || this.options.positionTo || "origin" ) );

			// Count down to triggering "popupafteropen" - we have two prerequisites:
			// 1. The popup window animation completes (container())
			// 2. The screen opacity animation completes (screen())
			this._createPrereqs(
				$.noop,
				$.noop,
				$.proxy( this, "_openPrereqsComplete" ) );

			if ( transition ) {
				this._currentTransition = transition;
				this._applyTransition( transition );
			} else {
				transition = this.options.transition;
			}

			if ( !this.options.theme ) {
				this._setTheme( this._page.jqmData( "theme" ) || $.mobile.getInheritedTheme( this._page, "c" ) );
			}

			this._ui.screen.removeClass( "ui-screen-hidden" );

			this._ui.container
				.removeClass( "ui-selectmenu-hidden" )
				.offset( coords );

			if ( this.options.overlayTheme && androidBlacklist ) {
				/* TODO:
				The native browser on Android 4.0.X ("Ice Cream Sandwich") suffers from an issue where the popup overlay appears to be z-indexed
				above the popup itself when certain other styles exist on the same page -- namely, any element set to `position: fixed` and certain
				types of input. These issues are reminiscent of previously uncovered bugs in older versions of Android's native browser:
				https://github.com/scottjehl/Device-Bugs/issues/3

				This fix closes the following bugs ( I use "closes" with reluctance, and stress that this issue should be revisited as soon as possible ):

				https://github.com/jquery/jquery-mobile/issues/4816
				https://github.com/jquery/jquery-mobile/issues/4844
				https://github.com/jquery/jquery-mobile/issues/4874
				*/

				// TODO sort out why this._page isn't working
				this.element.closest( ".ui-page" ).addClass( "ui-popup-open" );
			}
			this._animate({
				additionalCondition: true,
				transition: transition,
				classToRemove: "",
				screenClassToAdd: "in",
				containerClassToAdd: "in",
				applyTransition: false,
				prereqs: this._prereqs
			});
		},

		_closePrereqScreen: function() {
			this._ui.screen
				.removeClass( "out" )
				.addClass( "ui-screen-hidden" );
		},

		_closePrereqContainer: function() {
			this._ui.container
				.removeClass( "reverse out" )
				.addClass( "ui-selectmenu-hidden" )
				.removeAttr( "style" );
		},

		_closePrereqsDone: function() {
			var self = this, opts = self.options;

			self._ui.container.removeAttr( "tabindex" );

			// remove nav bindings if they are still present
			opts.container.unbind( opts.closeEvents );

			// unbind click handlers added when history is disabled
			self.element.undelegate( opts.closeLinkSelector, opts.closeLinkEvents );

			// remove the global mutex for popups
			$.mobile.popup.active = undefined;

			// alert users that the popup is closed
			self._trigger( "afterclose" );
		},

		_close: function() {
			this._ui.container.removeClass( "ui-popup-active" );
			this._page.removeClass( "ui-popup-open" );

			this._isOpen = false;

			// Count down to triggering "popupafterclose" - we have two prerequisites:
			// 1. The popup window reverse animation completes (container())
			// 2. The screen opacity animation completes (screen())
			this._createPrereqs(
				$.proxy( this, "_closePrereqScreen" ),
				$.proxy( this, "_closePrereqContainer" ),
				$.proxy( this, "_closePrereqsDone" ) );

			this._animate( {
				additionalCondition: this._ui.screen.hasClass( "in" ),
				transition: ( this._currentTransition || this.options.transition ),
				classToRemove: "in",
				screenClassToAdd: "out",
				containerClassToAdd: "reverse out",
				applyTransition: true,
				prereqs: this._prereqs
			});
		},

		_destroy: function() {
			var self = this;

			// hide and remove bindings
			self._close();

			// Put the element back to where the placeholder was and remove the "ui-popup" class
			self._setTheme( "none" );
			self.element
				.insertAfter( self._ui.placeholder )
				.removeClass( "ui-popup ui-overlay-shadow ui-corner-all" );
			self._ui.screen.remove();
			self._ui.container.remove();
			self._ui.placeholder.remove();

			// Unbind handlers that were bound to elements outside self.element (the window, in self case)
			$.each( self._globalHandlers, function( idx, oneSrc ) {
				$.each( oneSrc.handler, function( eventType, handler ) {
					oneSrc.src.unbind( eventType, handler );
				});
			});
		},

		// any navigation event after a popup is opened should close the popup
		// NOTE the pagebeforechange is bound to catch navigation events that don't
		//      alter the url (eg, dialogs from popups)
		_bindContainerClose: function() {
			var self = this;

			self.options.container
				.one( self.options.closeEvents, $.proxy( self._close, self ));
		},

		// TODO no clear deliniation of what should be here and
		// what should be in _open. Seems to be "visual" vs "history" for now
		open: function( options ) {
			var self = this, opts = this.options, url, hashkey, activePage, currentIsDialog, hasHash, urlHistory;

			// make sure open is idempotent
			if( $.mobile.popup.active ) {
				return;
			}

			// set the global popup mutex
			$.mobile.popup.active = this;

			// if history alteration is disabled close on navigate events
			// and leave the url as is
			if( !( opts.history ) ) {
				self._open( options );
				self._bindContainerClose();

				// When histoy is disabled we have to grab the data-rel
				// back link clicks so we can close the popup instead of
				// relying on history to do it for us
				self.element
					.delegate( opts.closeLinkSelector, opts.closeLinkEvents, function( e ) {
						self._close();

						// NOTE prevent the browser and navigation handlers from
						// working with the link's rel=back. This may cause
						// issues for developers expecting the event to bubble
						return false;
					});

				return;
			}

			// cache some values for min/readability
			hashkey = $.mobile.dialogHashKey;
			activePage = $.mobile.activePage;
			currentIsDialog = activePage.is( ".ui-dialog" );
			url = $.mobile.urlHistory.getActive().url;
			hasHash = ( url.indexOf( hashkey ) > -1 ) && !currentIsDialog;
			urlHistory = $.mobile.urlHistory;

			if ( hasHash ) {
				self._open( options );
				self._bindContainerClose();
				return;
			}

			// if the current url has no dialog hash key proceed as normal
			// otherwise, if the page is a dialog simply tack on the hash key
			if ( url.indexOf( hashkey ) === -1 && !currentIsDialog ){
				url = url + hashkey;
			} else {
				url = $.mobile.path.parseLocation().hash + hashkey;
			}

			// Tack on an extra hashkey if this is the first page and we've just reconstructed the initial hash
			if ( urlHistory.activeIndex === 0 && url === urlHistory.initialDst ) {
				url += hashkey;
			}

			// swallow the the initial navigation event, and bind for the next
			opts.container.one( opts.navigateEvents, function( e ) {
				e.preventDefault();
				self._open( options );
				self._bindContainerClose();
			});

			urlHistory.ignoreNextHashChange = currentIsDialog;

			// Gotta love methods with 1mm args :(
			urlHistory.addNew( url, undefined, undefined, undefined, "dialog" );

			// set the new url with (or without) the new dialog hash key
			$.mobile.path.set( url );
		},

		close: function() {
			// make sure close is idempotent
			if( !$.mobile.popup.active ){
				return;
			}

			if( this.options.history ) {
				$.mobile.back();
			} else {
				this._close();
			}
		}
	});


	// TODO this can be moved inside the widget
	$.mobile.popup.handleLink = function( $link ) {
		var closestPage = $link.closest( ":jqmData(role='page')" ),
			scope = ( ( closestPage.length === 0 ) ? $( "body" ) : closestPage ),
			// NOTE make sure to get only the hash, ie7 (wp7) return the absolute href
			//      in this case ruining the element selection
			popup = $( $.mobile.path.parseUrl($link.attr( "href" )).hash, scope[0] ),
			offset;

		if ( popup.data( "popup" ) ) {
			offset = $link.offset();
			popup.popup( "open", {
				x: offset.left + $link.outerWidth() / 2,
				y: offset.top + $link.outerHeight() / 2,
				transition: $link.jqmData( "transition" ),
				positionTo: $link.jqmData( "position-to" ),
				link: $link
			});
		}

		//remove after delay
		setTimeout( function() {
			$link.removeClass( $.mobile.activeBtnClass );
		}, 300 );
	};

	// TODO move inside _create
	$( document ).bind( "pagebeforechange", function( e, data ) {
		if ( data.options.role === "popup" ) {
			$.mobile.popup.handleLink( data.options.link );
			e.preventDefault();
		}
	});

	$( document ).bind( "pagecreate create", function( e )  {
		$.mobile.popup.prototype.enhanceWithin( e.target, true );
	});

})( jQuery );

(function( $ ) {
	var	meta = $( "meta[name=viewport]" ),
		initialContent = meta.attr( "content" ),
		disabledZoom = initialContent + ",maximum-scale=1, user-scalable=no",
		enabledZoom = initialContent + ",maximum-scale=10, user-scalable=yes",
		disabledInitially = /(user-scalable[\s]*=[\s]*no)|(maximum-scale[\s]*=[\s]*1)[$,\s]/.test( initialContent );

	$.mobile.zoom = $.extend( {}, {
		enabled: !disabledInitially,
		locked: false,
		disable: function( lock ) {
			if ( !disabledInitially && !$.mobile.zoom.locked ) {
				meta.attr( "content", disabledZoom );
				$.mobile.zoom.enabled = false;
				$.mobile.zoom.locked = lock || false;
			}
		},
		enable: function( unlock ) {
			if ( !disabledInitially && ( !$.mobile.zoom.locked || unlock === true ) ) {
				meta.attr( "content", enabledZoom );
				$.mobile.zoom.enabled = true;
				$.mobile.zoom.locked = false;
			}
		},
		restore: function() {
			if ( !disabledInitially ) {
				meta.attr( "content", initialContent );
				$.mobile.zoom.enabled = true;
			}
		}
	});

}( jQuery ));

(function( $, undefined ) {

$.widget( "mobile.textinput", $.mobile.widget, {
	options: {
		theme: null,
		// This option defaults to true on iOS devices.
		preventFocusZoom: /iPhone|iPad|iPod/.test( navigator.platform ) && navigator.userAgent.indexOf( "AppleWebKit" ) > -1,
		initSelector: "input[type='text'], input[type='search'], :jqmData(type='search'), input[type='number'], :jqmData(type='number'), input[type='password'], input[type='email'], input[type='url'], input[type='tel'], textarea, input[type='time'], input[type='date'], input[type='month'], input[type='week'], input[type='datetime'], input[type='datetime-local'], input[type='color'], input:not([type])",
		clearSearchButtonText: "clear text",
		disabled: false
	},

	_create: function() {

		var self = this,
			input = this.element,
			o = this.options,
			theme = o.theme || $.mobile.getInheritedTheme( this.element, "c" ),
			themeclass  = " ui-body-" + theme,
			mini = input.jqmData( "mini" ) === true,
			miniclass = mini ? " ui-mini" : "",
			focusedEl, clearbtn;

		function toggleClear() {
			setTimeout( function() {
				clearbtn.toggleClass( "ui-input-clear-hidden", !input.val() );
			}, 0 );
		}

		$( "label[for='" + input.attr( "id" ) + "']" ).addClass( "ui-input-text" );

		focusedEl = input.addClass("ui-input-text ui-body-"+ theme );

		// XXX: Temporary workaround for issue 785 (Apple bug 8910589).
		//      Turn off autocorrect and autocomplete on non-iOS 5 devices
		//      since the popup they use can't be dismissed by the user. Note
		//      that we test for the presence of the feature by looking for
		//      the autocorrect property on the input element. We currently
		//      have no test for iOS 5 or newer so we're temporarily using
		//      the touchOverflow support flag for jQM 1.0. Yes, I feel dirty. - jblas
		if ( typeof input[0].autocorrect !== "undefined" && !$.support.touchOverflow ) {
			// Set the attribute instead of the property just in case there
			// is code that attempts to make modifications via HTML.
			input[0].setAttribute( "autocorrect", "off" );
			input[0].setAttribute( "autocomplete", "off" );
		}


		//"search" input widget
		if ( input.is( "[type='search'],:jqmData(type='search')" ) ) {

			focusedEl = input.wrap( "<div class='ui-input-search ui-shadow-inset ui-btn-corner-all ui-btn-shadow ui-icon-searchfield" + themeclass + miniclass + "'></div>" ).parent();
			clearbtn = $( "<a href='#' class='ui-input-clear' title='" + o.clearSearchButtonText + "'>" + o.clearSearchButtonText + "</a>" )
				.bind('click', function( event ) {
					input
						.val( "" )
						.focus()
						.trigger( "change" );
					clearbtn.addClass( "ui-input-clear-hidden" );
					event.preventDefault();
				})
				.appendTo( focusedEl )
				.buttonMarkup({
					icon: "delete",
					iconpos: "notext",
					corners: true,
					shadow: true,
					mini: mini
				});

			toggleClear();

			input.bind( 'paste cut keyup focus change blur', toggleClear );

		} else {
			input.addClass( "ui-corner-all ui-shadow-inset" + themeclass + miniclass );
		}

		input.focus(function() {
				focusedEl.addClass( $.mobile.focusClass );
			})
			.blur(function() {
				focusedEl.removeClass( $.mobile.focusClass );
			})
			// In many situations, iOS will zoom into the select upon tap, this prevents that from happening
			.bind( "focus", function() {
				if ( o.preventFocusZoom ) {
					$.mobile.zoom.disable( true );
				}
			})
			.bind( "blur", function() {
				if ( o.preventFocusZoom ) {
					$.mobile.zoom.enable( true );
				}
			});

		// Autogrow
		if ( input.is( "textarea" ) ) {
			var extraLineHeight = 15,
				keyupTimeoutBuffer = 100,
				keyupTimeout;

			this._keyup = function() {
				var scrollHeight = input[ 0 ].scrollHeight,
					clientHeight = input[ 0 ].clientHeight;

				if ( clientHeight < scrollHeight ) {
					input.height(scrollHeight + extraLineHeight);
				}
			};

			input.keyup(function() {
				clearTimeout( keyupTimeout );
				keyupTimeout = setTimeout( self._keyup, keyupTimeoutBuffer );
			});

			// binding to pagechange here ensures that for pages loaded via
			// ajax the height is recalculated without user input
			this._on( $(document), {"pagechange": "_keyup" });

			// Issue 509: the browser is not providing scrollHeight properly until the styles load
			if ( $.trim( input.val() ) ) {
				// bind to the window load to make sure the height is calculated based on BOTH
				// the DOM and CSS
				this._on( $(window), {"load": "_keyup"});
			}
		}
		if ( input.attr( "disabled" ) ) {
			this.disable();
		}
	},

	disable: function() {
		var $el;
		if ( this.element.attr( "disabled", true ).is( "[type='search'], :jqmData(type='search')" ) ) {
			$el = this.element.parent();
		} else {
			$el = this.element;
		}
		$el.addClass( "ui-disabled" );
		return this._setOption( "disabled", true );
	},

	enable: function() {
		var $el;

		// TODO using more than one line of code is acceptable ;)
		if ( this.element.attr( "disabled", false ).is( "[type='search'], :jqmData(type='search')" ) ) {
			$el = this.element.parent();
		} else {
			$el = this.element;
		}
		$el.removeClass( "ui-disabled" );
		return this._setOption( "disabled", false );
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.textinput.prototype.enhanceWithin( e.target, true );
});

})( jQuery );

(function( $, undefined ) {

$.mobile.listview.prototype.options.filter = false;
$.mobile.listview.prototype.options.filterPlaceholder = "Filter items...";
$.mobile.listview.prototype.options.filterTheme = "c";
// TODO rename callback/deprecate and default to the item itself as the first argument
var defaultFilterCallback = function( text, searchValue, item ) {
		return text.toString().toLowerCase().indexOf( searchValue ) === -1;
	};

$.mobile.listview.prototype.options.filterCallback = defaultFilterCallback;

$( document ).delegate( ":jqmData(role='listview')", "listviewcreate", function() {

	var list = $( this ),
		listview = list.data( "listview" );

	if ( !listview.options.filter ) {
		return;
	}

	var wrapper = $( "<form>", {
			"class": "ui-listview-filter ui-bar-" + listview.options.filterTheme,
			"role": "search"
		}),
		search = $( "<input>", {
			placeholder: listview.options.filterPlaceholder
		})
		.attr( "data-" + $.mobile.ns + "type", "search" )
		.jqmData( "lastval", "" )
		.bind( "keyup change", function() {

			var $this = $( this ),
				val = this.value.toLowerCase(),
				listItems = null,
				lastval = $this.jqmData( "lastval" ) + "",
				childItems = false,
				itemtext = "",
				item,
				// Check if a custom filter callback applies
				isCustomFilterCallback = listview.options.filterCallback !== defaultFilterCallback;

			listview._trigger( "beforefilter", "beforefilter", { input: this } );

			// Change val as lastval for next execution
			$this.jqmData( "lastval" , val );
			if ( isCustomFilterCallback || val.length < lastval.length || val.indexOf( lastval ) !== 0 ) {

				// Custom filter callback applies or removed chars or pasted something totally different, check all items
				listItems = list.children();
			} else {

				// Only chars added, not removed, only use visible subset
				listItems = list.children( ":not(.ui-screen-hidden)" );
			}

			if ( val ) {

				// This handles hiding regular rows without the text we search for
				// and any list dividers without regular rows shown under it

				for ( var i = listItems.length - 1; i >= 0; i-- ) {
					item = $( listItems[ i ] );
					itemtext = item.jqmData( "filtertext" ) || item.text();

					if ( item.is( "li:jqmData(role=list-divider)" ) ) {

						item.toggleClass( "ui-filter-hidequeue" , !childItems );

						// New bucket!
						childItems = false;

					} else if ( listview.options.filterCallback( itemtext, val, item ) ) {

						//mark to be hidden
						item.toggleClass( "ui-filter-hidequeue" , true );
					} else {

						// There's a shown item in the bucket
						childItems = true;
					}
				}

				// Show items, not marked to be hidden
				listItems
					.filter( ":not(.ui-filter-hidequeue)" )
					.toggleClass( "ui-screen-hidden", false );

				// Hide items, marked to be hidden
				listItems
					.filter( ".ui-filter-hidequeue" )
					.toggleClass( "ui-screen-hidden", true )
					.toggleClass( "ui-filter-hidequeue", false );

			} else {

				//filtervalue is empty => show all
				listItems.toggleClass( "ui-screen-hidden", false );
			}
			listview._refreshCorners();
		})
		.appendTo( wrapper )
		.textinput();

	if ( listview.options.inset ) {
		wrapper.addClass( "ui-listview-filter-inset" );
	}

	wrapper.bind( "submit", function() {
		return false;
	})
	.insertBefore( list );
});

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.slider", $.mobile.widget, {
	widgetEventPrefix: "slide",

	options: {
		theme: null,
		trackTheme: null,
		disabled: false,
		initSelector: "input[type='range'], :jqmData(type='range'), :jqmData(role='slider')",
		mini: false
	},

	_create: function() {

		// TODO: Each of these should have comments explain what they're for
		var self = this,

			control = this.element,

			parentTheme = $.mobile.getInheritedTheme( control, "c" ),

			theme = this.options.theme || parentTheme,

			trackTheme = this.options.trackTheme || parentTheme,

			cType = control[ 0 ].nodeName.toLowerCase(),

			selectClass = ( cType === "select" ) ? "ui-slider-switch" : "",

			controlID = control.attr( "id" ),

			$label = $( "[for='" + controlID + "']" ),

			labelID = $label.attr( "id" ) || controlID + "-label",

			label = $label.attr( "id", labelID ),

			val = function() {
				return  cType === "input"  ? parseFloat( control.val() ) : control[0].selectedIndex;
			},

			min =  cType === "input" ? parseFloat( control.attr( "min" ) ) : 0,

			max =  cType === "input" ? parseFloat( control.attr( "max" ) ) : control.find( "option" ).length-1,

			step = window.parseFloat( control.attr( "step" ) || 1 ),

			inlineClass = ( this.options.inline || control.jqmData( "inline" ) === true ) ? " ui-slider-inline" : "",

			miniClass = ( this.options.mini || control.jqmData( "mini" ) ) ? " ui-slider-mini" : "",


			domHandle = document.createElement( 'a' ),
			handle = $( domHandle ),
			domSlider = document.createElement( 'div' ),
			slider = $( domSlider ),

			valuebg = control.jqmData( "highlight" ) && cType !== "select" ? (function() {
				var bg = document.createElement('div');
				bg.className = 'ui-slider-bg ' + $.mobile.activeBtnClass + ' ui-btn-corner-all';
				return $( bg ).prependTo( slider );
			})() : false,

			options;

		this._type = cType;

		domHandle.setAttribute( 'href', "#" );
		domSlider.setAttribute('role','application');
		domSlider.className = ['ui-slider ',selectClass," ui-btn-down-",trackTheme,' ui-btn-corner-all', inlineClass, miniClass].join( "" );
		domHandle.className = 'ui-slider-handle';
		domSlider.appendChild( domHandle );

		handle.buttonMarkup({ corners: true, theme: theme, shadow: true })
				.attr({
					"role": "slider",
					"aria-valuemin": min,
					"aria-valuemax": max,
					"aria-valuenow": val(),
					"aria-valuetext": val(),
					"title": val(),
					"aria-labelledby": labelID
				});

		$.extend( this, {
			slider: slider,
			handle: handle,
			valuebg: valuebg,
			dragging: false,
			beforeStart: null,
			userModified: false,
			mouseMoved: false
		});

		if ( cType === "select" ) {
			var wrapper = document.createElement('div');
			wrapper.className = 'ui-slider-inneroffset';

			for ( var j = 0,length = domSlider.childNodes.length;j < length;j++ ) {
				wrapper.appendChild( domSlider.childNodes[j] );
			}

			domSlider.appendChild( wrapper );

			// slider.wrapInner( "<div class='ui-slider-inneroffset'></div>" );

			// make the handle move with a smooth transition
			handle.addClass( "ui-slider-handle-snapping" );

			options = control.find( "option" );

			for ( var i = 0, optionsCount = options.length; i < optionsCount; i++ ) {
				var side = !i ? "b" : "a",
					sliderTheme = !i ? " ui-btn-down-" + trackTheme : ( " " + $.mobile.activeBtnClass ),
					sliderLabel = document.createElement( 'div' ),
					sliderImg = document.createElement( 'span' );

				sliderImg.className = ['ui-slider-label ui-slider-label-',side,sliderTheme," ui-btn-corner-all"].join( "" );
				sliderImg.setAttribute('role','img');
				sliderImg.appendChild( document.createTextNode( options[i].innerHTML ) );
				$(sliderImg).prependTo( slider );
			}

			self._labels = $( ".ui-slider-label", slider );

		}

		label.addClass( "ui-slider" );

		// monitor the input for updated values
		control.addClass( cType === "input" ? "ui-slider-input" : "ui-slider-switch" )
			.change(function() {
				// if the user dragged the handle, the "change" event was triggered from inside refresh(); don't call refresh() again
				if ( !self.mouseMoved ) {
					self.refresh( val(), true );
				}
			})
			.keyup(function() { // necessary?
				self.refresh( val(), true, true );
			})
			.blur(function() {
				self.refresh( val(), true );
			});

		this._preventDocumentDrag = function( event ) {
			// NOTE: we don't do this in refresh because we still want to
			//       support programmatic alteration of disabled inputs
			if ( self.dragging && !self.options.disabled ) {

				// self.mouseMoved must be updated before refresh() because it will be used in the control "change" event
				self.mouseMoved = true;

				if ( cType === "select" ) {
					// make the handle move in sync with the mouse
					handle.removeClass( "ui-slider-handle-snapping" );
				}

				self.refresh( event );

				// only after refresh() you can calculate self.userModified
				self.userModified = self.beforeStart !== control[0].selectedIndex;
				return false;
			}
		}

		this._on( $( document ), { "vmousemove": this._preventDocumentDrag });

		// it appears the clicking the up and down buttons in chrome on
		// range/number inputs doesn't trigger a change until the field is
		// blurred. Here we check thif the value has changed and refresh
		control.bind( "vmouseup", $.proxy( self._checkedRefresh, self));

		slider.bind( "vmousedown", function( event ) {
			// NOTE: we don't do this in refresh because we still want to
			//       support programmatic alteration of disabled inputs
			if ( self.options.disabled ) {
				return false;
			}

			self.dragging = true;
			self.userModified = false;
			self.mouseMoved = false;

			if ( cType === "select" ) {
				self.beforeStart = control[0].selectedIndex;
			}

			self.refresh( event );
			self._trigger( "start" );
			return false;
		})
		.bind( "vclick", false );

		this._sliderMouseUp = function() {
			if ( self.dragging ) {
				self.dragging = false;

				if ( cType === "select") {
					// make the handle move with a smooth transition
					handle.addClass( "ui-slider-handle-snapping" );

					if ( self.mouseMoved ) {
						// this is a drag, change the value only if user dragged enough
						if ( self.userModified ) {
						    self.refresh( self.beforeStart === 0 ? 1 : 0 );
						}
						else {
						    self.refresh( self.beforeStart );
						}
					}
					else {
						// this is just a click, change the value
						self.refresh( self.beforeStart === 0 ? 1 : 0 );
					}
				}

				self.mouseMoved = false;
				self._trigger( "stop" );
				return false;
			}
		};

		this._on( slider.add( document ), { "vmouseup": this._sliderMouseUp });
		slider.insertAfter( control );

		// Only add focus class to toggle switch, sliders get it automatically from ui-btn
		if ( cType === 'select' ) {
			this.handle.bind({
				focus: function() {
					slider.addClass( $.mobile.focusClass );
				},

				blur: function() {
					slider.removeClass( $.mobile.focusClass );
				}
			});
		}

		this.handle.bind({
			// NOTE force focus on handle
			vmousedown: function() {
				$( this ).focus();
			},

			vclick: false,

			keydown: function( event ) {
				var index = val();

				if ( self.options.disabled ) {
					return;
				}

				// In all cases prevent the default and mark the handle as active
				switch ( event.keyCode ) {
					case $.mobile.keyCode.HOME:
					case $.mobile.keyCode.END:
					case $.mobile.keyCode.PAGE_UP:
					case $.mobile.keyCode.PAGE_DOWN:
					case $.mobile.keyCode.UP:
					case $.mobile.keyCode.RIGHT:
					case $.mobile.keyCode.DOWN:
					case $.mobile.keyCode.LEFT:
						event.preventDefault();

						if ( !self._keySliding ) {
							self._keySliding = true;
							$( this ).addClass( "ui-state-active" );
						}
						break;
				}

				// move the slider according to the keypress
				switch ( event.keyCode ) {
					case $.mobile.keyCode.HOME:
						self.refresh( min );
						break;
					case $.mobile.keyCode.END:
						self.refresh( max );
						break;
					case $.mobile.keyCode.PAGE_UP:
					case $.mobile.keyCode.UP:
					case $.mobile.keyCode.RIGHT:
						self.refresh( index + step );
						break;
					case $.mobile.keyCode.PAGE_DOWN:
					case $.mobile.keyCode.DOWN:
					case $.mobile.keyCode.LEFT:
						self.refresh( index - step );
						break;
				}
			}, // remove active mark

			keyup: function( event ) {
				if ( self._keySliding ) {
					self._keySliding = false;
					$( this ).removeClass( "ui-state-active" );
				}
			}
			});

		this.refresh( undefined, undefined, true );
	},

	_checkedRefresh: function() {
		if( this.value != this._value() ){
			this.refresh( this._value() );
		}
	},

	_value: function() {
		return  this._type === "input" ?
			parseFloat( this.element.val() ) : this.element[0].selectedIndex;
	},

	refresh: function( val, isfromControl, preventInputUpdate ) {

		// NOTE: we don't return here because we want to support programmatic
		//       alteration of the input value, which should still update the slider
		if ( this.options.disabled || this.element.attr('disabled')) {
			this.disable();
		}

		// set the stored value for comparison later
		this.value = this._value();

		var control = this.element, percent,
			cType = control[0].nodeName.toLowerCase(),
			min = cType === "input" ? parseFloat( control.attr( "min" ) ) : 0,
			max = cType === "input" ? parseFloat( control.attr( "max" ) ) : control.find( "option" ).length - 1,
			step = ( cType === "input" && parseFloat( control.attr( "step" ) ) > 0 ) ? parseFloat( control.attr( "step" ) ) : 1;

		if ( typeof val === "object" ) {
			var data = val,
				// a slight tolerance helped get to the ends of the slider
				tol = 8;
			if ( !this.dragging ||
					data.pageX < this.slider.offset().left - tol ||
					data.pageX > this.slider.offset().left + this.slider.width() + tol ) {
				return;
			}
			percent = Math.round( ( ( data.pageX - this.slider.offset().left ) / this.slider.width() ) * 100 );
		} else {
			if ( val == null ) {
				val = cType === "input" ? parseFloat( control.val() || 0 ) : control[0].selectedIndex;
			}
			percent = ( parseFloat( val ) - min ) / ( max - min ) * 100;
		}

		if ( isNaN( percent ) ) {
			return;
		}

		if ( percent < 0 ) {
			percent = 0;
		}

		if ( percent > 100 ) {
			percent = 100;
		}

		var newval = ( percent / 100 ) * ( max - min ) + min;

		//from jQuery UI slider, the following source will round to the nearest step
		var valModStep = ( newval - min ) % step;
		var alignValue = newval - valModStep;

		if ( Math.abs( valModStep ) * 2 >= step ) {
			alignValue += ( valModStep > 0 ) ? step : ( -step );
		}
		// Since JavaScript has problems with large floats, round
		// the final value to 5 digits after the decimal point (see jQueryUI: #4124)
		newval = parseFloat( alignValue.toFixed(5) );

		if ( newval < min ) {
			newval = min;
		}

		if ( newval > max ) {
			newval = max;
		}

		this.handle.css( "left", percent + "%" );
		this.handle.attr( {
				"aria-valuenow": cType === "input" ? newval : control.find( "option" ).eq( newval ).attr( "value" ),
				"aria-valuetext": cType === "input" ? newval : control.find( "option" ).eq( newval ).getEncodedText(),
				title: cType === "input" ? newval : control.find( "option" ).eq( newval ).getEncodedText()
			});

		if ( this.valuebg ) {
			this.valuebg.css( "width", percent + "%" );
		}

		// drag the label widths
		if ( this._labels ) {
			var handlePercent = this.handle.width() / this.slider.width() * 100,
				aPercent = percent && handlePercent + ( 100 - handlePercent ) * percent / 100,
				bPercent = percent === 100 ? 0 : Math.min( handlePercent + 100 - aPercent, 100 );

			this._labels.each(function() {
				var ab = $( this ).is( ".ui-slider-label-a" );
				$( this ).width( ( ab ? aPercent : bPercent  ) + "%" );
			});
		}

		if ( !preventInputUpdate ) {
			var valueChanged = false;

			// update control"s value
			if ( cType === "input" ) {
				valueChanged = control.val() !== newval;
				control.val( newval );
			} else {
				valueChanged = control[ 0 ].selectedIndex !== newval;
				control[ 0 ].selectedIndex = newval;
			}
			if ( !isfromControl && valueChanged ) {
				control.trigger( "change" );
			}
		}
	},

	enable: function() {
		this.element.attr( "disabled", false );
		this.slider.removeClass( "ui-disabled" ).attr( "aria-disabled", false );
		return this._setOption( "disabled", false );
	},

	disable: function() {
		this.element.attr( "disabled", true );
		this.slider.addClass( "ui-disabled" ).attr( "aria-disabled", true );
		return this._setOption( "disabled", true );
	}

});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.slider.prototype.enhanceWithin( e.target, true );
});

})( jQuery );

(function( $, undefined ) {

$.widget( "mobile.selectmenu", $.mobile.widget, {
	options: {
		theme: null,
		disabled: false,
		icon: "arrow-d",
		iconpos: "right",
		inline: false,
		corners: true,
		shadow: true,
		iconshadow: true,
		overlayTheme: "a",
		hidePlaceholderMenuItems: true,
		closeText: "Close",
		nativeMenu: true,
		// This option defaults to true on iOS devices.
		preventFocusZoom: /iPhone|iPad|iPod/.test( navigator.platform ) && navigator.userAgent.indexOf( "AppleWebKit" ) > -1,
		initSelector: "select:not( :jqmData(role='slider') )",
		mini: false
	},

	_button: function() {
		return $( "<div/>" );
	},

	_setDisabled: function( value ) {
		this.element.attr( "disabled", value );
		this.button.attr( "aria-disabled", value );
		return this._setOption( "disabled", value );
	},

	_focusButton : function() {
		var self = this;

		setTimeout( function() {
			self.button.focus();
		}, 40);
	},

	_selectOptions: function() {
		return this.select.find( "option" );
	},

	// setup items that are generally necessary for select menu extension
	_preExtension: function() {
		var classes = "";
		// TODO: Post 1.1--once we have time to test thoroughly--any classes manually applied to the original element should be carried over to the enhanced element, with an `-enhanced` suffix. See https://github.com/jquery/jquery-mobile/issues/3577
		/* if ( $el[0].className.length ) {
			classes = $el[0].className;
		} */
		if ( !!~this.element[0].className.indexOf( "ui-btn-left" ) ) {
			classes =  " ui-btn-left";
		}

		if (  !!~this.element[0].className.indexOf( "ui-btn-right" ) ) {
			classes = " ui-btn-right";
		}

		this.select = this.element.wrap( "<div class='ui-select" + classes + "'>" );
		this.selectID  = this.select.attr( "id" );
		this.label = $( "label[for='"+ this.selectID +"']" ).addClass( "ui-select" );
		this.isMultiple = this.select[ 0 ].multiple;
		if ( !this.options.theme ) {
			this.options.theme = $.mobile.getInheritedTheme( this.select, "c" );
		}
	},

	_create: function() {
		this._preExtension();

		// Allows for extension of the native select for custom selects and other plugins
		// see select.custom for example extension
		// TODO explore plugin registration
		this._trigger( "beforeCreate" );

		this.button = this._button();

		var self = this,

			options = this.options,

			inline = options.inline || this.select.jqmData( "inline" ),
			mini = options.mini || this.select.jqmData( "mini" ),
			iconpos = options.icon ? ( options.iconpos || this.select.jqmData( "iconpos" ) ) : false,

			// IE throws an exception at options.item() function when
			// there is no selected item
			// select first in this case
			selectedIndex = this.select[ 0 ].selectedIndex === -1 ? 0 : this.select[ 0 ].selectedIndex,

			// TODO values buttonId and menuId are undefined here
			button = this.button
				.insertBefore( this.select )
				.buttonMarkup( {
					theme: options.theme,
					icon: options.icon,
					iconpos: iconpos,
					inline: inline,
					corners: options.corners,
					shadow: options.shadow,
					iconshadow: options.iconshadow,
					mini: mini
				});

		this.setButtonText();

		// Opera does not properly support opacity on select elements
		// In Mini, it hides the element, but not its text
		// On the desktop,it seems to do the opposite
		// for these reasons, using the nativeMenu option results in a full native select in Opera
		if ( options.nativeMenu && window.opera && window.opera.version ) {
			button.addClass( "ui-select-nativeonly" );
		}

		// Add counter for multi selects
		if ( this.isMultiple ) {
			this.buttonCount = $( "<span>" )
				.addClass( "ui-li-count ui-btn-up-c ui-btn-corner-all" )
				.hide()
				.appendTo( button.addClass('ui-li-has-count') );
		}

		// Disable if specified
		if ( options.disabled || this.element.attr('disabled')) {
			this.disable();
		}

		// Events on native select
		this.select.change(function() {
			self.refresh();
		});

		this.build();
	},

	build: function() {
		var self = this;

		this.select
			.appendTo( self.button )
			.bind( "vmousedown", function() {
				// Add active class to button
				self.button.addClass( $.mobile.activeBtnClass );
			})
			.bind( "focus", function() {
				self.button.addClass( $.mobile.focusClass );
			})
			.bind( "blur", function() {
				self.button.removeClass( $.mobile.focusClass );
			})
			.bind( "focus vmouseover", function() {
				self.button.trigger( "vmouseover" );
			})
			.bind( "vmousemove", function() {
				// Remove active class on scroll/touchmove
				self.button.removeClass( $.mobile.activeBtnClass );
			})
			.bind( "change blur vmouseout", function() {
				self.button.trigger( "vmouseout" )
					.removeClass( $.mobile.activeBtnClass );
			})
			.bind( "change blur", function() {
				self.button.removeClass( "ui-btn-down-" + self.options.theme );
			});

		// In many situations, iOS will zoom into the select upon tap, this prevents that from happening
		self.button.bind( "vmousedown", function() {
			if ( self.options.preventFocusZoom ) {
				$.mobile.zoom.disable( true );
			}
		}).bind( "mouseup", function() {
			if ( self.options.preventFocusZoom ) {
				setTimeout(function() {
					$.mobile.zoom.enable( true );
				}, 0);
			}
		});
	},

	selected: function() {
		return this._selectOptions().filter( ":selected" );
	},

	selectedIndices: function() {
		var self = this;

		return this.selected().map(function() {
			return self._selectOptions().index( this );
		}).get();
	},

	setButtonText: function() {
		var self = this,
			selected = this.selected(),
			text = this.placeholder,
			span = $( document.createElement( "span" ) );

		this.button.find( ".ui-btn-text" ).html(function() {
			if ( selected.length ) {
				text = selected.map(function() {
					return $( this ).text();
				}).get().join( ", " );
			} else {
				text = self.placeholder;
			}

			// TODO possibly aggregate multiple select option classes
			return span.text( text )
				.addClass( self.select.attr( "class" ) )
				.addClass( selected.attr( "class" ) );
		});
	},

	setButtonCount: function() {
		var selected = this.selected();

		// multiple count inside button
		if ( this.isMultiple ) {
			this.buttonCount[ selected.length > 1 ? "show" : "hide" ]().text( selected.length );
		}
	},

	refresh: function() {
		this.setButtonText();
		this.setButtonCount();
	},

	// open and close preserved in native selects
	// to simplify users code when looping over selects
	open: $.noop,
	close: $.noop,

	disable: function() {
		this._setDisabled( true );
		this.button.addClass( "ui-disabled" );
	},

	enable: function() {
		this._setDisabled( false );
		this.button.removeClass( "ui-disabled" );
	}
});

//auto self-init widgets
$( document ).bind( "pagecreate create", function( e ) {
	$.mobile.selectmenu.prototype.enhanceWithin( e.target, true );
});
})( jQuery );

/*
* custom "selectmenu" plugin
*/

(function( $, undefined ) {
	var extendSelect = function( widget ) {

		var select = widget.select,
			selectID  = widget.selectID,
			label = widget.label,
			thisPage = widget.select.closest( ".ui-page" ),
			selectOptions = widget._selectOptions(),
			isMultiple = widget.isMultiple = widget.select[ 0 ].multiple,
			buttonId = selectID + "-button",
			menuId = selectID + "-menu",
			menuPage = $( "<div data-" + $.mobile.ns + "role='dialog' data-" +$.mobile.ns + "theme='"+ widget.options.theme +"' data-" +$.mobile.ns + "overlay-theme='"+ widget.options.overlayTheme +"'>" +
				"<div data-" + $.mobile.ns + "role='header'>" +
				"<div class='ui-title'>" + label.getEncodedText() + "</div>"+
				"</div>"+
				"<div data-" + $.mobile.ns + "role='content'></div>"+
				"</div>" ),

			listbox =  $( "<div>", { "class": "ui-selectmenu" } ).insertAfter( widget.select ).popup( { theme: "a" } ),

			list = $( "<ul>", {
				"class": "ui-selectmenu-list",
				"id": menuId,
				"role": "listbox",
				"aria-labelledby": buttonId
			}).attr( "data-" + $.mobile.ns + "theme", widget.options.theme ).appendTo( listbox ),

			header = $( "<div>", {
				"class": "ui-header ui-bar-" + widget.options.theme
			}).prependTo( listbox ),

			headerTitle = $( "<h1>", {
				"class": "ui-title"
			}).appendTo( header ),

			menuPageContent,
			menuPageClose,
			headerClose;

		if ( widget.isMultiple ) {
			headerClose = $( "<a>", {
				"text": widget.options.closeText,
				"href": "#",
				"class": "ui-btn-left"
			}).attr( "data-" + $.mobile.ns + "iconpos", "notext" ).attr( "data-" + $.mobile.ns + "icon", "delete" ).appendTo( header ).buttonMarkup();
		}

		$.extend( widget, {
			select: widget.select,
			selectID: selectID,
			buttonId: buttonId,
			menuId: menuId,
			thisPage: thisPage,
			menuPage: menuPage,
			label: label,
			selectOptions: selectOptions,
			isMultiple: isMultiple,
			theme: widget.options.theme,
			listbox: listbox,
			list: list,
			header: header,
			headerTitle: headerTitle,
			headerClose: headerClose,
			menuPageContent: menuPageContent,
			menuPageClose: menuPageClose,
			placeholder: "",

			build: function() {
				var self = this;

				// Create list from select, update state
				self.refresh();

				self.select.attr( "tabindex", "-1" ).focus(function() {
					$( this ).blur();
					self.button.focus();
				});

				// Button events
				self.button.bind( "vclick keydown" , function( event ) {
					if (event.type === "vclick" ||
							event.keyCode && (event.keyCode === $.mobile.keyCode.ENTER ||
																event.keyCode === $.mobile.keyCode.SPACE)) {

						self.open();
						event.preventDefault();
					}
				});

				// Events for list items
				self.list.attr( "role", "listbox" )
					.bind( "focusin", function( e ) {
						$( e.target )
							.attr( "tabindex", "0" )
							.trigger( "vmouseover" );

					})
					.bind( "focusout", function( e ) {
						$( e.target )
							.attr( "tabindex", "-1" )
							.trigger( "vmouseout" );
					})
					.delegate( "li:not(.ui-disabled, .ui-li-divider)", "click", function( event ) {

						// index of option tag to be selected
						var oldIndex = self.select[ 0 ].selectedIndex,
							newIndex = self.list.find( "li:not(.ui-li-divider)" ).index( this ),
							option = self._selectOptions().eq( newIndex )[ 0 ];

						// toggle selected status on the tag for multi selects
						option.selected = self.isMultiple ? !option.selected : true;

						// toggle checkbox class for multiple selects
						if ( self.isMultiple ) {
							$( this ).find( ".ui-icon" )
								.toggleClass( "ui-icon-checkbox-on", option.selected )
								.toggleClass( "ui-icon-checkbox-off", !option.selected );
						}

						// trigger change if value changed
						if ( self.isMultiple || oldIndex !== newIndex ) {
							self.select.trigger( "change" );
						}

						// hide custom select for single selects only - otherwise focus clicked item
						// We need to grab the clicked item the hard way, because the list may have been rebuilt
						if ( self.isMultiple ) {
							self.list.find( "li:not(.ui-li-divider)" ).eq( newIndex )
								.addClass( "ui-btn-down-" + widget.options.theme ).find( "a" ).first().focus();
						}
						else {
							self.close();
						}

						event.preventDefault();
					})
					.keydown(function( event ) {  //keyboard events for menu items
						var target = $( event.target ),
							li = target.closest( "li" ),
							prev, next;

						// switch logic based on which key was pressed
						switch ( event.keyCode ) {
							// up or left arrow keys
						case 38:
							prev = li.prev().not( ".ui-selectmenu-placeholder" );

							if ( prev.is( ".ui-li-divider" ) ) {
								prev = prev.prev();
							}

							// if there's a previous option, focus it
							if ( prev.length ) {
								target
									.blur()
									.attr( "tabindex", "-1" );

								prev.addClass( "ui-btn-down-" + widget.options.theme ).find( "a" ).first().focus();
							}

							return false;
							// down or right arrow keys
						case 40:
							next = li.next();

							if ( next.is( ".ui-li-divider" ) ) {
								next = next.next();
							}

							// if there's a next option, focus it
							if ( next.length ) {
								target
									.blur()
									.attr( "tabindex", "-1" );

								next.addClass( "ui-btn-down-" + widget.options.theme ).find( "a" ).first().focus();
							}

							return false;
							// If enter or space is pressed, trigger click
						case 13:
						case 32:
							target.trigger( "click" );

							return false;
						}
					});

				// button refocus ensures proper height calculation
				// by removing the inline style and ensuring page inclusion
				self.menuPage.bind( "pagehide", function() {
					self.list.appendTo( self.listbox );
					self._focusButton();

					// TODO centralize page removal binding / handling in the page plugin.
					// Suggestion from @jblas to do refcounting
					//
					// TODO extremely confusing dependency on the open method where the pagehide.remove
					// bindings are stripped to prevent the parent page from disappearing. The way
					// we're keeping pages in the DOM right now sucks
					//
					// rebind the page remove that was unbound in the open function
					// to allow for the parent page removal from actions other than the use
					// of a dialog sized custom select
					//
					// doing this here provides for the back button on the custom select dialog
					$.mobile._bindPageRemove.call( self.thisPage );
				});

				// Events on the popup
				self.listbox.bind( "popupafterclose", function( event ) {
					self.close();
				});

				// Close button on small overlays
				if ( self.isMultiple ) {
					self.headerClose.click(function() {
						if ( self.menuType === "overlay" ) {
							self.close();
							return false;
						}
					});
				}

				// track this dependency so that when the parent page
				// is removed on pagehide it will also remove the menupage
				self.thisPage.addDependents( this.menuPage );
			},

			_isRebuildRequired: function() {
				var list = this.list.find( "li" ),
					options = this._selectOptions();

				// TODO exceedingly naive method to determine difference
				// ignores value changes etc in favor of a forcedRebuild
				// from the user in the refresh method
				return options.text() !== list.text();
			},

			selected: function() {
				return this._selectOptions().filter( ":selected:not( :jqmData(placeholder='true') )" );
			},

			refresh: function( forceRebuild , foo ) {
				var self = this,
				select = this.element,
				isMultiple = this.isMultiple,
				indicies;

				if (  forceRebuild || this._isRebuildRequired() ) {
					self._buildList();
				}

				indicies = this.selectedIndices();

				self.setButtonText();
				self.setButtonCount();

				self.list.find( "li:not(.ui-li-divider)" )
					.removeClass( $.mobile.activeBtnClass )
					.attr( "aria-selected", false )
					.each(function( i ) {

						if ( $.inArray( i, indicies ) > -1 ) {
							var item = $( this );

							// Aria selected attr
							item.attr( "aria-selected", true );

							// Multiple selects: add the "on" checkbox state to the icon
							if ( self.isMultiple ) {
								item.find( ".ui-icon" ).removeClass( "ui-icon-checkbox-off" ).addClass( "ui-icon-checkbox-on" );
							} else {
								if ( item.is( ".ui-selectmenu-placeholder" ) ) {
									item.next().addClass( $.mobile.activeBtnClass );
								} else {
									item.addClass( $.mobile.activeBtnClass );
								}
							}
						}
					});
			},

			close: function() {
				if ( this.options.disabled || !this.isOpen ) {
					return;
				}

				var self = this;

				if ( self.menuType === "page" ) {
					// doesn't solve the possible issue with calling change page
					// where the objects don't define data urls which prevents dialog key
					// stripping - changePage has incoming refactor
					$.mobile.back();
				} else {
					self.listbox.popup( "close" );
					self.list.appendTo( self.listbox );
					self._focusButton();
				}

				// allow the dialog to be closed again
				self.isOpen = false;
			},

			open: function() {
				if ( this.options.disabled ) {
					return;
				}

				var self = this,
					$window = $( window ),
					selfListParent = self.list.parent(),
					menuHeight = selfListParent.outerHeight(),
					menuWidth = selfListParent.outerWidth(),
					activePage = $( "." + $.mobile.activePageClass ),
					scrollTop = $window.scrollTop(),
					btnOffset = self.button.offset().top,
					screenHeight = $window.height(),
					screenWidth = $window.width();

				//add active class to button
				self.button.addClass( $.mobile.activeBtnClass );

				//remove after delay
				setTimeout( function() {
					self.button.removeClass( $.mobile.activeBtnClass );
				}, 300);

				function focusMenuItem() {
					var selector = self.list.find( "." + $.mobile.activeBtnClass + " a" );
					if ( selector.length === 0 ) {
						selector = self.list.find( "li.ui-btn:not( :jqmData(placeholder='true') ) a" );
					}
					selector.first().focus().closest( "li" ).addClass( "ui-btn-down-" + widget.options.theme );
				}

				if ( menuHeight > screenHeight - 80 || !$.support.scrollTop ) {

					self.menuPage.appendTo( $.mobile.pageContainer ).page();
					self.menuPageContent = menuPage.find( ".ui-content" );
					self.menuPageClose = menuPage.find( ".ui-header a" );

					// prevent the parent page from being removed from the DOM,
					// otherwise the results of selecting a list item in the dialog
					// fall into a black hole
					self.thisPage.unbind( "pagehide.remove" );

					//for WebOS/Opera Mini (set lastscroll using button offset)
					if ( scrollTop === 0 && btnOffset > screenHeight ) {
						self.thisPage.one( "pagehide", function() {
							$( this ).jqmData( "lastScroll", btnOffset );
						});
					}

					self.menuPage.one( "pageshow", function() {
						focusMenuItem();
						self.isOpen = true;
					});

					self.menuType = "page";
					self.menuPageContent.append( self.list );
					self.menuPage.find("div .ui-title").text(self.label.text());
					$.mobile.changePage( self.menuPage, {
						transition: $.mobile.defaultDialogTransition
					});
				} else {
					self.menuType = "overlay";

					self.listbox
						.one( "popupafteropen", focusMenuItem )
						.popup( "open", {
							x: self.button.offset().left + self.button.outerWidth() / 2,
							y: self.button.offset().top + self.button.outerHeight() / 2
						});

					// duplicate with value set in page show for dialog sized selects
					self.isOpen = true;
				}
			},

			_buildList: function() {
				var self = this,
					o = this.options,
					placeholder = this.placeholder,
					needPlaceholder = true,
					optgroups = [],
					lis = [],
					dataIcon = self.isMultiple ? "checkbox-off" : "false";

				self.list.empty().filter( ".ui-listview" ).listview( "destroy" );

				var $options = self.select.find( "option" ),
					numOptions = $options.length,
					select = this.select[ 0 ],
					dataPrefix = 'data-' + $.mobile.ns,
					dataIndexAttr = dataPrefix + 'option-index',
					dataIconAttr = dataPrefix + 'icon',
					dataRoleAttr = dataPrefix + 'role',
					dataPlaceholderAttr = dataPrefix + 'placeholder',
					fragment = document.createDocumentFragment(),
					isPlaceholderItem = false,
					optGroup;

				for (var i = 0; i < numOptions;i++, isPlaceholderItem = false) {
					var option = $options[i],
						$option = $( option ),
						parent = option.parentNode,
						text = $option.text(),
						anchor  = document.createElement( 'a' ),
						classes = [];

					anchor.setAttribute( 'href', '#' );
					anchor.appendChild( document.createTextNode( text ) );

					// Are we inside an optgroup?
					if ( parent !== select && parent.nodeName.toLowerCase() === "optgroup" ) {
						var optLabel = parent.getAttribute( 'label' );
						if ( optLabel !== optGroup ) {
							var divider = document.createElement( 'li' );
							divider.setAttribute( dataRoleAttr, 'list-divider' );
							divider.setAttribute( 'role', 'option' );
							divider.setAttribute( 'tabindex', '-1' );
							divider.appendChild( document.createTextNode( optLabel ) );
							fragment.appendChild( divider );
							optGroup = optLabel;
						}
					}

					if ( needPlaceholder && ( !option.getAttribute( "value" ) || text.length === 0 || $option.jqmData( "placeholder" ) ) ) {
						needPlaceholder = false;
						isPlaceholderItem = true;

						// If we have identified a placeholder, mark it retroactively in the select as well
						option.setAttribute( dataPlaceholderAttr, true );
						if ( o.hidePlaceholderMenuItems ) {
							classes.push( "ui-selectmenu-placeholder" );
						}
						if (!placeholder) {
							placeholder = self.placeholder = text;
						}
					}

					var item = document.createElement('li');
					if ( option.disabled ) {
						classes.push( "ui-disabled" );
						item.setAttribute('aria-disabled',true);
					}
					item.setAttribute( dataIndexAttr,i );
					item.setAttribute( dataIconAttr, dataIcon );
					if ( isPlaceholderItem ) {
						item.setAttribute( dataPlaceholderAttr, true );
					}
					item.className = classes.join( " " );
					item.setAttribute( 'role', 'option' );
					anchor.setAttribute( 'tabindex', '-1' );
					item.appendChild( anchor );
					fragment.appendChild( item );
				}

				self.list[0].appendChild( fragment );

				// Hide header if it's not a multiselect and there's no placeholder
				if ( !this.isMultiple && !placeholder.length ) {
					this.header.hide();
				} else {
					this.headerTitle.text( this.placeholder );
				}

				// Now populated, create listview
				self.list.listview();
			},

			_button: function() {
				return $( "<a>", {
					"href": "#",
					"role": "button",
					// TODO value is undefined at creation
					"id": this.buttonId,
					"aria-haspopup": "true",

					// TODO value is undefined at creation
					"aria-owns": this.menuId
				});
			}
		});
	};

	// issue #3894 - core doesn't trigger events on disabled delegates
	$( document ).bind( "selectmenubeforecreate", function( event ) {
		var selectmenuWidget = $( event.target ).data( "selectmenu" );

		if ( !selectmenuWidget.options.nativeMenu &&
				selectmenuWidget.element.parents( ":jqmData(role='popup')" ).length === 0 ) {
			extendSelect( selectmenuWidget );
		}
	});
})( jQuery );

(function( $, undefined ) {


	$.widget( "mobile.fixedtoolbar", $.mobile.widget, {
		options: {
			visibleOnPageShow: true,
			disablePageZoom: true,
			transition: "slide", //can be none, fade, slide (slide maps to slideup or slidedown)
			fullscreen: false,
			tapToggle: true,
			tapToggleBlacklist: "a, button, input, select, textarea, .ui-header-fixed, .ui-footer-fixed, .ui-popup",
			hideDuringFocus: "input, textarea, select",
			updatePagePadding: true,
			trackPersistentToolbars: true,

			// Browser detection! Weeee, here we go...
			// Unfortunately, position:fixed is costly, not to mention probably impossible, to feature-detect accurately.
			// Some tests exist, but they currently return false results in critical devices and browsers, which could lead to a broken experience.
			// Testing fixed positioning is also pretty obtrusive to page load, requiring injected elements and scrolling the window
			// The following function serves to rule out some popular browsers with known fixed-positioning issues
			// This is a plugin option like any other, so feel free to improve or overwrite it
			supportBlacklist: function() {
				var w = window,
					ua = navigator.userAgent,
					platform = navigator.platform,
					// Rendering engine is Webkit, and capture major version
					wkmatch = ua.match( /AppleWebKit\/([0-9]+)/ ),
					wkversion = !!wkmatch && wkmatch[ 1 ],
					ffmatch = ua.match( /Fennec\/([0-9]+)/ ),
					ffversion = !!ffmatch && ffmatch[ 1 ],
					operammobilematch = ua.match( /Opera Mobi\/([0-9]+)/ ),
					omversion = !!operammobilematch && operammobilematch[ 1 ];

				if(
					// iOS 4.3 and older : Platform is iPhone/Pad/Touch and Webkit version is less than 534 (ios5)
					( ( platform.indexOf( "iPhone" ) > -1 || platform.indexOf( "iPad" ) > -1  || platform.indexOf( "iPod" ) > -1 ) && wkversion && wkversion < 534 ) ||
					// Opera Mini
					( w.operamini && ({}).toString.call( w.operamini ) === "[object OperaMini]" ) ||
					( operammobilematch && omversion < 7458 )	||
					//Android lte 2.1: Platform is Android and Webkit version is less than 533 (Android 2.2)
					( ua.indexOf( "Android" ) > -1 && wkversion && wkversion < 533 ) ||
					// Firefox Mobile before 6.0 -
					( ffversion && ffversion < 6 ) ||
					// WebOS less than 3
					( "palmGetResource" in window && wkversion && wkversion < 534 )	||
					// MeeGo
					( ua.indexOf( "MeeGo" ) > -1 && ua.indexOf( "NokiaBrowser/8.5.0" ) > -1 ) ) {
					return true;
				}

				return false;
			},
			initSelector: ":jqmData(position='fixed')"
		},

		_create: function() {

			var self = this,
				o = self.options,
				$el = self.element,
				tbtype = $el.is( ":jqmData(role='header')" ) ? "header" : "footer",
				$page = $el.closest( ".ui-page" );

			// Feature detecting support for
			if ( o.supportBlacklist() ) {
				self.destroy();
				return;
			}

			$el.addClass( "ui-"+ tbtype +"-fixed" );

			// "fullscreen" overlay positioning
			if ( o.fullscreen ) {
				$el.addClass( "ui-"+ tbtype +"-fullscreen" );
				$page.addClass( "ui-page-" + tbtype + "-fullscreen" );
			}
			// If not fullscreen, add class to page to set top or bottom padding
			else{
				$page.addClass( "ui-page-" + tbtype + "-fixed" );
			}

			self._addTransitionClass();
			self._bindPageEvents();
			self._bindToggleHandlers();
		},

		_addTransitionClass: function() {
			var tclass = this.options.transition;

			if ( tclass && tclass !== "none" ) {
				// use appropriate slide for header or footer
				if ( tclass === "slide" ) {
					tclass = this.element.is( ".ui-header" ) ? "slidedown" : "slideup";
				}

				this.element.addClass( tclass );
			}
		},

		_bindPageEvents: function() {
			var self = this,
				o = self.options,
				$el = self.element;

			//page event bindings
			// Fixed toolbars require page zoom to be disabled, otherwise usability issues crop up
			// This method is meant to disable zoom while a fixed-positioned toolbar page is visible
			$el.closest( ".ui-page" )
				.bind( "pagebeforeshow", function() {
					if ( o.disablePageZoom ) {
						$.mobile.zoom.disable( true );
					}
					if ( !o.visibleOnPageShow ) {
						self.hide( true );
					}
				} )
				.bind( "webkitAnimationStart animationstart updatelayout", function() {
					var thisPage = this;
					if ( o.updatePagePadding ) {
						self.updatePagePadding( thisPage );
					}
				})
				.bind( "pageshow", function() {
					var thisPage = this;
					self.updatePagePadding( thisPage );
					if ( o.updatePagePadding ) {
						$( window ).bind( "throttledresize." + self.widgetName, function() {
							self.updatePagePadding( thisPage );
						});
					}
				})
				.bind( "pagebeforehide", function( e, ui ) {
					if ( o.disablePageZoom ) {
						$.mobile.zoom.enable( true );
					}
					if ( o.updatePagePadding ) {
						$( window ).unbind( "throttledresize." + self.widgetName );
					}

					if ( o.trackPersistentToolbars ) {
						var thisFooter = $( ".ui-footer-fixed:jqmData(id)", this ),
							thisHeader = $( ".ui-header-fixed:jqmData(id)", this ),
							nextFooter = thisFooter.length && ui.nextPage && $( ".ui-footer-fixed:jqmData(id='" + thisFooter.jqmData( "id" ) + "')", ui.nextPage ) || $(),
							nextHeader = thisHeader.length && ui.nextPage && $( ".ui-header-fixed:jqmData(id='" + thisHeader.jqmData( "id" ) + "')", ui.nextPage ) || $();

							if ( nextFooter.length || nextHeader.length ) {

								nextFooter.add( nextHeader ).appendTo( $.mobile.pageContainer );

								ui.nextPage.one( "pageshow", function() {
									nextFooter.add( nextHeader ).appendTo( this );
								});
							}
					}
				});
		},

		_visible: true,

		// This will set the content element's top or bottom padding equal to the toolbar's height
		updatePagePadding: function( tbPage ) {
			var $el = this.element,
				header = $el.is( ".ui-header" );

			// This behavior only applies to "fixed", not "fullscreen"
			if ( this.options.fullscreen ) { return; }

			tbPage = tbPage || $el.closest( ".ui-page" );
			$( tbPage ).css( "padding-" + ( header ? "top" : "bottom" ), $el.outerHeight() );
		},

		_useTransition: function( notransition ) {
			var $win = $( window ),
				$el = this.element,
				scroll = $win.scrollTop(),
				elHeight = $el.height(),
				pHeight = $el.closest( ".ui-page" ).height(),
				viewportHeight = $.mobile.getScreenHeight(),
				tbtype = $el.is( ":jqmData(role='header')" ) ? "header" : "footer";

			return !notransition &&
				( this.options.transition && this.options.transition !== "none" &&
				(
					( tbtype === "header" && !this.options.fullscreen && scroll > elHeight ) ||
					( tbtype === "footer" && !this.options.fullscreen && scroll + viewportHeight < pHeight - elHeight )
				) || this.options.fullscreen
				);
		},

		show: function( notransition ) {
			var hideClass = "ui-fixed-hidden",
				$el = this.element;

			if ( this._useTransition( notransition ) ) {
				$el
					.removeClass( "out " + hideClass )
					.addClass( "in" );
			}
			else {
				$el.removeClass( hideClass );
			}
			this._visible = true;
		},

		hide: function( notransition ) {
			var hideClass = "ui-fixed-hidden",
				$el = this.element,
				// if it's a slide transition, our new transitions need the reverse class as well to slide outward
				outclass = "out" + ( this.options.transition === "slide" ? " reverse" : "" );

			if( this._useTransition( notransition ) ) {
				$el
					.addClass( outclass )
					.removeClass( "in" )
					.animationComplete(function() {
						$el.addClass( hideClass ).removeClass( outclass );
					});
			}
			else {
				$el.addClass( hideClass ).removeClass( outclass );
			}
			this._visible = false;
		},

		toggle: function() {
			this[ this._visible ? "hide" : "show" ]();
		},

		_bindToggleHandlers: function() {
			var self = this,
				o = self.options,
				$el = self.element;

			// tap toggle
			$el.closest( ".ui-page" )
				.bind( "vclick", function( e ) {
					if ( o.tapToggle && !$( e.target ).closest( o.tapToggleBlacklist ).length ) {
						self.toggle();
					}
				})
				.bind( "focusin focusout", function( e ) {
					if ( screen.width < 500 && $( e.target ).is( o.hideDuringFocus ) && !$( e.target ).closest( ".ui-header-fixed, .ui-footer-fixed" ).length ) {
						self[ ( e.type === "focusin" && self._visible ) ? "hide" : "show" ]();
					}
				});
		},

		destroy: function() {
			this.element.removeClass( "ui-header-fixed ui-footer-fixed ui-header-fullscreen ui-footer-fullscreen in out fade slidedown slideup ui-fixed-hidden" );
			this.element.closest( ".ui-page" ).removeClass( "ui-page-header-fixed ui-page-footer-fixed ui-page-header-fullscreen ui-page-footer-fullscreen" );
		}

	});

	//auto self-init widgets
	$( document )
		.bind( "pagecreate create", function( e ) {

			// DEPRECATED in 1.1: support for data-fullscreen=true|false on the page element.
			// This line ensures it still works, but we recommend moving the attribute to the toolbars themselves.
			if ( $( e.target ).jqmData( "fullscreen" ) ) {
				$( $.mobile.fixedtoolbar.prototype.options.initSelector, e.target ).not( ":jqmData(fullscreen)" ).jqmData( "fullscreen", true );
			}

			$.mobile.fixedtoolbar.prototype.enhanceWithin( e.target );
		});

})( jQuery );

(function( $, window ) {

	// This fix addresses an iOS bug, so return early if the UA claims it's something else.
	if ( !(/iPhone|iPad|iPod/.test( navigator.platform ) && navigator.userAgent.indexOf( "AppleWebKit" ) > -1 ) ) {
		return;
	}

  var zoom = $.mobile.zoom,
		evt, x, y, z, aig;

  function checkTilt( e ) {
		evt = e.originalEvent;
		aig = evt.accelerationIncludingGravity;

		x = Math.abs( aig.x );
		y = Math.abs( aig.y );
		z = Math.abs( aig.z );

		// If portrait orientation and in one of the danger zones
    if ( !window.orientation && ( x > 7 || ( ( z > 6 && y < 8 || z < 8 && y > 6 ) && x > 5 ) ) ) {
			if ( zoom.enabled ) {
				zoom.disable();
			}
    }	else if ( !zoom.enabled ) {
			zoom.enable();
    }
  }

  $( window )
		.bind( "orientationchange.iosorientationfix", zoom.enable )
		.bind( "devicemotion.iosorientationfix", checkTilt );

}( jQuery, this ));

(function( $, window, undefined ) {
	var	$html = $( "html" ),
			$head = $( "head" ),
			$window = $( window );

	//remove initial build class (only present on first pageshow)
	function hideRenderingClass() {
		$html.removeClass( "ui-mobile-rendering" );
	}

	// trigger mobileinit event - useful hook for configuring $.mobile settings before they're used
	$( window.document ).trigger( "mobileinit" );

	// support conditions
	// if device support condition(s) aren't met, leave things as they are -> a basic, usable experience,
	// otherwise, proceed with the enhancements
	if ( !$.mobile.gradeA() ) {
		return;
	}

	// override ajaxEnabled on platforms that have known conflicts with hash history updates
	// or generally work better browsing in regular http for full page refreshes (BB5, Opera Mini)
	if ( $.mobile.ajaxBlacklist ) {
		$.mobile.ajaxEnabled = false;
	}

	// Add mobile, initial load "rendering" classes to docEl
	$html.addClass( "ui-mobile ui-mobile-rendering" );

	// This is a fallback. If anything goes wrong (JS errors, etc), or events don't fire,
	// this ensures the rendering class is removed after 5 seconds, so content is visible and accessible
	setTimeout( hideRenderingClass, 5000 );

	$.extend( $.mobile, {
		// find and enhance the pages in the dom and transition to the first page.
		initializePage: function() {
			// find present pages
			var $pages = $( ":jqmData(role='page'), :jqmData(role='dialog')" ),
				hash = $.mobile.path.parseLocation().hash.replace("#", ""),
				hashPage = document.getElementById( hash );

			// if no pages are found, create one with body's inner html
			if ( !$pages.length ) {
				$pages = $( "body" ).wrapInner( "<div data-" + $.mobile.ns + "role='page'></div>" ).children( 0 );
			}

			// add dialogs, set data-url attrs
			$pages.each(function() {
				var $this = $( this );

				// unless the data url is already set set it to the pathname
				if ( !$this.jqmData( "url" ) ) {
					$this.attr( "data-" + $.mobile.ns + "url", $this.attr( "id" ) || location.pathname + location.search );
				}
			});

			// define first page in dom case one backs out to the directory root (not always the first page visited, but defined as fallback)
			$.mobile.firstPage = $pages.first();

			// define page container
			$.mobile.pageContainer = $pages.first().parent().addClass( "ui-mobile-viewport" );

			// alert listeners that the pagecontainer has been determined for binding
			// to events triggered on it
			$window.trigger( "pagecontainercreate" );

			// cue page loading message
			$.mobile.showPageLoadingMsg();

			//remove initial build class (only present on first pageshow)
			hideRenderingClass();

			// if hashchange listening is disabled, there's no hash deeplink,
			// the hash is not valid (contains more than one # or does not start with #)
			// or there is no page with that hash, change to the first page in the DOM
			// Remember, however, that the hash can also be a path!
			if ( ! ( $.mobile.hashListeningEnabled &&
				$.mobile.path.isHashValid( location.hash ) &&
				( $( hashPage ).is( ':jqmData(role="page")' ) ||
					$.mobile.path.isPath( hash ) ||
					hash === $.mobile.dialogHashKey ) ) ) {

				// Store the initial destination
				if ( $.mobile.path.isHashValid( location.hash ) ) {
					$.mobile.urlHistory.initialDst = hash.replace( "#", "" );
				}
				$.mobile.changePage( $.mobile.firstPage, { transition: "none", reverse: true, changeHash: false, fromHashChange: true } );
			}
			// otherwise, trigger a hashchange to load a deeplink
			else {
				$window.trigger( "hashchange", [ true ] );
			}
		}
	});

	// initialize events now, after mobileinit has occurred
	$.mobile.navreadyDeferred.resolve();

	// check which scrollTop value should be used by scrolling to 1 immediately at domready
	// then check what the scroll top is. Android will report 0... others 1
	// note that this initial scroll won't hide the address bar. It's just for the check.
	$(function() {
		window.scrollTo( 0, 1 );

		// if defaultHomeScroll hasn't been set yet, see if scrollTop is 1
		// it should be 1 in most browsers, but android treats 1 as 0 (for hiding addr bar)
		// so if it's 1, use 0 from now on
		$.mobile.defaultHomeScroll = ( !$.support.scrollTop || $( window ).scrollTop() === 1 ) ? 0 : 1;


		// TODO: Implement a proper registration mechanism with dependency handling in order to not have exceptions like the one below
		//auto self-init widgets for those widgets that have a soft dependency on others
		if ( $.fn.controlgroup ) {
			$( document ).bind( "pagecreate create", function( e ) {
				$( ":jqmData(role='controlgroup')", e.target )
					.jqmEnhanceable()
					.controlgroup({ excludeInvisible: false });
			});
		}

		//dom-ready inits
		if ( $.mobile.autoInitializePage ) {
			$.mobile.initializePage();
		}

		// window load event
		// hide iOS browser chrome on load
		$window.load( $.mobile.silentScroll );

		if ( !$.support.cssPointerEvents ) {
			// IE and Opera don't support CSS pointer-events: none that we use to disable link-based buttons
			// by adding the 'ui-disabled' class to them. Using a JavaScript workaround for those browser.
			// https://github.com/jquery/jquery-mobile/issues/3558

			$( document ).delegate( ".ui-disabled", "vclick",
				function( e ) {
					e.preventDefault();
					e.stopImmediatePropagation();
				}
			);
		}
	});
}( jQuery, this ));

}));



ready.js
========================


var rnc = rnc || {};

// The purpose of this method is to wait until both cordova deviceready and the jQuery document ready events have occurred
// then call the initialze
(function (rnc, $, document) {
  "use strict"

  var jqReady = $.Deferred(),
    pgReady = $.Deferred();

    rnc.onTheWeb = false;
    rnc.resolver = {
      /* Callback for when the app is ready */
      callback: null,

      /* Application Constructor */
      initialize: function (callback) {
        rnc.resolver.callback = callback;
        var browser = document.URL.match(/^https?:/);
        //if (browser) {
        //  console.log("Running on the web");
        //  rnc.onTheWeb = true;
        //  // In case of web, we ignore PG but resolve the Deferred Object to trigger initialization
        //  pgReady.resolve();
        //}
        //else {
        //  console.log("NOT running on the web");
        //  this.bindEvents();
        //}
          rnc.onTheWeb = true;
          pgReady.resolve();
      },
      bindEvents: function () {
        document.addEventListener("deviceready", this.onDeviceReady, false);
      },
      onDeviceReady: function () {
        /* The scope of 'this' is the event, hence we need to use rnc. */
        rnc.resolver.receivedEvent("deviceready");
      },
      receivedEvent: function (event) {
        switch (event) {
          case "deviceready":
            pgReady.resolve();
            break;
        }
      }
    };

  $(document).ready(function () {
    console.log("document ready");
    jqReady.resolve();
  });

  $.when(jqReady, pgReady).then(function () {
    console.log("Frameworks ready.");
    /* both frameworks have initialized, so call the callback if one exists */
    if (rnc.resolver.callback) {
      rnc.resolver.callback();
    }
  });
}(rnc, jQuery, document));
