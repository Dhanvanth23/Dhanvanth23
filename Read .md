
BEGIN
READ values of num1,num2,num3
IF num1>num2 THEN
  DISPLAY num1
ELSE
  DISPLAY num3
ENDIF
ELSE
  IF num2>num3 THEN
    DISPLAY num2
  ELSE
    DISPLAY num3
  ENDIF
ENDIF
END
