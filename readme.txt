def sigmoid(x, L ,x0, k, b):
    y = L / (1 + np.exp(-k*(x-x0)))+b
    return (y)

#y-> y value to be predicted
#L -> Max y value
#k -> Slope of the curve
#(x-x0) -> Slope of the curve

p0 = [max(ydata), np.median(xdata),1,min(ydata)]