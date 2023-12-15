
class Uzayli:
    def __init__(self, ad):
        self.ad = ad
        self.can = 100
        self.guc = 20

    def savas(self):
        saldiri_gucu = random.randint(1, self.guc)
        return saldiri_gucu

class Insan:
    def __init__(self, ad):
        self.ad = ad
        self.can = 100
        self.guc = 15
