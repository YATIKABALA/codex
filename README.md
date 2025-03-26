def fun(distance, time):#distance and time as input
    if time == 0:#Speed is not defined if time is zero, so we handle this case.
        return "Time cannot be zero"
    return distance / time #If time is valid, we divide distance by time to get speed.

# Example usage
distance = float(input("Enter distance (in meters): "))
time = float(input("Enter time (in seconds): "))

speed = fun(distance, time)
print(f"Speed: {speed} m/s")
