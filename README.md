import random

def stellar_galaxy_exploration():
    print("Welcome to the Stellar Galaxy Adventure!")
    print("You find yourself aboard a starship, navigating through the wonders of a distant galaxy.")

    while True:
        print("\nYou navigate through the stellar expanse...")
        input("Press Enter to continue your journey...")

        event = random.randint(1, 3)

        if event == 1:
            print("You discover a lush planet with vibrant alien flora and fauna.")
            choice = input("Do you wish to land and explore? (yes/no): ").lower()
            if choice == 'yes':
                explore_planet()
        elif event == 2:
            print("A mysterious signal leads you to an abandoned space station.")
            choice = input("Do you investigate the station? (yes/no): ").lower()
            if choice == 'yes':
                investigate_station()
        elif event == 3:
            print("Your ship encounters a cosmic anomaly, warping spacetime around you.")
            choice = input("Do you attempt to study the anomaly? (yes/no): ").lower()
            if choice == 'yes':
                study_anomaly()

        choice = input("\nContinue your stellar journey? (yes/no): ").lower()
        if choice != 'yes':
            break

    print("\nYour stellar adventure concludes.")
    print("Thank you for exploring the wonders of the galaxy!")

def explore_planet():
    print("\nYou land on the lush planet...")
    print("Exploring the diverse ecosystems, you uncover ancient ruins and encounter friendly alien creatures.")

def investigate_station():
    print("\nYou dock at the abandoned space station...")
    print("Inside, you find remnants of a lost civilization and recover valuable technology.")

def study_anomaly():
    print("\nYou divert course to study the cosmic anomaly...")
    print("As you analyze the anomaly, you gain new insights into the fabric of spacetime.")

# Start the stellar galaxy exploration
stellar_galaxy_exploration()
