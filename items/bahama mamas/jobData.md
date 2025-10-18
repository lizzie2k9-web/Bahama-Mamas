-- QBCORE
bahamamamas = {
    label = 'Bahama Mamas',
    type = 'stripclub',
    defaultDuty = true,
    offDutyPay = undefined,
    grades = {
        ['1'] = {
            name = 'floor staff',
            payment = 250
        },
        ['2'] = {
            name = 'security',
            payment = 350
        },
        ['3'] = {
            name = 'bar staff',
            payment = 350
        },
        ['4'] = {
            name = 'head of security',
            payment = 500
         },
        ['5'] = {
            name = 'head manager',
            payment = 2000
        },
        ['6'] = {
            name = ' owner',
            payment = 4000
            isboss = true,
            bankAuth = true
        }
    },
},

-- QBOX
['bahamamamas'] = {
    label = 'Bahama Mamas',
    type = 'stripclub',
    defaultDuty = true,
    offDutyPay = undefined,
    grades = {
        [1] = {
            name = 'floor staff',
            payment = 250
        },
        [2] = {
            name = 'security',
            payment = 350
        },
        [3] = {
            name = 'bar staff',
            payment = 350
        },
        [4] = {
            name = 'head of security',
            payment = 500
 },
        [5] = {
            name = 'head manager',
            payment = 2000
        },
        [6] = {
            name = 'owner',
            payment = 4000,
            isboss = true,
            bankAuth = true
        }
    },
},

-- SQL Insert Statements
INSERT INTO `jobs` (name, label) VALUES
  ('bahamamamas', 'Bahama Mamas');

INSERT INTO `job_grades` (job_name, grade, name, label, salary, skin_male, skin_female) VALUES
  ('bahamamamas', 1, 'floor staff', 'floor staff', 250, '{}', '{}'),
  ('bahamamamas', 2, 'security', 'security', 350, '{}', '{}'),
  ('bahamamamas', 3, 'bar staff', 'bar staff', 350, '{}', '{}'),
  ('bahamamamas', 4, 'head of security', 'head of security', 500, '{}', '{}')
  ('bahamamamas', 5, 'head manager', 'head manager', 2000, '{}', '{}')
  ('bahamamamas', 6, 'owner', 'owner', 4000, '{}', '{}')
;
