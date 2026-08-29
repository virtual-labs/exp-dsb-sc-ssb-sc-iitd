<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body>
    <ol>
    <strong>Input Parameters:</strong>
    <p>Input <strong>Message Frequency (Hz)</strong>, <strong>Carrier Frequency (Hz),</strong> and <strong>Message Signal Gain</strong>:<br></p>
    <p>
        Begin by choosing the message signal gain, message and carrier frequencies using the provided slider inputs. 
        Adjust the sliders to set your desired frequency values.
    </p>
     <h3><strong>Steps:</strong></h3>
         <li>
      <strong>1. Generate Message Signal:</strong> 
      Click the <em>“Generate Message”</em> button to generate the message signal. 
    </li>
        <li>
      <strong>2. Generate Carrier Signal:</strong> 
      Click the <em>“Generate Carrier”</em> button to generate the carrier signal. 
    </li>
    <li>
    <strong>3. Generate Modulated Signal</strong>
        Once the frequencies are selected, click on the <em>"Generate Modulated Signal"</em> button. 
        This action will display the DSB-SC or SSB-SC modulated signal based on the selected modulation technique.
    </li>
    <li>
        <strong>4. View Frequency Spectrums</strong>
        If you wish to analyze the frequency components, click on the <em>"Show Frequency Spectrums"</em> button. 
        This will generate and display the frequency spectrums of the message signal, the modulated signal, and the demodulated signal.
    </li>
    <li>
    <strong>5. Perform Demodulation</strong>
        To recover the original message signal, click on the <em>"Perform Demodulation"</em> button. 
        This will execute the demodulation process and display the demodulated signal.
    </li>
    </ol>
    <p>
        Each step provides visual feedback, allowing you to observe the effects of modulation and demodulation in real-time.
    </p>
</body>
</html>
