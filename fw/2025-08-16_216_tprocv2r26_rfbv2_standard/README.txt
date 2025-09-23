QICK running on ZCU216, software version 0.2.365

Firmware configuration (built Sat Aug 16 12:14:08 2025):

	Global clocks (MHz): tProc dispatcher timing 430.080, RF reference 245.760
	Groups of related clocks: [tProc core clock, tProc timing clock, DAC tile 1, DAC tile 2, DAC tile 3], [DAC tile 0], [ADC tile 1, ADC tile 2]

	16 signal generator channels:
	0:	axis_signal_gen_v6 - fs=9584.640 Msps, fabric=599.040 MHz
		envelope memory: 65536 complex samples (6.838 us)
		32-bit DDS, range=9584.640 MHz
		DAC tile 0, blk 0 is 0_228 on JHC1, or QICK box DAC port 0
	1:	axis_signal_gen_v6 - fs=9584.640 Msps, fabric=599.040 MHz
		envelope memory: 16384 complex samples (1.709 us)
		32-bit DDS, range=9584.640 MHz
		DAC tile 0, blk 1 is 1_228 on JHC2, or QICK box DAC port 1
	2:	axis_signal_gen_v6 - fs=9584.640 Msps, fabric=599.040 MHz
		envelope memory: 32768 complex samples (3.419 us)
		32-bit DDS, range=9584.640 MHz
		DAC tile 0, blk 2 is 2_228 on JHC1, or QICK box DAC port 2
	3:	axis_signal_gen_v6 - fs=9584.640 Msps, fabric=599.040 MHz
		envelope memory: 16384 complex samples (1.709 us)
		32-bit DDS, range=9584.640 MHz
		DAC tile 0, blk 3 is 3_228 on JHC2, or QICK box DAC port 3
	4:	axis_sg_mixmux8_v1 - fs=6881.280 Msps, fabric=430.080 MHz
		32-bit DDS, range=1720.320 MHz
		DAC tile 1, blk 0 is 0_229 on JHC1, or QICK box DAC port 4
	5:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 16384 complex samples (38.095 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 1, blk 1 is 1_229 on JHC2, or QICK box DAC port 5
	6:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 1, blk 2 is 2_229 on JHC1, or QICK box DAC port 6
	7:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 16384 complex samples (38.095 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 1, blk 3 is 3_229 on JHC2, or QICK box DAC port 7
	8:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 2, blk 0 is 0_230 on JHC3, or QICK box DAC port 8
	9:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 2, blk 1 is 1_230 on JHC4, or QICK box DAC port 9
	10:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 2, blk 2 is 2_230 on JHC3, or QICK box DAC port 10
	11:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 2, blk 3 is 3_230 on JHC4, or QICK box DAC port 11
	12:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 3, blk 0 is 0_231 on JHC3, or QICK box DAC port 12
	13:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 3, blk 1 is 1_231 on JHC4, or QICK box DAC port 13
	14:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 3, blk 2 is 2_231 on JHC3, or QICK box DAC port 14
	15:	axis_sg_int4_v2 - fs=6881.280 Msps, fabric=430.080 MHz
		envelope memory: 8192 complex samples (19.048 us)
		32-bit DDS, range=1720.320 MHz
		DAC tile 3, blk 3 is 3_231 on JHC4, or QICK box DAC port 15

	11 readout channels:
	0:	axis_dyn_readout_v1 - configured by tProc output 4
		fs=2457.600 Msps, decimated=307.200 MHz, 32-bit DDS, range=2457.600 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 4096 decimated (13.333 us)
		triggered by tport 10, pin 0, feedback to tProc input 0
		ADC tile 2, blk 0 is 0_226 on JHC7, or QICK box ADC port 4
	1:	axis_dyn_readout_v1 - configured by tProc output 4
		fs=2457.600 Msps, decimated=307.200 MHz, 32-bit DDS, range=2457.600 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 4096 decimated (13.333 us)
		triggered by tport 11, pin 0, feedback to tProc input 1
		ADC tile 2, blk 2 is 2_226 on JHC7, or QICK box ADC port 6
	2:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 12, pin 0, feedback to tProc input 2
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	3:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 13, pin 0, feedback to tProc input 3
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	4:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 14, pin 0, feedback to tProc input 4
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	5:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 15, pin 0, feedback to tProc input 5
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	6:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 16, pin 0, feedback to tProc input 6
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	7:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 17, pin 0, feedback to tProc input 7
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	8:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 6, pin 0, feedback to tProc input -1
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	9:	axis_pfb_readout_v4 - configured by PYNQ
		fs=2457.600 Msps, decimated=38.400 MHz, 32-bit DDS, range=38.400 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 1024 decimated (26.667 us)
		triggered by tport 7, pin 0, feedback to tProc input -1
		ADC tile 2, blk 1 is 1_226 on JHC8, or QICK box ADC port 5
	10:	axis_dyn_readout_v1 - configured by tProc output 4
		fs=2457.600 Msps, decimated=307.200 MHz, 32-bit DDS, range=2457.600 MHz
		axis_avg_buffer v1.2 (has edge counter, no weights)
		memory 8192 accumulated, 4096 decimated (13.333 us)
		triggered by tport 18, pin 0, feedback to tProc input -1
		ADC tile 1, blk 0 is 0_225 on JHC5, or QICK box ADC port 0

	1 time-tagger blocks:
	0:	qick_time_tagger
		memories: 4096 time-tags (TAG), 1024 counts (ARM), 16384 samples (SMP)
		armed by tport 5, pin 0
		is tProc peripheral A
		1 ADC ports:
		  0_0: ADC tile 1, blk 1 is 1_225 on JHC6, or QICK box ADC port 1

	5 digital output pins:
	0:	SPARE0_1V8
	1:	SPARE1_1V8
	2:	SPARE2_1V8
	3:	SPARE3_1V8
	4:	SPARE4_1V8

	tProc: qick_processor ("v2") rev 26, core execution clock 215.040 MHz
		memories (words): program 4096, data 16384, waveform 1024
		external start pin: SPARE5_1V8
		external stop pin: None

	DDR4 memory buffer: 1073741824 samples (3.495 sec), 128 samples/transfer
		wired to readouts [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

	MR buffer: 8192 samples (3.333 us), wired to readouts [0, 1, 10]

QICK box daughter cards detected:
	ADC slot 0: DC In card has ports [0, 1]
	ADC slot 1: DC In card has ports [2, 3]
	ADC slot 2: RF In card has ports [4, 5]
	ADC slot 3: No card detected
	DAC slot 0: No card detected
	DAC slot 1: RF Out card has ports [4, 5, 6, 7]
	DAC slot 2: No card detected
	DAC slot 3: DC Out card has ports [12, 13, 14, 15]
