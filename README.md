# NTQ
Nutritional Therapy Questionnaire
<!DOCTYPE html>

<html>

<head>
	<meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Corinna Venturi">

	<title>Nutritional Therapy Questionnaire</title>

	<style>

		fieldset {background:lightgray; border:10px solid gray; margin-bottom:10px; width:720px}
			label {width:180px; display:inline-block; text-align:right; vertical-align:top}
			label:hover {font-size:20px}
			input:hover {font-size:20px}
			textarea {width:360px; height:50px}
			.nice {vertical-align:top; text-align:center; background:lightpink}
			.nicer {vertical-align:top; text-align:center; background:lightblue}
			.aw {width:auto}
			div {
				margin-top: 10px;
			    margin-bottom: 10px;
			    margin-right: 8px;
			    margin-left: 8px;
				}
			body {
				font-family: sans-serif;
				}
			body {
				margin-left:auto;
				margin-right:auto;
				width:80%;
				}
			td {width:500px}
	</style>
</head>

<body>
	<h2>Nutritional Therapy Questionnaire for LDN Nutrition</h2>
	<h3>Please complete all relevant areas concerning health, diet and lifestyle.  Unless otherwise stated, all fields are optional.  Please note that any information given is treated with the strictest confidentiality.  Form may take up to 30 minutes to complete:</h3>
<!--I THINK SERVER INFO MIGHT GO HERE BUT NOT SURE-->
<div type="container">
	<form method="post" action="">
    
    
		<fieldset>
			<legend>GENERAL INFORMATION</legend>
				<div>
					<label for="name">Name:<br>
					<span style="font-size: 11px">(required)</span></label>
					</label>
					<input type="text" name="name" required>
				</div>	

				<div>
					<label for="sex">Sex:<br>
					<span style="font-size: 11px">(required)</span></label>
					Female <input type="radio" gender="female" name="gender" checked>
					Male <input type="radio" gender="male" name="gender">
				</div>

				<div>
					<label for="genderinfo">Gender Information <span style="font-size: 11px">(optional)</span>:</label>
					<textarea type="text" name="genderinfo"></textarea>
				</div>

				<div>
					<label for="age">Age:<br>
					<span style="font-size: 11px">(required)</span></label></label>
					<input type="number" min="0" max="99" step="1" value="18" id="age" name="age" required>
					<label for="date">Date of Birth:</label>
					<input type="date" id="date" name="date" required>
				</div>

				<div>
					<label for="email">Email:<br>
					<span style="font-size: 11px">(required)</span></label></label>
					<input type="text" name="email" required>
				</div>

				<div>
					<label for="telephone">Telephone:<br>
					<span style="font-size: 11px">(required)</span></label></label>
					<input type="text" name="telephone" required>
				</div>

				<div>
					<label for="address">Address:<br>
					<span style="font-size: 11px">(required)</span></label></label>
					<textarea type="text" name="address" required></textarea>
				</div>

				<div>
					<label for="occupation">Occupation:</label>
					<textarea type="text" name="occupation"></textarea>
				</div>

				<div>
					<label for="workenvironment">Work Environment (e.g. city, farm):</label>
					<textarea type="text" name="workenvironment"></textarea>
				</div>

				<div>
					<label for="newsletter"></label>
					<b>Tick here if you would like to receive our newsletter</b><input type="checkbox" contact="email">
				</div>

		</fieldset>

		<fieldset>
			<legend>HEALTH PROFILE</legend>

				<div>
					<label for="advice">What is your main reason for seeking nutritional advice?</label>
					<textarea type="text" name="advice" required></textarea>
				</div>

				<div>
					<label for="outcome">What outcome are you hoping to achieve?</label>
					<textarea type="text" name="outcome" required></textarea>
				</div>

				<div>
					<p><b>Please list the issues you would like to focus on:</b></p>

					<table>
						<thead>
							<tr>
								<td>Health issue (e.g. arthritis, overweight)</td>
								<td>Management so far (e.g. operation, exercise)</td>
								<td>Onset/duration</td>
							</tr>
						</thead>

						<tbody>
							<tr>
        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>
    						</tr>

    						<tr>
        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:220px" name="freetext"></textarea>
        							</td>
    						</tr>

    					</tbody>
    				</table>
    			</div>

    			<div>
					<label for="tests">Have you had any recent health tests? Please specify.</label>
					<textarea type="text" name="tests"></textarea>
				</div>

				<div>
					<label for="conditions">Have you had any other major surgery <b>(including cosmetic surgery)</b>, biopsies, diagnosed medical conditions, significant periods of ill health.  Or do you suffer from any allergies, chronic or niggling health problems? (please give details e.g. high blood pressure, frequent colds, recurrent urinary infections etc.</label>
					<textarea type="text" name="conditions"></textarea>
				</div>

				<div>
					<label for="past_event">Do you suspect your symptoms relate to a particular event or time in your life?</label>
					<textarea type="text" name="past_event"></textarea>
				</div>
		</fieldset>

		<fieldset>
			<legend>MEDICATION & REMEDIES</legend>

			<p>Please list <b>anything you take regularly</b> including GP prescribed medication, self-prescribed medication (e.g. painkillers) nutritional supplements, herbal or homeopathic remedies etc.</p>

				<div>
					<table>
						<thead>
							<tr>
								<td>Remedy</td>
								<td>Dose</td>
								<td>Condition being treated</td>
								<td>Frequency & Duration</td>
							</tr>
						</thead>

						<tbody>
							<tr>
        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>
    						</tr>

    						<tr>
        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>
    						</tr>


    						<tr>
        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>

        							<td>
            							<textarea type="text" style="width:160px" name="freetext"></textarea>
        							</td>
    						</tr>

    					</tbody>
    				</table>
    			</div>

    			<div>
					<label for="antibiotics">Antibiotic history: please state when and why you last took antibiotics plus any previous times you can remember:</label>
					<textarea type="text" name="antibiotics"></textarea>
				</div>
		</fieldset>

		<fieldset>
			<legend>BODY SCAN</legend>

			<p>Please check <B>ALL</B> conditions that you regularly experience within each body area:</p>

			<div>
				<p>Head:</p>
					<input type="checkbox" name="head" value="headaches"><i>headaches</i>
					<input type="checkbox" name="head" value="migraine">migraine
					<input type="checkbox" name="head" value="stiffneck">stiff neck
					<input type="checkbox" name="head" value="fuzzyheaded">fuzzy headed
					<input type="checkbox" name="head" value="dizziness"><i>dizziness</i>
					<input type="checkbox" name="head" value="balance">poor balance<br>
					<input type="checkbox" name="head" value="pounding">pounding head
					<input type="checkbox" name="head" value="hangover">feeling of hangover
					<input type="checkbox" name="head" value="pain"><i>unexplained pain</i>
			</div>

			<div>
				<p>Hair:</p>
					<input type="checkbox" name="hair" value="oily">oily
					<input type="checkbox" name="hair" value="dry">dry
					<input type="checkbox" name="hair" value="condition">poor condition
					<input type="checkbox" name="hair" value="brittle">brittle
					<input type="checkbox" name="hair" value="thinning">thinning
					<input type="checkbox" name="hair" value="grey">prematurely grey
					<input type="checkbox" name="hair" value="dandruff">dandruff<br>
					<input type="checkbox" name="hair" value="inc_facial">increased facial hair
					<input type="checkbox" name="hair" value="inc_body">increased body hair
					<input type="checkbox" name="hair" value="dec_body">decreased body hair
			</div>

			<div>
				<p>Mouth:</p>
					<input type="checkbox" name="mouth" value="tongue">sore tongue
					<input type="checkbox" name="mouth" value="patches">white/red patches
					<input type="checkbox" name="mouth" value="decay">tooth decay
					<input type="checkbox" name="mouth" value="ulcers">ulcers
					<input type="checkbox" name="mouth" value="breath">bad breath
					<input type="checkbox" name="mouth" value="throat">sore throat<br>
					<input type="checkbox" name="mouth" value="taste">poor sense of taste
					<input type="checkbox" name="mouth" value="saliva">excess saliva
					<input type="checkbox" name="mouth" value="dry_mouth">dry mouth
					<input type="checkbox" name="mouth" value="swallowing"><i>difficulty swallowing</i>
					<input type="checkbox" name="mouth" value="hoarse">hoarse voice<br>
					<input type="checkbox" name="mouth" value="gingivitis">gingivitis
					<input type="checkbox" name="mouth" value="gums">bleeding gums
					<input type="checkbox" name="mouth" value="sores">cold sores
			</div>

			<div>
				<p>Eyes:</p>
					<input type="checkbox" name="eyes" value="burning">burning
					<input type="checkbox" name="eyes" value="gritty">gritty
					<input type="checkbox" name="eyes" value="protruding">protruding
					<input type="checkbox" name="eyes" value="infection">prone to infection
					<input type="checkbox" name="eyes" value="sticky">sticky
					<input type="checkbox" name="eyes" value="itchy">itchy
					<input type="checkbox" name="eyes" value="painful"><i>painful</i><br>
					<input type="checkbox" name="eyes" value="night_vision">poor night vision
					<input type="checkbox" name="eyes" value="dry_eyes">dry
					<input type="checkbox" name="eyes" value="cataracts">cataracts
					<input type="checkbox" name="eyes" value="sensitive">sensitive to light
					<input type="checkbox" name="eyes" value="bags">bags
					<input type="checkbox" name="eyes" value="swollen">swollen eyelids
					<input type="checkbox" name="eyes" value="blurred"><i>blurred vision</i>
					<input type="checkbox" name="eyes" value="double">double vision
					<input type="checkbox" name="eyes" value="failing">failing eyesight
					<input type="checkbox" name="eyes" value="yellow">yellowish
			</div>

			<div>
				<p>Ears:</p>
					<input type="checkbox" name="ears" value="blocked">blocked
					<input type="checkbox" name="ears" value="sore_ears">sore
					<input type="checkbox" name="ears" value="itchy">itchy
					<input type="checkbox" name="ears" value="weeping">weeping
					<input type="checkbox" name="ears" value="watery">watery
					<input type="checkbox" name="ears" value="waxy">overly waxy
					<input type="checkbox" name="ears" value="creased_earlobe">creased earlobe
			</div>

			<div>
				<p>Nose:</p>
					<input type="checkbox" name="nose" value="congested">congested
					<input type="checkbox" name="nose" value="runny">runny
					<input type="checkbox" name="nose" value="bleeds"><i>frequent nose bleeds</i>
					<input type="checkbox" name="nose" value="snoring">prone to snoring
					<input type="checkbox" name="nose" value="sinusitis">sinusitis
					<input type="checkbox" name="nose" value="hay_fever">hay fever<br>
					<input type="checkbox" name="nose" value="drip">post nasal drip
					<input type="checkbox" name="nose" value="rhinitis">rhinitis
					<input type="checkbox" name="nose" value="sneezing">sneezing
					<input type="checkbox" name="nose" value="poor_smell">poor sense of smell
			</div>

			<div>
				<p>Muscles:</p>
					<input type="checkbox" name="muscles" value="tender">tender
					<input type="checkbox" name="muscles" value="sore">sore
					<input type="checkbox" name="muscles" value="cramps">cramps
					<input type="checkbox" name="muscles" value="spasms">spasms
					<input type="checkbox" name="muscles" value="twitches">twitches
					<input type="checkbox" name="muscles" value="tone">loss of tone
					<input type="checkbox" name="muscles" value="wasting">wasting
					<input type="checkbox" name="muscles" value="weak">weak
					<input type="checkbox" name="muscles" value="stiff">stiff<br>
					<input type="checkbox" name="muscles" value="frozen">frozen
					<input type="checkbox" name="muscles" value="restless">restless legs
					<input type="checkbox" name="muscles" value="numb">numbness
			</div>

			<div>
				<p>Skin:</p>
					<input type="checkbox" name="skin" value="dry_skin">dry
					<input type="checkbox" name="skin" value="rough">rough
					<input type="checkbox" name="skin" value="flaky">flaky
					<input type="checkbox" name="skin" value="scaly">scaly
					<input type="checkbox" name="skin" value="puffy">puffy
					<input type="checkbox" name="skin" value="pale">pale
					<input type="checkbox" name="skin" value="patches">brown patches
					<input type="checkbox" name="skin" value="moles_lesions"><i>change in moles or lesions</i><br>
					<input type="checkbox" name="skin" value="lined">pematurely lined
					<input type="checkbox" name="skin" value="congested">congested
					<input type="checkbox" name="skin" value="oily">oily
					<input type="checkbox" name="skin" value="clammy">clammy
					<input type="checkbox" name="skin" value="yellow">yellow
					<input type="checkbox" name="skin" value="slow_heal">slow to heal
			</div>

			<div>
				<p>Skin Prone To:</p>
					<input type="checkbox" name="skinprone" value="acne">acne
					<input type="checkbox" name="skinprone" value="pimples">pimples
					<input type="checkbox" name="skinprone" value="rosacea">rosacea
					<input type="checkbox" name="skinprone" value="eczema">eczema
					<input type="checkbox" name="skinprone" value="dermatitis">dermatitis
					<input type="checkbox" name="skinprone" value="psoriasis">psoriasis
					<input type="checkbox" name="skinprone" value="rashes">rashes
					<input type="checkbox" name="skinprone" value="boils">boils
					<input type="checkbox" name="skinprone" value="hives">hives<br>
					<input type="checkbox" name="skinprone" value="itching">itching
					<input type="checkbox" name="skinprone" value="stretch_marks">stretch marks
					<input type="checkbox" name="skinprone" value="cellulite">cellulite
					<input type="checkbox" name="skinprone" value="bruising">easy bruisimg
					<input type="checkbox" name="skinprone" value="threadveins">thread veins
					<input type="checkbox" name="skinprone" value="varicose">varicose veins<br>
					<input type="checkbox" name="skinprone" value="ringworm">ringworm
					<input type="checkbox" name="skinprone" value="allergic">allergic reactions
					<input type="checkbox" name="skinprone" value="inc_sweat">excessive sweating
			</div>

			<div>
				<p>Joints:</p>
					<input type="checkbox" name="joints" value="painful_joint">painful
					<input type="checkbox" name="joints" value="inflamed">inflamed
					<input type="checkbox" name="joints" value="swollen_joint">swollen
					<input type="checkbox" name="joints" value="stiff_joint">stiff
					<input type="checkbox" name="joints" value="rheumatic">rheumatic
					<input type="checkbox" name="joints" value="arthritic">arthritic
					<input type="checkbox" name="joints" value="aching">aching
					<input type="checkbox" name="joints" value="sore_joint">sore
					<input type="checkbox" name="joints" value="dec_bend">difficulty bending<br>
					<input type="checkbox" name="joints" value="dec_mobile">reduced mobility
					<input type="checkbox" name="joints" value="unsteady">unstadiness
					<input type="checkbox" name="joints" value="slow_move">slow movement
			</div>

			<div>
				<p>Mood <span style="font-size: 13px">(tick all predominant states, even if they conflict)</span>:</p>
					<input type="checkbox" name="mood" value="depressed"><i>depressed</i>
					<input type="checkbox" name="mood" value="anxious">anxious
					<input type="checkbox" name="mood" value="tense">tense
					<input type="checkbox" name="mood" value="angry">angry
					<input type="checkbox" name="mood" value="happy">happy
					<input type="checkbox" name="mood" value="balanced">balanced
					<input type="checkbox" name="mood" value="optimistic">optimistic
					<input type="checkbox" name="mood" value="sad">sad
					<input type="checkbox" name="mood" value="pessimistic">pessimistic<br>
					<input type="checkbox" name="mood" value="tired">tired
					<input type="checkbox" name="mood" value="not_bothered">can't be bothered
					<input type="checkbox" name="mood" value="hyperative">hyperactive
					<input type="checkbox" name="mood" value="cheerful">cheerful
					<input type="checkbox" name="mood" value="agitated">agitated
					<input type="checkbox" name="mood" value="easy_upset">easily upset
					<input type="checkbox" name="mood" value="tearful">tearful
					<input type="checkbox" name="mood" value="jittery">jittery<br>
					<input type="checkbox" name="mood" value="frightened">frightened
					<input type="checkbox" name="mood" value="explosive">explosive
					<input type="checkbox" name="mood" value="pent_up">pent up
					<input type="checkbox" name="mood" value="worried">worried
					<input type="checkbox" name="mood" value="irritated">irritated
					<input type="checkbox" name="mood" value="annoyed">annoyed
					<input type="checkbox" name="mood" value="overwhelmed">overwhelmed
					<input type="checkbox" name="mood" value="suicidal"><i>suicidal</i><br>
					<input type="checkbox" name="mood" value="fluctuating">fluctuating
					<input type="checkbox" name="mood" value="aggressive">aggressive
			</div>

			<div>
				<p>Mind:</p>
					<input type="checkbox" name="mind" value="forgetful">forgetful
					<input type="checkbox" name="mind" value="dec_learn">difficulty learning new things
					<input type="checkbox" name="mind" value="confused">easily confused
					<input type="checkbox" name="mind" value="no_switch_off">can't switch off<br>
					<input type="checkbox" name="mind" value="dec_concentrate">difficulty concentrating
					<input type="checkbox" name="mind" value="frustrated">easily frustrated
					<input type="checkbox" name="mind" value="distracted">easily distracted
					<input type="checkbox" name="mind" value="dec_decisions">difficulty making decisions<br>
					<input type="checkbox" name="mind" value="no_interest">loss of interest in daily life
					<input type="checkbox" name="mind" value="fogginess">fogginess
					<input type="checkbox" name="mind" value="dyslexia">dyslexia
					<input type="checkbox" name="mind" value="dyspraxia">dyspraxia
					<input type="checkbox" name="mind" value="insomnia">insomnia
					<input type="checkbox" name="mind" value="hyper_mind">hyperactive<br>
					<input type="checkbox" name="mind" value="panic">panic attacks
					<input type="checkbox" name="mind" value="dec_motivation">no motivation
			</div>

			<div>
				<p>Chest:</p>
					<input type="checkbox" name="chest" value="colds_infections">frequent colds and chest infections
					<input type="checkbox" name="chest" value="asthma">asthma
					<input type="checkbox" name="chest" value="bronchitis">bronchitis
					<input type="checkbox" name="chest" value="palpitations">palpitations
					<input type="checkbox" name="chest" value="heart_condition">heart condition<br>
					<input type="checkbox" name="chest" value="chest_pain"><i>chest discomfort/pain</i>
					<input type="checkbox" name="chest" value="short_breath"><i>shortness of breath</i>
					<input type="checkbox" name="chest" value="dec_breath">difficulty breathing
					<input type="checkbox" name="chest" value="wheezing">wheezing<br>
					<input type="checkbox" name="chest" value="inc_cough"><i>persistent cough</i>
					<input type="checkbox" name="chest" value="noisy_breath">noisy breathing
					<input type="checkbox" name="chest" value="breast_pain">breast pain				
			</div>

			<div>
				<p>Gut:</p>
					<input type="checkbox" name="gut" value="bloated">bloated
					<input type="checkbox" name="gut" value="painful_gut"><i>painful</i>
					<input type="checkbox" name="gut" value="tender">tender
					<input type="checkbox" name="gut" value="cramping">cramping
					<input type="checkbox" name="gut" value="distended">distended
					<input type="checkbox" name="gut" value="nausea">nausea
					<input type="checkbox" name="gut" value="hernia">hiatus hernia<br>
					<input type="checkbox" name="gut" value="fullness">sensation of fullness
					<input type="checkbox" name="gut" value="reflux">acid reflux
					<input type="checkbox" name="gut" value="heartburn">heartburn
					<input type="checkbox" name="gut" value="flatulence">flatulence
					<input type="checkbox" name="gut" value="belching">belching
					<input type="checkbox" name="gut" value="churning">churning
					<input type="checkbox" name="gut" value="vomiting">vomiting<br>
					<input type="checkbox" name="gut" value="ibs">irritable bowel
					<input type="checkbox" name="gut" value="coeliac">coeliac
					<input type="checkbox" name="gut" value="diverticula">diverticula
					<input type="checkbox" name="gut" value="polyps">polyps
					<input type="checkbox" name="gut" value="haemmorrhoids">haemmorrhoids
					<input type="checkbox" name="gut" value="ulcers">ulcers
					<input type="checkbox" name="gut" value="sluggish">sluggish<br>
					<input type="checkbox" name="gut" value="sensitive">sensitive
					<input type="checkbox" name="gut" value="constipation"><i>constipation</i>
					<input type="checkbox" name="gut" value="diarrhoea"><i>diarrhoea</i>
			</div>

			<div>
				<p>Genitals:</p>
					<input type="checkbox" name="genitals" value="itch">itchy
					<input type="checkbox" name="genitals" value="cystitis">cystitis
					<input type="checkbox" name="genitals" value="thrush">thrush
					<input type="checkbox" name="genitals" value="ulcer">ulcers
					<input type="checkbox" name="genitals" value="warts">warts
					<input type="checkbox" name="genitals" value="herpes">herpes
					<input type="checkbox" name="genitals" value="groin_pain">groin pain
					<input type="checkbox" name="genitals" value="prostatitis">prostatitis<br>
					<input type="checkbox" name="genitals" value="pid">pelvic inflammatory disease
					<input type="checkbox" name="genitals" value="impotence">impotence
					<input type="checkbox" name="genitals" value="pain_sex">painful intercourse
					<input type="checkbox" name="genitals" value="dry_vagina">vaginal dryness<br>
					<input type="checkbox" name="genitals" value="inc_pain_urine"><i>painful or frequent urination</i>
					<input type="checkbox" name="genitals" value="discharge">unexplained discharge				
			</div>

			<div>
				<p>Hands:</p>
					<input type="checkbox" name="hands" value="dry_hands">dry
					<input type="checkbox" name="hands" value="cracked">cracked
					<input type="checkbox" name="hands" value="eczema_hands">eczema
					<input type="checkbox" name="hands" value="sore_joint2">sore joints
					<input type="checkbox" name="hands" value="puffy">puffy
					<input type="checkbox" name="hands" value="cold_hands">cold
					<input type="checkbox" name="hands" value="chilblains">chilblains
					<input type="checkbox" name="hands" value="numb_hands"><i>numbness</i>
					<input type="checkbox" name="hands" value="tingling">tingling<br>
					<input type="checkbox" name="hands" value="clumsy">feeling clumsy and uncoordinated
					<input type="checkbox" name="hands" value="dec_circulation">poor circulation	
			</div>

			<div>
				<p>Nails:</p>
					<input type="checkbox" name="nails" value="fragile">fragile
					<input type="checkbox" name="nails" value="dry_nails">dry
					<input type="checkbox" name="nails" value="brittle_nails">brittle
					<input type="checkbox" name="nails" value="flaky_nails">flaky
					<input type="checkbox" name="nails" value="peeling">peeling
					<input type="checkbox" name="nails" value="split">split
					<input type="checkbox" name="nails" value="fungal">fungal
					<input type="checkbox" name="nails" value="hangnails">hangnails
					<input type="checkbox" name="nails" value="infected">infected
					<input type="checkbox" name="nails" value="clubbed"><i>clubbed</i><br>
					<input type="checkbox" name="nails" value="cuticles">split cuticles
					<input type="checkbox" name="nails" value="ridged">ridged
					<input type="checkbox" name="nails" value="spoon">spoon shaped
					<input type="checkbox" name="nails" value="spots">white spots on more than 2
					<input type="checkbox" name="nails" value="white_lines">horizontal white lines<br>
					<input type="checkbox" name="nails" value="thick">thickened or 'horny'
					<input type="checkbox" name="nails" value="dark">dark nails
					<input type="checkbox" name="nails" value="pale_bed">pale nail bed			
			</div>

			<div>
				<p>Legs & Feet:</p>
					<input type="checkbox" name="legsfeet" value="restless_legs">restless legs
					<input type="checkbox" name="legsfeet" value="swollen_legs">swollen
					<input type="checkbox" name="legsfeet" value="aching_legs">aching
					<input type="checkbox" name="legsfeet" value="athlete">athlete's foot
					<input type="checkbox" name="legsfeet" value="burning_feet">burning feet
					<input type="checkbox" name="legsfeet" value="tender_heels">tender heels
					<input type="checkbox" name="legsfeet" value="gout">gout<br>
					<input type="checkbox" name="legsfeet" value="sciatica">sciatica
					<input type="checkbox" name="legsfeet" value="cold_feet">cod feet
					<input type="checkbox" name="legsfeet" value="tingling_legsfeet">tingling
					<input type="checkbox" name="legsfeet" value="numb_legsfeet"><i>numb</i>	
					<input type="checkbox" name="legsfeet" value="prickling_legsfeet">prickling	
			</div>

			<div>
				<p><b>IMPORTANT SYMPTOMS</b><br>
				<span style="font-size: 13px"><b>Please indicate by underlining if you suffer from any of the following symptoms which may require additional medical care</b></span>:</p>
					<input type="checkbox" name="important_symptoms" value="persistent_pain">persistent or unexplained pain
					<input type="checkbox" name="important_symptoms" value="unexplaned_bleeding">unexplained bleeding or discharge from the nipple, vagina or rectum
					<input type="checkbox" name="important_symptoms" value="blood">blood in sputum, vomit, urine or stools
					<input type="checkbox" name="important_symptoms" value="breast_lumps">breast lumps
					<input type="checkbox" name="important_symptoms" value="calf_swell">calf swelling<br>
					<input type="checkbox" name="important_symptoms" value="difficulty_swallowing">difficulty swallowing
					<input type="checkbox" name="important_symptoms" value="inc_thirst">excessive thirst
					<input type="checkbox" name="important_symptoms" value="inc_urination">increased urination
					<input type="checkbox" name="important_symptoms" value="weight_plateau">inability to gain or lose weight<br>
					<input type="checkbox" name="important_symptoms" value="loss_appetite">loss of appetite
					<input type="checkbox" name="important_symptoms" value="paralysis">paralysis
					<input type="checkbox" name="important_symptoms" value="slurring">slurred speech
					<input type="checkbox" name="important_symptoms" value="unexplained_bruising">unexplained bruising
					<input type="checkbox" name="important_symptoms" value="rash_weight_loss">unexplained rash or weight loss
					<input type="checkbox" name="important_symptoms" value="black_stool">black, tarry stools
					<input type="checkbox" name="important_symptoms" value="painless_ulcer">painless ulcers or fissures
					<input type="checkbox" name="important_symptoms" value="bleeding_pregancy">bleeding in pregnancy

		</fieldset>

		<fieldset>
			<legend>YOUR VITAL STATISTICS</legend>

			<div>
				<label for="bp">What is your normal blood pressure?</label>
				<textarea type="text" name="bp"></textarea>
			</div>

			<div>
				<label for="pulse">What is your resting pulse rate?</label>
				<textarea type="text" name="pulse"></textarea>
			</div>

			<div>
				<label for="weight">What is your current weight?</label>
				<textarea type="text" name="weight"></textarea>
			</div>

			<div>
				<label for="height">What is your height?</label>
				<textarea type="text" name="height"></textarea>
			</div>

			<div>
				<label for="waist">What is your waist circumference?</label>
				<textarea type="text" name="waist"></textarea>
			</div>

			<div>
				<label for="hip">What is your hip circumference?</label>
				<textarea type="text" name="hip"></textarea>
			</div>

			<div>
				<label for="blood_type">What is your blood type?</label>
				<textarea type="text" name="blood_type"></textarea>
			</div>

			<div>
				<label for="weight_stability">Is your weight stable, increasing or decreasing?</label>
				<textarea type="text" name="weight_stability"></textarea>
			</div>

			<div>
				<label for="vaccines">Did you have the recommended immunisations (vaccines) as a child?</label>
				<textarea type="text" name="vaccines"></textarea>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR FAMILY HISTORY</legend>

			<p>Do you have a family history of disease or allergies?  (e.g. heart disease, diabetes, asthma, etc.)  State disease, age at onset and gender:

			<div>
				<label for="grandparents">Grandparents:</label>
				<textarea type="text" name="grandparents"></textarea>
			</div>

			<div>
				<label for="parents">Parents:</label>
				<textarea type="text" name="parents"></textarea>
			</div>

			<div>
				<label for="siblings">Siblings:</label>
				<textarea type="text" name="siblings"></textarea>
			</div>

			<div>
				<label for="children">Children:</label>
				<textarea type="text" name="children"></textarea>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR DAILY LIFE</legend>

			<div>
				<label for="enjoy_life">Do you enjoy your daily life?</label>
					<select names="enjoy_life">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="mostly">Mostly</option>
					<option value="sometimes">Sometimes</option>
					<option value="rarely">Rarely</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="dependents">How many people depend on your support?</label>
					<select names="dependents">
					<option value="select">Please select</option>
					<option value="0">0</option>
					<option value="1">1</option>
					<option value="2">2</option>
					<option value="3">3</option>
					<option value="4">4</option>
					<option value="5">5</option>
					<option value=">more">More than 5</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="support">Do you feel supported by people around you?</label>
					<select names="support">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="recent_situ">Are you recently separated/divorced/a new parent?</label>
					<select names="recent_situ">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="grief">Are you recently bereaved?</label>
					<select names="grief">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="house_job">Have you moved house or changed jobs recently?</label>
					<select names="house_job">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="hours">Do you work long or irregular hours?</label>
					<select names="hours">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="workload">Is your workload bigger than you can manage?</label>
					<select names="workload">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="stress">Are you under significant stress in any other way?</label>
					<select names="stress">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="relaxing">Do you feel guilty when you are relaxing?</label>
					<select names="relaxing">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="drive">Do you have a strong drive for achievement?</label>
					<select names="drive">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="multitask">Do you often do 2 or 3 tasks simultaneously?</label>
					<select names="multitask">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="reg_exercise">Do you take regular exercise?</label>
					<select names="reg_exercise">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="active_job">Is your job active?</label>
					<select names="active_job">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="active_hobbies">Do you have any active hobbies?</label>
					<select names="active_hobbies">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="sleep">Do you sleep well?</label>
					<select names="sleep">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="relax">Do you take time for relaxation?</label>
					<select names="relax">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR DIGESTION</legend>

			<p>Do you regularly experience...</p>

			<div>
				<label for="indigestion">Indigestion after food or between meals?</label>
					<select names="indigestion">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="fatty">Indigestion after fatty food?</label>
					<select names="fatty">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="bowel_move">Bowel movement shortly after eating?</label>
					<select names="bowel_move">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="stomach_upset">Frequent stomach upsets or stomach pain?</label>
					<select names="stomach_upset">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="nausea_vomit">Nausea or vomiting?</label>
					<select names="nausea_vomit">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="pain_shoulder_rib">Pain between the shoulders or under the ribs?</label>
					<select names="pain_shoulder_rib">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="constipation2">Constipation or hard-to-pass stools?</label>
					<select names="constipation2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="diarrhoea2">Diarrhoea or urgency to go?</label>
					<select names="diarrhoea2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="blood_mucus">Blood or mucus in stools?</label>
					<select names="blood_mucus">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="undigested">Undigested food in stools?</label>
					<select names="undigested">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="inconsistent">Generally inconsistent bowel movements?</label>
					<select names="inconsistent">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="anal_itch">Anal itching?</label>
					<select names="anal_itch">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="thrush_cystitis">Thrush or cystitis</label>
					<select names="thrush_cystitis">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<p>Description of bowel habits:</p>

			<div>
				<label for="frequency_bm">How often do you have a bowel movement?</label>
					<select names="frequency_bm">
					<option value="select">Please select</option>
					<option value="yes">Less than once per week</option>
					<option value="1_3">1-3 x per week</option>
					<option value="4_6">4-6 x per week</option>
					<option value="1pd">Once per day</option>
					<option value="2pd">Twice per day</option>
					<option value="3pd">3 x per day</option>
					<option value="3+pd">More than 3 x per day</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="change_bm">Have you noticed any recent change in bowel habit?  Please describe:</label>
				<textarea type="text" name="change_bm"></textarea>
			</div>

			<div>
				<label for="stool_colour">Describe your stool colour:</label>
					<select names="stool_colour">
					<option value="select">Please select</option>
					<option value="pale2">Pale</option>
					<option value="midbrown">Mid brown</option>
					<option value="darkbrown">Dark Brown</option>
					<option value="black">Black</option>
					<option value="grey">Grey</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="foreign_travel">Have you ever had a stomach upset after foreign travel?  Please describe:</label>
				<textarea type="text" name="foreign_travel"></textarea>
			</div>

			<div>
				<label for="intolerence">Do any foods cause digestive problems?  Please describe:</label>
				<textarea type="text" name="intolerence"></textarea>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR TOXIC EXPOSURE</legend>

			<div>
				<label for="pollution">Do you live, exercise or work in a city or by a busy road?</label>
					<select names="pollution">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="pollution2">Do you spend a lot of time on busy roads?</label>
					<select names="pollution2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="pesticides">Do you live close to an agricultural area?</label>
					<select names="pesticides">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="water">Do you drink unfiltered water?</label>
					<select names="water">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="alcohol">How many *units of alcohol do you drink in a week?</label>
					<select names="alcohol">
					<option value="select">Please select</option>
					<option value="0">0</option>
					<option value="less1">Less than 1</option>
					<option value="1_2">1-2</option>
					<option value="2_4">2-4</option>
					<option value="4_6">4-6</option>
					<option value="6_8">6-8</option>
					<option value="8_10">8-10</option>
					<option value="10more">More than 10</option>
					<option value="no_answer">Don't know</option>
					</select>

					<p><span style="font-size: 13px"><b>*One alcohol unit is measured as 10ml or 8g of pure alcohol. This equals one 25ml single measure of whisky (ABV 40%), or a third of a pint of beer (ABV 5-6%) or half a standard (175ml) glass of red wine (ABV 12%).</b></span></p>
			</div>

			<div>
				<label for="beverage">What is your usual alcoholic drink?</label>
				<textarea type="text" name="beverage"></textarea>
			</div>

			<div>
				<label for="smoking">How much do you smoke?</label>
					<select names="smoking">
					<option value="select">Please select</option>
					<option value="never">Never smoked</option>
					<option value="gaveup5">Gave up over 5 years ago</option>
					<option value="gaveup2">Gave up over 2 years ago</option>
					<option value="gaveuprecent">Gave up within the last 2 years</option>
					<option value="less1pd">Less than 1 per day</option>
					<option value="1_5">1-5 per day</option>
					<option value="5_10">5-10 per day</option>
					<option value="10_20">10-20 per day</option>
					<option value="20more">More than 20 per day</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="smoky">Do you live in a smoky atmosphere?</label>
					<select names="smoky">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="water">Do you drink unfiltered water?</label>
					<select names="water">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="addiction">Do you think you may be addicted to anything?  Please describe:</label>
				<textarea type="text" name="addiction"></textarea>
			</div>

			<div>
				<label for="screens">Do you spend a lot of time in front of a TV or computer monitor?</label>
					<select names="screens">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="mobile">Do you spend a lot of time using your mobile phone for communication, social media or other apps?</label>
					<select names="mobile">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="sun">Do you sunbathe a lot?</label>
					<select names="sun">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="flying">Are you a frequent flyer? <span style="font-size: 13px">(6+ return flights per year)</span></label>
					<select names="flying">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="chemicals">Are you exposed to *chemicals through work or hobby?</label>
					<select names="chemicals">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>

					<p><span style="font-size: 13px">*e.g. developing photographic prints; hairdresser; nail technician, carpet or upholstery manufacturing etc.</span></p>
			</div>

			<div>
				<label for="plastic">Do you heat freeze or wrap food in plastics?</label>
					<select names="plastic">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="foil">Do you cook or wrap food in aluminium foil?</label>
					<select names="foil">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="antacid">Do you regularly take antacid (indigestion) medication?</label>
					<select names="antacid">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="organic">Roughly what % of your food is organic?</label>
					<select names="organic">
					<option value="select">Please select</option>
					<option value="none">None</option>
					<option value="1_10">1-10%</option>
					<option value="10_20">10-20%</option>
					<option value="20_50">20-50%</option>
					<option value="50_75">50-75%</option>
					<option value="75_100">75-100%</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="high_heat">Do you frequently fry or roast food at high temperatures?</label>
					<select names="high_heat">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="browned">Do you regularly eat browned or barbequed food?</label>
					<select names="browned">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="oily_fish">Do you eat oily fish or shellfish more than 3 x per week?</label>
					<select names="oily_fish">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="sweeteners">Do you regularly consume artificial sweeteners?</label>
					<select names="sweeteners">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="floss">Do you floss your teeth regularly? <span style="font-size: 13px">(tape or water pik)</span></label>
					<select names="floss">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="fillings">Are your teeth filled with mercury amalgams? <span style="font-size: 13px">(silver-coloured fillings)</span></label>
					<select names="fillings">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR ENERGY LEVELS</legend>

			<div>
				<label for="sleep_length">Do you need more than 8 hours sleep per night?</label>
					<select names="sleep_length">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="low_energy">Is your energy less than you want it to be?</label>
					<select names="low_energy">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="morning_energy">Do you find it difficult to get going in the morning?</label>
					<select names="morning_energy">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="drowsy">Do you feel drowsy during the day?</label>
					<select names="drowsy">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="time_energy_low">What time(s) of day is your energy lowest?</label>
				<textarea type="text" name="time_energy_low"></textarea>
			</div>

			<div>
				<label for="irritable2">Do you get dizzy or irritable if you don't eat often?</label>
					<select names="irritable2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="stimulant">Do you use caffeine, sugar or nicotine to keep going?</label>
					<select names="stimulant">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="concentration">Do you find it difficult to concentrate?</label>
					<select names="concentration">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="lightheaded">Do you feel dizzy or light-headed if you stand up quickly?</label>
					<select names="lightheaded">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="fatigue">Do you suffer from unexplained fatigue or listlessness?</label>
					<select names="fatigue">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>SELECT ONLY THOSE THAT APPLY TO YOU</legend>

			<div>
				<label for="pregnant">Are you pregnant?</label>
					<select names="pregnant">
					<option value="select">Please select</option>
					<option value="no">No</option>
					<option value="yes1">Yes - 1st trimester</option>
					<option value="yes2">Yes - 2nd trimester</option>
					<option value="yes3">Yes - 3rd trimester</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="pregnant2">Are you trying to become pregnant?</label>
					<select names="pregnant2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="breast_feeding">Are you breast-feeding at present?</label>
					<select names="breast_feeding">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="children2">How many children have you given birth to?</label>
					<select names="children2">
					<option value="select">Please select</option>
					<option value="0">0</option>
					<option value="1">1</option>
					<option value="2">2</option>
					<option value="3">3</option>
					<option value="4">4</option>
					<option value="5">5</option>
					<option value="6">6</option>
					<option value="6+">More than 6</option>
					</select>
			</div>

			<div>
				<label for="fertility">Have you had problems with fertility?</label>
					<select names="fertility">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="miscarriage">Have you ever had a miscarriage?</label>
					<select names="miscarriage">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="contraception">What contraception do you use</label>
					<select names="contraception">
					<option value="select">Please select</option>
					<option value="none">None</option>
					<option value="condom">Condom</option>
					<option value="femidom">Femidom</option>
					<option value="diaphragm">Diaphragm</option>
					<option value="cap">Cervical cap</option>
					<option value="pill">Pill</option>
					<option value="implant">Implant</option>
					<option value="iud">Intrauterine device</option>
					<option value="sponge">Sponge</option>
					<option value="injection">Injection</option>
					<option value="app">'Natural Cycles' or other App</option>
					<option value="rhythm">Rhythm Method</option>
					<option value="sterile">Sterilisation</option>
					<option value="vasectomy">Vasectomy</option>
					<option value="other">Other</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="menses">Are you still menstruating?</label>
					<select names="menses">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="hrt">Are you or have you been on Hormone Replacement Therapy?</label>
					<select names="hrt">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="reg_menses">Are your periods regular?</label>
					<select names="reg_menses">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="na">Not applicable</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="spotting">Any bleeding or spotting between periods?</label>
					<select names="spotting">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="na">Not applicable</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="heavy">Are your periods particularly heavy or painful?</label>
					<select names="heavy">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="na">Not applicable</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="pcos">Do you suffer from PCOS, fibroids or endometriosis?</label>
					<select names="pcos">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="std">Any known genito-urinary conditions?</label>
					<select names="std">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="loss_drive">Loss of sex drive?</label>
					<select names="loss_drive">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<p><b>If you are still menstruating:</b> please tick all that apply:</p>
					<input type="checkbox" name="menstruating" value="bloating">pre-menstrual bloating
					<input type="checkbox" name="menstruating" value="tired2">tiredness
					<input type="checkbox" name="menstruating" value="irritable3">irritability
					<input type="checkbox" name="menstruating" value="depression">depression
					<input type="checkbox" name="menstruating" value="breast_tender">breast tenderness<br>
					<input type="checkbox" name="menstruating" value="oedema">water retention
					<input type="checkbox" name="menstruating" value="headaches">headaches
					<input type="checkbox" name="menstruating" value="other2">other
			</div>

			<div>
				<p><b>If you are menopausal:</b> please tick all that apply:</p>
					<input type="checkbox" name="menopausal" value="flush">hot flushes
					<input type="checkbox" name="menopausal" value="insomnia2">insomnia
					<input type="checkbox" name="menopausal" value="osteoporosis">osteoporosis
					<input type="checkbox" name="menopausal" value="mood2">mood swings
					<input type="checkbox" name="menopausal" value="depression2">depression
					<input type="checkbox" name="menopausal" value="dry_vagina2">vaginal dryness
					<input type="checkbox" name="menopausal" value="other3">other
			</div>

			<div>
				<label for="depression3">Do you experience mood swings or depression?</label>
					<select names="depression3">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="dec_motivation2">Loss of motivation and drive?</label>
					<select names="dec_motivation2">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="erection">Problems achieving or maintaining an erection?</label>
					<select names="erection">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="urine_difficult">Frequent or difficult urination?</label>
					<select names="urine_difficult">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="prostate">Prostate problems?</label>
					<select names="prostate">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="night_urination">Waking up at night to urinate?</label>
					<select names="night_urination">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="urine_stream">Difficulty starting or stopping urine stream?</label>
					<select names="urine_stream">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="urine_pain">Pain or burning when urinating?</label>
					<select names="urine_pain">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR EATING HABITS</legend>

			<div>
				<label for="favourite">Which are you favourite foods?</label>
				<textarea type="text" name="favourite"></textarea>
			</div>

			<div>
				<label for="dislike">Which foods do you dislike?</label>
				<textarea type="text" name="dislike"></textarea>
			</div>

			<div>
				<label for="crave">Which foods do you crave?</label>
				<textarea type="text" name="crave"></textarea>
			</div>

			<div>
				<label for="give_up">Which foods would you find hard to give up?</label>
				<textarea type="text" name="give_up"></textarea>
			</div>

			<div>
				<label for="special_diet">Do you cater for a special diet in the household? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="special_diet"></textarea>
			</div>

			<div>
				<label for="culture">Do you avoid any food for cultural/ethical reasons? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="culture"></textarea>
			</div>

			<div>
				<label for="who_cooks">Who does the cooking in your household?</label>
					<select names="who_cooks">
					<option value="select">Please select</option>
					<option value="me">Me</option>
					<option value="other">Someone else</option>
					<option value="varies">Varies</option>
					</select>
			</div>

			<div>
				<label for="allergy">Are you allergic to any foods? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="allergy"></textarea>
			</div>

			<div>
				<label for="intolerence2">Do you suspect any foods don't agree with you? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="intolerence2"></textarea>
			</div>

			<div>
				<label for="diet_change">Have you recently changed your diet? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="diet_change"></textarea>
			</div>

			<div>
				<label for="stress_eat">Do you eat on the move/when stressed?</label>
					<select names="stress_eat">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="binge">Do you ever have eating binges?</label>
					<select names="binge">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="what_binge">What do you binge on?</label>
				<textarea type="text" name="what_binge"></textarea>
			</div>

			<div>
				<label for="eating_disorder">Have you ever suffered from an eating disorder? <span style="font-size: 13px">(please describe)</span>:</label>
				<textarea type="text" name="eating_disorder"></textarea>
			</div>

			<div>
				<label for="chew">Do you chew your food thoroughly?</label>
					<select names="chew">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="thirsty">Are you excessively thirsty?</label>
					<select names="thirsty">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>YOUR AVERAGE DAILY ROUTINE</legend>

			<div>
				<label for="wake">What time do you usually wake up?</label>
				<textarea type="text" name="wake"></textarea>
			</div>

			<div>
				<label for="getup">What time do you usually get out of bed?</label>
				<textarea type="text" name="getup"></textarea>
			</div>

			<div>
				<label for="work_start">Work day start time:</label>
				<textarea type="text" name="work_start"></textarea>
			</div>

			<div>
				<label for="breaks">Work day breaks:</label>
				<textarea type="text" name="breaks"></textarea>
			</div>

			<div>
				<label for="work_end">Work day end time:</label>
				<textarea type="text" name="work_end"></textarea>
			</div>

			<div>
				<label for="commute">Time spent travelling:</label>
				<textarea type="text" name="commute"></textarea>
			</div>

			<div>
				<label for="exercise2">Time spent exercising:</label>
				<textarea type="text" name="exercise2"></textarea>
			</div>

			<div>
				<label for="exercise_time">Exercise time of day:</label>
				<textarea type="text" name="exercise_time"></textarea>
			</div>

			<div>
				<label for="relax_time">Time spent relaxing:</label>
				<textarea type="text" name="relax_time"></textarea>
			</div>

			<div>
				<label for="relax_type">Type of relaxation:</label>
				<textarea type="text" name="relax_type"></textarea>
			</div>

			<div>
				<label for="other_leisure">Other leisure activity:</label>
				<textarea type="text" name="other_leisure"></textarea>
			</div>

			<div>
				<label for="other_routine">Other routine:</label>
				<textarea type="text" name="other_routine"></textarea>
			</div>

			<div>
				<label for="outdoors">Time spent outdoors:</label>
				<textarea type="text" name="outdoors"></textarea>
			</div>

			<div>
				<label for="mood3">Overall mood:</label>
				<textarea type="text" name="mood3"></textarea>
			</div>

			<div>
				<label for="bedtime">Go to bed time:</label>
				<textarea type="text" name="bedtime"></textarea>
			</div>

			<div>
				<label for="asleep">Fall asleep time:</label>
				<textarea type="text" name="asleep"></textarea>
			</div>

			<div>
				<label for="sleep_maintenance">Do you usually have uninterrupted sleep?</label>
					<select names="sleep_maintenance">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

		</fieldset>

		<fieldset>
			<legend>WHAT DID YOU EAT YESTERDAY?</legend>

			<p>You can fill in today's meals instead if you can't adequately recall yesterday's meals.</p>

			<div>
				<label for="breakfast">Breakfast:</label>
				<textarea type="text" name="breakfast"></textarea>
			</div>

			<div>
				<label for="lunch">Lunch:</label>
				<textarea type="text" name="lunch"></textarea>
			</div>

			<div>
				<label for="dinner">Dinner:</label>
				<textarea type="text" name="dinner"></textarea>
			</div>

			<div>
				<label for="snacks">Snacks:</label>
				<textarea type="text" name="snacks"></textarea>
			</div>

			<div>
				<label for="beverages">All beverages:</label>
				<textarea type="text" name="beverages"></textarea>
			</div>
			
		</fieldset>

		<fieldset>
			<legend>YOUR HEALTH CARERS</legend>

			<div>
				<label for="1stnt">Is this your first visit to a Nutritional Therapist?</label>
					<select names="1stnt">
					<option value="select">Please select</option>
					<option value="yes">Yes</option>
					<option value="no">No</option>
					<option value="no_answer">Don't know</option>
					</select>
			</div>

			<div>
				<label for="locate">How did you find out about me?</label>
					<select names="locate">
					<option value="select">Please select</option>
					<option value="family_friend">Family/friend</option>
					<option value="bant">BANT website</option>
					<option value="nutriresource">Nutritionist Resource website</option>
					<option value="find_therapy">Find A Therapy website</option>
					<option value="internet">Internet search</option>
					<option value="magazine">CAM or other magazine</option>
					<option value="other4">Other</option>
					</select>
			</div>

			<div>
				<label for="gp">Please provide details of your GP <span style="font-size: 13px">(name and address)</span>:</label>
				<textarea type="text" name="gp"></textarea>
			</div>

			<div>
				<label for="therapists">Are there any other therapists/clinics involved in your care? <span style="font-size: 13px">(please list)</span>:</label>
				<textarea type="text" name="therapists"></textarea>
			</div>

		</fieldset>

		<fieldset>
			<legend>DECLARATION AND CONSENT</legend>

			<div>
				<input type="checkbox" name="declare" value="consent" required><i>By ticking this box you declare that you have disclosed all the relevant information applicable to this consultation and your health status at this point in time.  You consent for the information provided to be used by LDN Nutrition and your therapist to liaise with appropriate health professionals.<br>
					<span style="font-size: 11px">(required)</span></label></i>
			</div>

			<div>
				<label for="date">Date of Completion:<br>
					<span style="font-size: 11px">(required)</span></label></label>
				<input type="date" id="date" name="date" required>
			</div>

		</fieldset>

<input type="submit" value="SUBMIT">

</form>

</div>


</body>
</html>
