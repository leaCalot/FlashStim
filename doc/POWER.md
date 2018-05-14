# Output Power Estimation

While this device clearly has applications in a BDSM context to hurt people, it should stay within sane power limits.

## Compare to EMS

* Assumptions
 * Load impedance 500 Ohm (```R_min```)
 * 320V worst-case output voltage (```U_max```)
 * Frequency 10-100Hz

* Designed limits ```C_max```
 * 25uC above waist (transthoracic)
 * 75uC below waist (non-transthoracic)

* Subject to pulsewidth```dt = (U_max / R_min) * C_max```
 * ```dt``` = 16uS for 25uC
 * ```dt``` = 48uS for 75uC

## Compare to Cattle Prod

* Assumptions
 * Load impedance 500 Ohm (```R_min```)
 * 320V worst-case output voltage (```U_max```)
 * Frequency 1-10Hz

* Designed limits ```C_max```
 * 500uC close electrode pair (prod)

* Subject to pulsewidth```dt = (U_max / R_min) * C_max```
 * ```dt = 320uS```

# Firmware Plan

* Three operation modes
 * **Lea** (16uS up to 100Hz) ***default***
 * **Latex** (48uS up to 100Hz) ***disclaimer***
 * **Beating** (320uS up to 10Hz) ***disclaimer with at least 3 confirmations, needs physical access to unit, no remote activation***

* Make pulse output bi-phasic to maximize perception
* Add button on device for prod mode

# References

* [TENS Limit guidelines](http://www.calmtechnologies.com/default/assets/File/TN-S04-0001%20-%20TENS%20Test%20Limit%20Guidelines%20R0.pdf)
* [StimFit](https://mystimfit.com/principles-electrical-stimulation/)
* [Shock batons](https://en.wikipedia.org/wiki/Electroshock_weapon#Electric_shock_prods)
