//=============================================================================
// Project Lynxmotion Phoenix - Quadruped Adaptation
// Software version: V1.0
// Date: May 06, 2013
// Programmers: Jeroen Janssen [aka Xan]
//             Kurt Eckhardt(KurtE) converted to C and Arduino
//             Kåre Halvorsen aka Zenta - Makes everything work correctly!     
//
// This version of the Phoenix code was ported over to the Arduino Environement
// and is specifically configured for the Lynxmotion BotBoarduino
//
// The code is meant to be used with the QBK-02 12DoF quadruped and the 
// RC-01 V2 PS2 controller with level shifter.
//
//=============================================================================
//
//KNOWN BUGS:
//    - Lots
//
//=============================================================================
// Header Files
//=============================================================================

#define DEFINE_HEX_GLOBALS
#if ARDUINO>99
#include <Arduino.h>
#else
#endif
#include <Wire.h>
#include <EEPROM.h>
#include <PS2X_lib.h> // Include PS2 library

#include <SoftwareSerial.h>
#include "Hex_CFG.h"  // Include hexapod configuration
#include <Phoenix.h>
#include <Phoenix_Input_PS2.h>
#include <Phoenix_Driver_SSC32.h>
#include <Phoenix_Code.h>
