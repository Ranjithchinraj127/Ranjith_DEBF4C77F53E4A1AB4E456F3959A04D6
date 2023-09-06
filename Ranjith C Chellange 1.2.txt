#leap year
def isleapYear(Year):
   if (Year %4 ==0 and Year % 100 != 0) or Year %  400 == 0:
      return True
   else:
    return False

Year = 2013
     
if isleapYear(Year):
  print('{} is a leap Year.'.format(Year))
else:
  print('{} is not a leap Year.'.format(Year))
     