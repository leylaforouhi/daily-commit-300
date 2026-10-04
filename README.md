
def fibonacci_sequence(count):
    sequence = []
    a, b = 0, 1

    for _ in range(count):
        sequence.append(a)
        a, b = b, a + b

    return sequence


if __name__ == "__main__":
    count = 10

    print("Count:", count)
    print("Fibonacci sequence:", fibonacci_sequence(count))
