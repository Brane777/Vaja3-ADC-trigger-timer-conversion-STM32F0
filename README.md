# Vaja3-ADC-trigger-timer-conversion-STM32F0

Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PA1.

Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC_IN1.

Aktiviramo samo zeleno LED diodo na ustreznem izhodu PC9.

V Clock Configuration spremenimo APB1 Timer clock (MHz) na 16 MHz (pritisnemo ENTER). Kaj opazite? vse ostalo se nastavi na 16 Mhz, razen APB1 Periperial clock, ki se nastavi na 8 MHz

V razdelku TIM1, pod Counter Settings, bi radi časovniku spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko znaša ta vrednost? 16000. 

Komentar:
