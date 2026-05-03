#input
adCost = float(input('Enter advertising ($): '))
adType = input('Enter ad type (i=internet, r=radio): ')

#processing = common variables and calculations
fixedCost = 200
totalCost = fixedCost + adCost
baseAttendees = 20
ticketPrice = 10

#processing alternatives
if adType == 'r':
    addAttendees = 2*round(adCost**.5)
elif adType == 'i':
    addAttendees = 4*round(adCost**.3)
else:
    addAttendees = 0
print('Warning, unknown ad type:', adType)

#further processing
ticketSales = (baseAttendees+addAttendees)*ticketPrice
profit = ticketSales - totalCost
