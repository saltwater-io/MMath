import numpy as np

def scale_array(a, num):
    for i in a:
        for j in i:
            j = j * num
    return a


def main():
    a = [[1, 2], [3, 4]]
    b = [[5, 6], [7, 8]]
    c = [[9],[10]]
    print("Matrix a:", a)
    print("Matrix b:", b)
    print("")
    print("A + B = \n",  np.add(a, b))
    print("")
    print("A - B = \n", np.subtract(a, b))
    print("")
    print("A * B = \n", np.multiply(a, b))
    print("")
    print("3A = \n", 3 * np.array(a))
    print("")
    print("A transpose = \n", np.matrix.transpose(np.matrix(a)))
    print("")
    print("A-Inverse = \n", np.linalg.inv(a))
    print("")
    print("A Rank: ", np.linalg.matrix_rank(a))
    print(" ")
    print("A det: ", np.linalg.det(a))

    print("\nGauss-Jordan method: \n", np.linalg.solve(a, c))


if __name__ == "__main__":
    main()
