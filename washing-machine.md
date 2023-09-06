# Washing machine state

## START
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Door",
    "value"     :   "CLOSED"
}

## HEATWATER
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Level",
    "value"     :   "100"
}

## WASH
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Temp",
    "value"     :   "PASS"
}

## RINSE
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Function",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/app/get/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Function",
    "value"     :   "SPIN"
}

## FAULT
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FAULT"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Door",
    "value"     :   "OPEN"
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Level",
    "value"     :   "50"
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Temp",
    "value"     :   "WAIT"
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "MOTORFAILURE"
}

## FAULTCLEARED
topic:v1cdti/app/set/6420301002/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}