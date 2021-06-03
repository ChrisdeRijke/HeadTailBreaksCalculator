# HeadTailBreaksCalculator
A tool for calculating head/tail breaks 2.0

see https://en.wikipedia.org/wiki/Head/tail_Breaks

For calculations using less than 10.000 datapoints use ExcelHTCalculatorOneColumn.xlsx and insert data into column A

For calculation using between 10.000 and 50.000 datapoints use ExcelHTCalculatorOneColumn50K.xlsx and insert data into column A

For calculations using more than 50.000 datapoints create a histogram of the data and use ExcelHTCalculatorTwoColumnsv6.xlsx with 
  column A being the "count" (i.e. amount of datapoints of a value)
  column B being the "value" (i.e. the value of the datapoint)
  
  Alternatively with less than 1.048.576 different values and datapoints a histogram need not be made and for input use
    column A being 1
    column B being the values of the datapoints
