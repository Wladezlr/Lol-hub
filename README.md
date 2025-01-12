class Player:
    def __init__(self, name):
        self.name = name
        self.credits = float('inf')  # Setting credits to infinity

    def show_credits(self):
        print(f"{self.name} has unlimited credits.")

    def spend_credits(self, amount):
        # Spending credits does not affect the total because it's infinite
        print(f"{self.name} spends {amount} credits.")

# Create a player with infinite credits
player = Player(name="Player1")

# Show player's credits
player.show_credits()

# Spend some credits
player.spend_credits(1000)
player.spend_credits(5000)

# Show player's credits again to confirm it's still infinite
player.show_credits()# Lol-hub
