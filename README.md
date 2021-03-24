# Pilot-system.py
altitude=int(input("Enter the present height of plane above sea level in ft. : "))
if altitude <= 3000 :
  print("Captain! We can safely land. ")
elif altitude >3000 and altitude <6000 :
  print("Captain! We can atleast try to land.I believe you can do it.")
else :
  print("Opps!Captain!No way , Turn around and Try to land from some other place.")


