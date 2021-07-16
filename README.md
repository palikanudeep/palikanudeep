# taking kilometers from the user
kilometeres = float(input("Enter value in kilometeres: "))

#conversion factor
conv_fac = 0.621371

#calculate miles
miles = kilometeres * conv_fac
print('%0.2f kilometeres is equal to %0.2f miles' %(kilometeres,miles))
