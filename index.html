import random
from datetime import datetime

# Define exercise routines based on goals
exercise_routines = {
    'penurunan berat badan': {
        'pemula': ['Berjalan', 'Bodyweight squats', 'Berbasikal', 'Lompat bintang'],
        'pertengahan': ['Joging', 'Lunges', 'HIIT', 'Mountain climbers'],
        'mahir': ['Berlari', 'Burpees', 'Box jumps', 'Plyometric exercises']
    },
    'penambahan otot': {
        'pemula': ['Push-ups', 'Bodyweight squats', 'Dumbbell press', 'Lat pulldowns'],
        'pertengahan': ['Bench press', 'Deadlifts', 'Pull-ups', 'Overhead press'],
        'mahir': ['Squat jumps', 'Clean and press', 'Snatches', 'Barbell deadlift']
    },
    'ketahanan': {
        'pemula': ['Berjalan', 'Jogging ringan', 'Berenang', 'Berbasikal'],
        'pertengahan': ['Berlari', 'latihan litar', 'Rowing', 'Kettlebell swings'],
        'mahir': ['Latihan maraton', 'HIIT', 'CrossFit WODs', 'Spinning classes']
    },
    'kelenturan': {
        'pemula': ['pose yoga', 'Stretching exercises', 'Pilates basics'],
        'pertengahan': ['Yoga flow', 'Dynamic stretching', 'Advanced Pilates'],
        'mahir': ['Acro yoga', 'Ballet flexibility exercises', 'Deep stretching', 'Advanced Pilates']
    }
}

# Define nutrition recommendations based on goals
nutrition_recommendations = {
    'penurunan berat badan': [
        "Sarapan: Oatmeal dengan buah segar",
        "Makan tengah hari: Salad dengan ayam panggang",
        "Makan malam: Ikan kukus dengan sayuran hijau",
        "Snek: Yogurt rendah lemak atau kacang badam"
    ],
    'penambahan otot': [
        "Sarapan: Telur hancur dengan roti gandum",
        "Makan tengah hari: Ayam panggang dengan nasi perang dan brokoli",
        "Makan malam: Daging lembu tanpa lemak dengan kentang manis",
        "Snek: Protein shake atau keju cottage"
    ],
    'ketahanan': [
        "Sarapan: Smoothie dengan pisang, bayam, dan protein",
        "Makan tengah hari: Pasta gandum dengan ayam dan sayuran",
        "Makan malam: Salmon panggang dengan quinoa",
        "Snek: Bar tenaga atau buah segar"
    ],
    'kelenturan': [
        "Sarapan: Roti bakar dengan alpukat",
        "Makan tengah hari: Sup lentil dengan sayuran",
        "Makan malam: Tofu panggang dengan nasi perang",
        "Snek: Campuran kacang dan biji-bijian"
    ]
}

# User Profile class with support for multiple goals
class UserProfile:
    def __init__(self, name, goals, fitness_level):
        self.name = name
        self.goals = goals  # A list of goals
        self.fitness_level = fitness_level
        self.progress = {goal: 0 for goal in goals}
        self.sleep_quality = 'baik'  # Default sleep quality (good, poor)
        self.stress_level = 'rendah'  # Default stress level (low, high)
        self.available_time = 60  # Default available time for workouts (in minutes)
        self.slot_duration = 15  # Default slot duration

    def set_sleep_quality(self, quality):
        self.sleep_quality = quality

    def set_stress_level(self, level):
        self.stress_level = level

    def set_available_time(self, time):
        self.available_time = time

    def set_slot_duration(self, duration):
        self.slot_duration = duration

# Generate dynamic schedule for all selected goals
def generate_dynamic_schedule(user):
    print("\nGenerating your dynamic workout schedule...")
    schedule = []
    total_time = user.available_time
    slot_duration = user.slot_duration
    num_slots = total_time // slot_duration
    remaining_time = total_time % slot_duration
    goal_index = 0

    # Adjust intensity based on sleep and stress levels
    if user.sleep_quality == 'teruk' or user.stress_level == 'tinggi':
        adjusted_level = 'pemula'
    else:
        adjusted_level = user.fitness_level

    for slot in range(num_slots):
        current_goal = user.goals[goal_index % len(user.goals)]
        workout = random.choice(exercise_routines[current_goal][adjusted_level])
        schedule.append(f"Slot {slot + 1} ({slot_duration} min): {workout}")
        goal_index += 1

    if remaining_time > 0:
        current_goal = user.goals[goal_index % len(user.goals)]
        workout = random.choice(exercise_routines[current_goal][adjusted_level])
        schedule.append(f"Slot {num_slots + 1} ({remaining_time} min): {workout}")

    return schedule

# Suggest nutrition plan for all selected goals
def suggest_nutrition(user):
    print("\nSaranan Pemakanan Anda Berdasarkan Matlamat:")
    for goal in user.goals:
        print(f"\nMatlamat: {goal.capitalize()}")
        recommendations = nutrition_recommendations[goal]
        for item in recommendations:
            print(f"- {item}")

# Main function to simulate interaction
def fitness_system():
    print("Selamat datang ke Sistem Saranan Kecergasan!")
    name = input("Masukkan nama anda: ").strip()
    
    goals_input = input(
        "Masukkan matlamat kecergasan anda, pisahkan dengan koma (penambahan otot, penurunan berat badan, ketahanan, kelenturan): "
    ).strip().lower()
    goals = [goal.strip() for goal in goals_input.split(",")]
    
    fitness_level = input("Masukkan tahap kecergasan anda (pemula, pertengahan, mahir): ").strip().lower()

    # Create user profile
    user = UserProfile(name, goals, fitness_level)

    # Simulate sleep and stress levels
    sleep_quality = input("Bagaimanakah kualiti tidur anda semalam? (baik, teruk): ").strip().lower()
    user.set_sleep_quality(sleep_quality)
    
    stress_level = input("Bagaimana tahap tekanan stres anda hari ini? (rendah, tinggi): ").strip().lower()
    user.set_stress_level(stress_level)

    # Set available time for workout
    available_time = int(input("Berapa banyak masa yang anda ada untuk bersenam hari ini (dalam minit)? ").strip())
    user.set_available_time(available_time)

    # Set slot duration
    slot_duration = int(input("Berapa lama durasi untuk setiap slot senaman (dalam minit)? ").strip())
    user.set_slot_duration(slot_duration)

    # Generate and display the dynamic schedule
    dynamic_schedule = generate_dynamic_schedule(user)
    print("\nBerikut ialah jadual senaman dinamik anda untuk hari ini:")
    for slot in dynamic_schedule:
        print(slot)

    # Suggest nutrition plan
    suggest_nutrition(user)

if __name__ == "__main__":
    fitness_system()
