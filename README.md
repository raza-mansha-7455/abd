# abd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carvedilol - Complete Drug Information</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --success-color: #27ae60;
            --warning-color: #f39c12;
            --danger-color: #e74c3c;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f5f7fa;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 30px 0;
            text-align: center;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            margin-bottom: 30px;
        }
        
        h1 {
            margin: 0;
            font-size: 2.8rem;
            font-weight: 700;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
        }
        
        .pronunciation {
            font-style: italic;
            font-size: 1.3rem;
            margin-top: 10px;
            opacity: 0.9;
        }
        
        .card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 3px 12px rgba(0, 0, 0, 0.08);
            padding: 30px;
            margin-bottom: 40px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.12);
        }
        
        h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--light-color);
            padding-bottom: 12px;
            margin-top: 0;
            font-size: 1.8rem;
        }
        
        h3 {
            color: var(--secondary-color);
            font-size: 1.4rem;
            margin-top: 25px;
        }
        
        h4 {
            color: var(--primary-color);
            font-size: 1.2rem;
            margin-top: 20px;
        }
        
        .chemistry-box {
            background-color: #f8f9fa;
            border-left: 5px solid var(--secondary-color);
            padding: 20px;
            margin: 25px 0;
            font-family: 'Courier New', monospace;
            border-radius: 0 5px 5px 0;
        }
        
        .warning {
            background-color: rgba(255, 243, 205, 0.5);
            border-left: 5px solid var(--warning-color);
            padding: 20px;
            margin: 25px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .danger {
            background-color: rgba(231, 76, 60, 0.1);
            border-left: 5px solid var(--danger-color);
            padding: 20px;
            margin: 25px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .success {
            background-color: rgba(39, 174, 96, 0.1);
            border-left: 5px solid var(--success-color);
            padding: 20px;
            margin: 25px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .side-effects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        
        .effect-card {
            background-color: #f8f9fa;
            padding: 18px;
            border-radius: 8px;
            border-left: 4px solid var(--secondary-color);
            transition: transform 0.2s ease;
        }
        
        .effect-card:hover {
            transform: scale(1.02);
        }
        
        .common-effect {
            border-left-color: var(--warning-color);
        }
        
        .serious-effect {
            border-left-color: var(--danger-color);
        }
        
        .brands-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 25px;
        }
        
        .brand-card {
            background-color: white;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            padding: 18px;
            width: 160px;
            text-align: center;
            box-shadow: 0 3px 8px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
        }
        
        .brand-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 12px rgba(0,0,0,0.12);
        }
        
        .brand-name {
            font-weight: bold;
            color: var(--primary-color);
            font-size: 1.1rem;
            margin-bottom: 5px;
        }
        
        .brand-dose {
            color: var(--accent-color);
            font-size: 0.95rem;
            font-weight: 600;
        }
        
        .dosage-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        .dosage-table th, .dosage-table td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }
        
        .dosage-table th {
            background-color: var(--primary-color);
            color: white;
        }
        
        .dosage-table tr:nth-child(even) {
            background-color: #f8f9fa;
        }
        
        .dosage-table tr:hover {
            background-color: #f1f5f9;
        }
        
        .interaction-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        .interaction-table th, .interaction-table td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }
        
        .interaction-table th {
            background-color: var(--secondary-color);
            color: white;
        }
        
        .interaction-table tr:nth-child(even) {
            background-color: #f0f7fc;
        }
        
        .interaction-table tr:hover {
            background-color: #e1f0fa;
        }
        
        footer {
            text-align: center;
            padding: 30px;
            background-color: var(--dark-color);
            color: white;
            margin-top: 50px;
            border-radius: 10px 10px 0 0;
        }
        
        .back-to-top {
            display: inline-block;
            background-color: var(--secondary-color);
            color: white;
            padding: 10px 20px;
            border-radius: 30px;
            text-decoration: none;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }
        
        .back-to-top:hover {
            background-color: #2980b9;
        }
        
        @media (max-width: 768px) {
            .side-effects {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .brands-container {
                justify-content: center;
            }
            
            .brand-card {
                width: 140px;
            }
        }
        
        /* Print styles */
        @media print {
            body {
                background-color: white;
                font-size: 12pt;
            }
            
            .card {
                box-shadow: none;
                border: 1px solid #ddd;
                page-break-inside: avoid;
            }
            
            header, footer {
                display: none;
            }
            .brand-image {
                display: block;
                margin: 8px auto;
                max-width: 60px;
                height: auto;
            }
        }
        .brand-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 8px auto;
}
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1> <div class="school-logo">
    <img src="path-to-your-logo-image.png" alt="UMT School of Pharmacy" style="max-height: 80px;">
</div>CARVEDILOL</h1>
            <div class="pronunciation">Pronunciation: "KAR-vuh-DIH-lol"</div>
        </div>
    </header>
    
    <div class="container">
        <div class="card">
            <h2>Basic Information</h2>
            <p><strong>Generic name:</strong> Carvedilol</p>
            
            <div class="chemistry-box">
                <h3>Chemistry</h3>
                <p><strong>Chemical name:</strong> (R,S)-1-(Carbazol-4-yloxy)-3-[[2-(O-methoxyphenoxy)ethyl]amino]-2-propanol</p>
                <p><strong>Molecular formula:</strong> C<sub>24</sub>H<sub>26</sub>N<sub>2</sub>O<sub>4</sub></p>
                <p><strong>Molecular weight:</strong> 406.5</p>
                <p><strong>pK<sub>a</sub> (at 25°C):</strong> 7.9</p>
            </div>
            
            <h3>Solubility</h3>
            <ul>
                <li><strong>In ethanol and methanol:</strong> slightly soluble</li>
                <li><strong>In water and buffer (≥ pH 7):</strong> practically insoluble</li>
                <li><strong>Octanol/water partition coefficient:</strong> 3.8</li>
            </ul>
            
            <p>Carvedilol is a colorless, crystalline substance prepared by chemical synthesis. It is optically active, the racemate being used clinically. Carvedilol is not currently present in any combination products.</p>
        </div>
        
        <div class="card">
            <h2>Mechanism of Action</h2>
            <p>A cardiovascular agent for the treatment of congestive heart failure that combines beta-adrenoceptor blockade and vasodilation in a single racemic mixture.</p>
            
            <ul>
                <li>Nonselective beta-adrenoceptor blocking activity is present in the <strong>S(-)</strong> enantiomer</li>
                <li>Alpha1-adrenoceptor blocking activity is present at equal potency in both the <strong>R(+)</strong> and <strong>S(-)</strong> enantiomers</li>
                <li>Has no intrinsic sympathomimetic activity</li>
                <li>Action on beta-receptors is <strong>10 times</strong> stronger than on alpha1-receptors</li>
                <li>Reduces peripheral vascular resistance by vasodilation, causing a fall in systemic blood pressure after acute administration (predominantly mediated through selective alpha1-antagonism)</li>
                <li>Beta blockade prevents reflex tachycardia, with the net result that heart rate is unchanged or decreased</li>
                <li>Reduces renin release through beta blockade</li>
            </ul>
        </div>
        
        <div class="card">
            <h2>Indications and Clinical Use</h2>
            <ul>
                <li>Treatment of mild, moderate, or severe heart failure of ischemic or non-ischemic origin to increase survival</li>
                <li>Reduce the combined risk of all-cause mortality and cardiovascular or non-cardiovascular hospitalizations</li>
                <li>Used in <strong>angina pectoris</strong> and <strong>congestive heart failure</strong></li>
            </ul>
            
            <div class="warning">
                <h3>Important Considerations</h3>
                <p>❖ CARVEDILOL should be prescribed by a physician experienced in the treatment of heart failure.</p>
                <p>❖ CARVEDILOL is used in conjunction with diuretics and an ACE inhibitor, with or without digitalis.</p>
                <p><strong>FDA pregnancy class:</strong> Category C (should be used during pregnancy only if the potential benefit justifies the potential risk to the fetus).</p>
            </div>
            
            <h3>Off-Label Uses</h3>
            <ul>
                <li>Stable angina</li>
                <li>Atrial fibrillation</li>
                <li>Cirrhotic esophageal variceal bleeding prophylaxis</li>
                <li>Ventricular arrhythmias</li>
            </ul>
            <p>These off-label uses can generally be <strong>extrapolated to most beta blockers</strong> rather than being specific to carvedilol alone.</p>
        </div>
        
        <div class="card">
            <h2>Pharmacokinetics</h2>
            
            <h3>Absorption</h3>
            <p>Carvedilol is rapidly absorbed after oral administration, reaching peak plasma concentrations at 1 hour in fasting subjects. Its absolute bioavailability is about 25–35% due to significant first-pass metabolism. Plasma concentrations are dose-proportional. Food slows the absorption rate, delaying peak concentration to about 2.3 hours, without affecting overall bioavailability.</p>
            
            <h3>Distribution</h3>
            <p>Carvedilol is highly bound to plasma proteins (over 98%), mainly to albumin, with binding independent of concentration across the therapeutic range. It is a basic, lipophilic compound with a steady-state volume of distribution of approximately 1.5 L/kg. Carvedilol has a terminal elimination half-life of 7 to 10 hours and a plasma clearance of 500 to 700 mL/min.</p>
            
            <h3>Metabolism</h3>
            <p>It is extensively metabolized, with less than 2% excreted unchanged in urine. Metabolism occurs mainly through glucuronidation and aromatic ring oxidation via CYP2D6 and CYP2C9.</p>
            
            <h3>Elimination</h3>
            <p>Metabolites are primarily excreted in bile into the feces. Elimination is mainly biliary. The primary route of excretion is via the feces. A minor part is eliminated via the kidneys in the form of various metabolites.</p>
        </div>
        
        <div class="card">
            <h2>Administration</h2>
            
            <h3>Available Dosage Forms and Strengths</h3>
            <p>Carvedilol is administered orally as immediate-release (twice daily) or controlled-release (once daily). Dosage is individualized based on blood pressure and heart rate response. For heart failure, guideline-directed medical therapy (GDMT) is followed.</p>
            
            <h3>Adult Dosage</h3>
            
            <table class="dosage-table">
                <thead>
                    <tr>
                        <th>Condition</th>
                        <th>Initial Dose</th>
                        <th>Titration</th>
                        <th>Maximum Dose</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Heart Failure</strong></td>
                        <td>3.125 mg twice daily</td>
                        <td>Double dose every 2 weeks to 6.25 mg, 12.5 mg, then 25 mg twice daily</td>
                        <td>25 mg twice daily (50 mg/day)</td>
                    </tr>
                    <tr>
                        <td><strong>Left Ventricular Dysfunction Post-MI</strong></td>
                        <td>6.25 mg twice daily</td>
                        <td>Titrate to 12.5 mg then 25 mg twice daily over 3-10 days</td>
                        <td>25 mg twice daily</td>
                    </tr>
                    <tr>
                        <td><strong>Hypertension</strong></td>
                        <td>6.25 mg twice daily</td>
                        <td>Titrate to 12.5 mg then 25 mg twice daily over 1-2 weeks</td>
                        <td>25 mg twice daily (up to 100 mg/day for patients >85 kg)</td>
                    </tr>
                </tbody>
            </table>
            
            <div class="warning">
                <p>For heart failure: Lower doses should be maintained if higher doses are not tolerated.</p>
                <p>For post-MI: Lower starting doses or slower titration may be considered.</p>
            </div>
            
            <h3>Specific Patient Populations</h3>
            
            <h4>Hepatic Impairment</h4>
            <p>Carvedilol may be used in patients with ascites for primary and secondary prophylaxis of variceal bleeding. Close monitoring is essential for hypotension, renal function, and infections.</p>
            <div class="danger">
                <p><strong>Contraindicated</strong> in severe or refractory ascites. No dose adjustment is needed for mild-to-moderate hepatic impairment, but it is <strong>contraindicated</strong> in severe hepatic impairment.</p>
            </div>
            
            <h4>Renal Impairment</h4>
            <p>No dosage adjustment is required for renal impairment.</p>
            
            <h4>Pregnancy Considerations</h4>
            <p>Though lowering BP below 140/90 mm Hg reduces adverse pregnancy outcomes, <strong>labetalol</strong> is the recommended antihypertensive in pregnancy, not carvedilol.</p>
            
            <h4>Breastfeeding Considerations</h4>
            <p>Carvedilol has minimal renal excretion and no significant accumulation in breastfed infants. Due to limited clinical data, alternative drugs are preferred, especially in preterm infants.</p>
            
            <h4>Pediatric Patients</h4>
            <p>Carvedilol is <strong>not FDA approved</strong> for pediatric use but is used <strong>off-label</strong> in pediatric heart failure.</p>
            
            <h4>Older Patients</h4>
            <p>Caution is advised in older patients, particularly when switching from immediate-release to controlled-release formulations.</p>
        </div>
        
        <div class="card">
            <h2>Side Effects</h2>
            
            <h3>Common Side Effects</h3>
            <div class="side-effects">
                <div class="effect-card common-effect">
                    <h4>Hypotension</h4>
                    <p>Low blood pressure, particularly during initiation or dose increases</p>
                </div>
                <div class="effect-card common-effect">
                    <h4>Dizziness</h4>
                    <p>Especially when standing up quickly (orthostatic hypotension)</p>
                </div>
                <div class="effect-card common-effect">
                    <h4>Fatigue</h4>
                    <p>General tiredness and lack of energy</p>
                </div>
                <div class="effect-card common-effect">
                    <h4>Headache</h4>
                    <p>Usually mild to moderate in intensity</p>
                </div>
            </div>
            
            <h3>Adverse Effects</h3>
            <p>Carvedilol is generally well-tolerated, with fewer frequent adverse events than other beta-blockers; adverse events are usually dose-related.</p>
            
            <div class="side-effects">
                <div class="effect-card">
                    <h4>Cardiovascular</h4>
                    <p>Bradycardia, AV block, worsening heart failure</p>
                </div>
                <div class="effect-card">
                    <h4>Respiratory</h4>
                    <p>Dyspnea, bronchospasm (especially in patients with asthma/COPD)</p>
                </div>
                <div class="effect-card">
                    <h4>Neurological</h4>
                    <p>Malaise, asthenia, depression, memory loss</p>
                </div>
                <div class="effect-card">
                    <h4>Other</h4>
                    <p>Weight gain, impotence, dry eyes (in contact lens wearers)</p>
                </div>
                <div class="effect-card serious-effect">
                    <h4>Hepatotoxicity</h4>
                    <p>Rare; mild aminotransferase elevations (&lt;2%) are typically asymptomatic and resolve without stopping therapy</p>
                </div>
                <div class="effect-card serious-effect">
                    <h4>Withdrawal Effects</h4>
                    <p>Abrupt discontinuation may lead to rebound hypertension</p>
                </div>
            </div>
            
            <div class="warning">
                <p>Only 7% of patients discontinued treatment due to adverse events in post-marketing surveillance.</p>
                <p>The most common adverse effect is <strong>hypotension</strong>, causing dizziness, lightheadedness, fatigue, and headaches.</p>
            </div>
        </div>
        
        <div class="card">
            <h2>Drug Interactions</h2>
            
            <h3>Overview</h3>
            <p>Carvedilol undergoes substantial oxidative metabolism, so plasma concentrations may be affected by cytochrome P450 inducers or inhibitors.</p>
            
            <table class="interaction-table">
                <thead>
                    <tr>
                        <th>Interacting Drug</th>
                        <th>Effect</th>
                        <th>Management</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Rifampin</strong></td>
                        <td>Reduced carvedilol's AUC and Cmax by ~70%</td>
                        <td>Monitor effectiveness, may need dose adjustment</td>
                    </tr>
                    <tr>
                        <td><strong>Cimetidine</strong></td>
                        <td>Increased AUC by 30% without changing peak plasma levels</td>
                        <td>Monitor for increased effects</td>
                    </tr>
                    <tr>
                        <td><strong>Antidepressants</strong> (fluoxetine, paroxetine, duloxetine, bupropion)</td>
                        <td>Inhibit CYP2D6, may increase carvedilol levels</td>
                        <td>Increased risk of hypotension, bradycardia, and falls</td>
                    </tr>
                    <tr>
                        <td><strong>Digoxin</strong></td>
                        <td>Both reduce heart rate and AV conduction</td>
                        <td>Increased risk of bradycardia</td>
                    </tr>
                    <tr>
                        <td><strong>Clonidine</strong></td>
                        <td>May cause severe hypotension and bradycardia</td>
                        <td>Carvedilol should be discontinued before clonidine, which must be tapered gradually</td>
                    </tr>
                    <tr>
                        <td><strong>Cyclosporine</strong></td>
                        <td>Levels increase with carvedilol due to P-glycoprotein inhibition</td>
                        <td>Close monitoring of cyclosporine levels needed</td>
                    </tr>
                    <tr>
                        <td><strong>Amiodarone</strong></td>
                        <td>Inhibits CYP2C9 and P-glycoprotein, increasing S(-) enantiomer</td>
                        <td>Enhanced beta-blockade, risk of bradycardia or heart block</td>
                    </tr>
                    <tr>
                        <td><strong>Non-dihydropyridine CCBs</strong> (verapamil, diltiazem)</td>
                        <td>May cause bradycardia and hemodynamic compromise</td>
                        <td>ECG and BP monitoring advised</td>
                    </tr>
                    <tr>
                        <td><strong>Insulin/Oral Hypoglycemics</strong></td>
                        <td>May increase hypoglycemic effects</td>
                        <td>Regular blood glucose monitoring recommended</td>
                    </tr>
                    <tr>
                        <td><strong>Catecholamine-depleting agents</strong> (reserpine, MAOIs)</td>
                        <td>Risk of hypotension and/or marked bradycardia</td>
                        <td>Close monitoring required</td>
                    </tr>
                </tbody>
            </table>
            
            <h3>Drug-Food Interactions</h3>
            <div class="warning">
                <h4>Grapefruit Juice</h4>
                <p>Co-administration of 25 mg carvedilol with 300 mL grapefruit juice increased AUC by approximately 16% compared to water, due to CYP3A4 and CYP1A2 inhibition.</p>
            </div>
            
            <h3>Drug-Herb Interactions</h3>
            <p>Interactions with herbal products have not been established.</p>
        </div>
        
        <div class="card">
            <h2>Contraindications</h2>
            
            <div class="danger">
                <p>Carvedilol is contraindicated in patients with:</p>
                <ul>
                    <li>Decompensated cardiac failure requiring IV inotropic therapy with sympathomimetic agents</li>
                    <li>Bronchial asthma or related bronchospastic conditions</li>
                    <li>Second- or third-degree AV block, or sick sinus syndrome (unless a permanent pacemaker is in place)</li>
                    <li>Cardiogenic shock</li>
                    <li>Severe hypotension</li>
                    <li>Severe bradycardia</li>
                    <li>Primary obstructive valvular heart disease</li>
                    <li>Clinically manifest hepatic impairment (e.g., jaundice, ascites, spider angiomata, esophageal varices)</li>
                    <li>Mental incapacity (e.g., severe Alzheimer's, alcoholism, drug abuse) unless closely supervised</li>
                    <li>Hypersensitivity to carvedilol or any component of CARVEDILOL</li>
                </ul>
            </div>
        </div>
        
        <div class="card">
            <h2>Patient Information</h2>
            
            <div class="success">
                <h3>Important Instructions</h3>
                <ul>
                    <li>Take CARVEDILOL exactly as your doctor instructs</li>
                    <li>Your doctor will decide the number of tablets, the schedule, and the duration</li>
                    <li>The dose may be increased or decreased based on your response</li>
                    <li>Swallow the tablets whole with water; <strong>do not chew or break</strong> them</li>
                    <li>Take your tablets <strong>at the same time each day</strong></li>
                    <li><strong>Always take CARVEDILOL with food</strong></li>
                    <li><strong>Do not stop</strong> taking CARVEDILOL without consulting your doctor</li>
                </ul>
            </div>
            
            <h3>Overdose</h3>
            <div class="danger">
                <p>If you have taken <strong>more tablets than the recommended dose</strong>, inform your doctor or go to the <strong>nearest hospital emergency department immediately</strong>.</p>
                <p>Bring your <strong>bottle of CARVEDILOL tablets</strong> and <strong>any other medications</strong> you are taking to show the healthcare provider.</p>
            </div>
            
            <h3>Missed Dose</h3>
            <div class="warning">
                <ul>
                    <li><strong>Take the missed dose as soon as you remember</strong></li>
                    <li>If possible, take your <strong>next dose at the normal time</strong>, but <strong>do not take two doses within 6 hours of each other</strong></li>
                    <li>If you miss <strong>more than 2 doses</strong>, contact your doctor</li>
                    <li><strong>Do not restart CARVEDILOL</strong> until you have spoken with your doctor</li>
                </ul>
            </div>
            
            <h3>Side Effects Management</h3>
            <p>Carvedilol may cause dizziness, headache, tiredness, and stomach issues, especially at the start or with dose changes. Other possible side effects include breathing problems, slow heart rate, swelling, cold limbs, weight gain, and sleep or mood changes.</p>
            <div class="warning">
                <p>These effects often improve with continued use, but medical advice should be sought if symptoms worsen. Avoid driving if dizzy or fatigued. If you wear contact lenses you may suffer from dryness of the eyes while taking your tablets.</p>
            </div>
        </div>
        
        <div class="card">
            <h2>Brand Names</h2>
            
            <div class="brands-container">
                <div class="brand-card">
                    <div class="brand-name">CURALOV</div>
                     <img src="C:\Users\bashi\Downloads\curalov.jpg" alt="CURALOV" class="brand-image" />
                    <div class="brand-dose">25 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">Delaware</div>
                     <img src="C:\Users\bashi\Downloads\Delaware.jpg" alt="Delaware" class="brand-image" />
                    <div class="brand-dose">6.25 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">Carloc</div>
                     <img src="C:\Users\bashi\Downloads\carloc.jpg" alt="CARLOC" class="brand-image" />
                    <div class="brand-dose">3.125 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">Dilatrend</div>
                     <img src="C:\Users\bashi\Downloads\dilatrend.jpg" alt="Dilatrend" class="brand-image" />
                    <div class="brand-dose">25 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">Hart</div>
                     <img src="C:\Users\bashi\Downloads\Hart.jpg" alt="Hart" class="brand-image" />
                    <div class="brand-dose">6.25 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">VEDICAR</div>
                     <img src="C:\Users\bashi\Downloads\vadecar.jpg" alt="VEDICAR" class="brand-image" />
                    <div class="brand-dose">12.5 mg</div>
                </div>
                <div class="brand-card">
                    <div class="brand-name">CARPRO</div>
                     <img src="C:\Users\bashi\Downloads\capro.jpg" alt="CARPRO" class="brand-image" />
                    <div class="brand-dose">25 mg</div>
                </div>
            </div>
        </div>
        
        <a href="#" class="back-to-top">Back to Top</a>
    </div>
    
    <footer>
        <div class="container">
            <p>Carvedilol Drug Information - Pharmacy Student Project</p>
            <p>This information is for educational purposes only and should not replace professional medical advice.</p>
        </div>
    </footer>
    
    <script>
        // Smooth scrolling for back to top button
        document.querySelector('.back-to-top').addEventListener('click', function(e) {
            e.preventDefault();
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Show/hide back to top button based on scroll position
        window.addEventListener('scroll', function() {
            const backToTopButton = document.querySelector('.back-to-top');
            if (window.pageYOffset > 300) {
                backToTopButton.style.display = 'inline-block';
            } else {
                backToTopButton.style.display = 'none';
            }
        });
    </script>
</body>
</html>
