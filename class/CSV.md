#Working with CSV files

##Reading
`with open(cereal_csv_path, newline='') as csvfile:`
    `csvreader = csv.reader(csvfile, delimiter=',')`
    `header = next(csvreader, None)`

    `for row in csvreader:`
        `[DO SOMETHING]`

##Writing
`with open(output_path, 'w', newline='') as csvfile:`
    `csvwriter = csv.writer(csvfile, delimiter=',')`

    `# Write the first row (column headers)`
    `csvwriter.writerow(['First Name', 'Last Name', 'SSN'])`

    `# Write the second row`
    `csvwriter.writerow(['Caleb', 'Frost'])`
