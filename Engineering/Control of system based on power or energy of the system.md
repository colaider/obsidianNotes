#controls 

Learned this from Aramis. He create a controller for AC/DC [[converter]] that controls output of this converter using PD [[controller]] with [[low-pass filter]] on derivative side. 

This controller outputs [[power]] of the system then divide this power by measured feedback [[voltage]] which results in a [[current]], this current go into simulated power [[electronic]]s.

Feedback that goes back into controller was a squared voltage because it simplifies and [[linear]]ises system due two power in [[capacitor]] formula.  