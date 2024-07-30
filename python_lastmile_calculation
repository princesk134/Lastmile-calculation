#User shall adjust the weight value under variable named user_weight manually

user_weight = 41.5
flatcharge_ground_shipping = 20
flatcharge_ground_shipping_premium = 125

#Ground shipping calculation
if user_weight <= 2:
  cost_GS = user_weight * 1.5 + flatcharge_ground_shipping
elif user_weight <= 6:
  cost_GS = user_weight * 3 + flatcharge_ground_shipping
elif user_weight <= 10:
  cost_GS = user_weight * 4 + flatcharge_ground_shipping
elif user_weight > 10:
  cost_GS = user_weight * 4.75 + flatcharge_ground_shipping
print("ground shipping cost:", cost_GS, "USD")

#Ground shipping premium calculation
cost_GS_premium = flatcharge_ground_shipping_premium
print("ground shipping premium cost:", cost_GS_premium, "USD")

#Drone shipping calculation
if user_weight <= 2:
  cost_drone = user_weight * 4.5
elif user_weight <= 6:
  cost_drone = user_weight * 9
elif user_weight <= 10:
  cost_drone = user_weight * 12
elif user_weight > 10:
  cost_drone = user_weight * 14.25
print("drone shipping cost:", cost_drone, "USD")
